# VR-Notes
Notes for VR Quiz 2 based on Revision Lecture

## Development Tools from Revision
- Babylon.js can be used to build WebXR AR applications.

## Hardware & Software Components
- Describe common hardware components in XR devices
- Explain the image formation process in typical XR HMDs
- Describe common software components in immersive applications.
- Describe the architecture of a typical WebXR Application.

### Common Hardware Components
- It carries two 5.5-inch displays, as well as a 100-degree field-of-view, and internal sensors for head tracking (accelerometer, gyroscope, and compass)

- Lens Mounts
- HMD
- Motion tracking Chips
- LCD Screen
- Eyesight Correction Mounts
- Connection Interface.

### Image Formation Process in typical XR HMDs
[HMD](Images/HMD_Info.png)
[HMD2](Images/HMD2.png)

- Important Syntax:
    - w IPD: IPD stands for Interpupillary Distance, which refers to the distance between the centers of the pupils of the two eyes. In the context of virtual reality (VR), IPD width is a crucial factor for ensuring a comfortable and immersive experience
    - w Display: The length of the display mounted within the HMD.

- What does changing the focal length of the lenses in a HMD affect?
    - The size of the virtual image.
    - Vertical and horizontal FOV.

- What effect does using the same projection matrix for both displays (or display parititons) for both eyes in a VR HMD have?
    - NOT reduced cybersickness
    - NOT enlarged field of view
    - NOT reduced head-tracking accuracy that can induce cybersickness
    - NOT reducing in visual anomalies like ghosting or flickering.


### Describe Common Software Components in Immersive Applications
- What is the function of the debug layer in the scene class of Babylon.js
    - Allows the developer to visualize important scene information such as the positions, rotations, and bounding boxes of the mesh objects within the scene. The debug layer can also provide tools for monitoring and analyzing the performance of the scene, including fps, memory usuage and draw calls.
    - PhotoDome class in babylonjs: used to display a 360 degree panoramic image within a 3D scene. allowing developers to create immersive environments by wrapping the panoramic image around a sphere, enabling users to explore the scene from any angle.

#### Model-based Approach
- Hand made 3D models using 3D modelling tools. 
- Requires deep technical art expertise. 
- Enables full interactive interactions 
Pros:
- High fidelity
- Customization
- Interactivity
- Realism in terms of level of details. 

Cons:
- Complexity
- Performance overhead
- File size

### Interaction
- Viewpoint Control
Top priority. Helps to give a sense of presence
Passive interaction: Not done consciously
- Hand Gestures
- Body Gestures

#### Implementing Interaction
- ActionManager
Consists of a collection of actions, each representing a specific behavior of action that should occur when triggered. Customize interaction parameters (duration, conditions, triggers)
For example: an action action may be triggered when a user clicks on a mesh object, when 2 objects collide, or when a certain condition is met.

- Observables (Source)
Holds the state and notifies its observers when its state has been changed. It is responsible for managing and notifying its list of observers

Used in event driven programming paradigms such as GUIs, where UI elements (observables) notify listeners (observers) of user interactions or state changes.
- Observers
An object that subscribes to an Observable and receives notifications when the Observable's state changes. It defines a callback or handler function that is invoked by the Observable when conditions are met.

Used where objects need to react to changes in the state of other objects without being tightly coupled to them.
How many observers were used here (1)
In total, how many observables did we operate on? (1)
In total, how many observables did we create? (0)

- Pointer Drag Behavior
The ability to interactively drag and move objects within a 3D scene using mouse or touch inputs

The following code allows the sphere to be dragged around a plane perpendicular to the direction the player is viewing

Can you suggest an improvement to the "debug code" to get the position of the sphere only when it is being dragged? (add observer to the onDragObservable of pointerDragBehavior to get position)

- Movement
What happens when I change "timeToTeleport" to 0 in the following babylonjs code? (Teleportation triggers imediately when the button is pressed)