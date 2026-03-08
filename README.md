```
# Multimodal-User-Interfaces-Group-Project
Here are our ideas so far:

1. Hands-free VR toolkit that combines eye tracking, voice commands and motion inputs to enable a new way for navigation and object manipulation in VR.

Traditional VR relies heavily on hand controllers. In this project, our aim would be to investigate alternative interaction techniques that would allow the users to interact
with the virtual environment without relying entirely on their hands using eye tracking and speech as complementary input modalities.

This research is important because it could allow designers to explore and manipulate virtual environments more naturally without relyiong on handheld controllers. Voice and eye tracking
can also support users who have limited mobility or difficulty using controllers. Part of our project would be to assess whether something like this is practical and usable compared to traditional
controller-based interaction. 

Example interactions:

Hands-Free Navigation
- Look at a location and say "Go there" to teleport.
- Say "Move forward" and movement follows gaze direction.
- Say "Stop" to halt movement.

Object Selection
- Look at an object and say "Select this" to highlight it.
- Look at an object and say "Delete" to remove it.

Object Manipulation
- Look at an object and say "Move this", then look at another location and say "Place here".
- Look at an object and say "Scale up" to enlarge it.

Menu Navigation
- Look at a button on the menu and say "Click" to press it.
- Look at the menu and say "Close" to close the menu.

In summary, the project explores multimodal fusion, where gaze provides spatial context while voice commands trigger actions.



2. A multimodal VR interaction toolkit combining voice commands and motion-based interaction to manipulate virtual objects and environments.
   
Input Layer
   |
   |-- Microphone (Voice Recognition)
   |-- VR Controller / Hand Tracking
   |-- Headset Pose Tracking
   |
Interpretation Layer
   |
   |-- Speech parser
   |-- Gesture recognizer
   |-- Object pointing detection
   |
Fusion Layer
   |
   |-- Combine modalities
   |-- Resolve conflicts
   |
Application Layer
   |
   |-- VR Environment Toolkit
   |-- Object Manipulation

Here are some example actions you could do in the demo environment:

| Action        | Voice               | Movement             |
| ------------- | ------------------- | -------------------- |
| Spawn object  | "Create cube"       | —                    |
| Select object | "Select that"       | point at object      |
| Move object   | "Move"              | drag with controller |
| Scale object  | "Scale up"          | stretch gesture      |
| Reset scene   | "Reset environment" | press button         |

The idea is to manipulate the environment by either replacing certain button inputs with voice or create completely
new actions using voice together with movement and other inputs.


3. Our other option is to create a multimodal platformer game toolkit that combines the EEGs inputs and touch commands to move the character.

We have only two group members so far so we need to find 3 additional CS students or combine with another team.
```
