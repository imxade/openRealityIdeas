# A Vision For Extended Reality

These are just some initial thoughts on how a better Mixed Reality might be. 

Wanted a centralized platform where enthusiasts can collaborate, provide input, and share insights to shape this idea together. 
It doesn’t matter if nobody cares about our ideas, the goal is to build a catalog for storing, criticizing, and refining these ideas. With this approach, our brainstorming won’t go to waste (as has often been the case). Instead, if anyone ever asks us what our vision for XR would look like, we’ll have a reference beyond just rough ideas.

If any of us are ever in a position to shape the future of XR, we won’t need to brainstorm from scratch.

### Contributing to This Document

Do consider contributing to this markdown! Here’s how:

- **Add Your Ideas**: Share your own thoughts on how XR can evolve.
- **Challenge Existing Ideas**: Open issues to discuss improvements or alternative approaches, inviting community input.
- **Clarify or Elaborate**: Expand on existing ideas where more detail might help.
- **Improve Structure**: Suggest ways to categorize and organize this document more effectively.
- **Suggest Practical Implementations**: Offer specific ways to bring ideas to life.

> **Note:** Before creating a pull request (PR), may be consider opening an issue to involve the community in the discussion. PRs should relate to XR interface concepts.


## 1. Core Requirements

### 1.1 3D-First Interface
Rethink the interface from scratch for a 3D environment, instead of mimicking existing 2D interfaces from desktop or phone.

### 1.2 Gesture-Based Interaction
Make [hand gestures](https://www.interaction-design.org/literature/article/how-to-design-gesture-interactions-for-virtual-and-augmented-reality) the primary means of interaction, avoiding reliance on physical controllers.

### 1.3 Systemwide Standardization
Establish consistent settings for sensitivity, hand movements, and other interactions across all applications.

### 1.4 Predictable Confirmation
Ensure actions yield predictable outcomes, making interactions feel natural and reliable.

### 1.5 VR Conceptual Model
Develop a coherent model for users to understand navigation and interaction within the XR space.

## 2. Eye-Based Features

| Feature                     | Implementation Level | Description                                                                                   |
|-----------------------------|----------------------|-----------------------------------------------------------------------------------------------|
| **Zooming/Bionic Eye**      | Hardware             | Zooming functionality.                              |
| **Eye Tracking**            |              | Support for gaze-based interactions and precise navigation in the VR space. [Pupil Labs](https://github.com/pupil-labs/pupil)                      |
| **Eye Power Correction**    | Software             | Seeing the world through a screen should allow us to alter properties of image and change it's **focus** based on users' visual requirements.                           |
| **Eye Power Correction**    | Hardware             | Prescribed lenses or membranes with liquid adjustments for vision correction.            |


## 3. Privacy

### 3.1 Camera Access

Eliminate the possibility of the camera feed going online. This is vital as headsets have direct access to users' eye vision, making it hard to control what is being displayed compared to handset.
  
#### Option1: Third-party apps as extension 

A default interface/app to be extended by thirdparty apps.
- Other apps will serve as an extension to the default one, extending both functionality and interface.
- The default app will make use of extensions not the other wise, **thereby not allowing extensions to access the feed**.
  - For example: In case of an object detection app the functionality needs to be implemented in a standard way so the default app could utilize it to process the feed locally and the interface will be modified for user interaction. 

#### Option2: Offline camera apps

Simply, restrict connectivity of camera centric apps.
  
### 3.2 Video Streaming?

> We'll likely have to make an exception and make sure only receivers can decrypt the encrypted stream.

### 3.3 Sensor indications

Users will receive visible indication when the microphone or other sensors are in use.

## 4. Miscellaneous Features

### 4.1 Augmented Surface

Augmented planes within the XR space, providing customizable areas for various tasks. For example,

- Augmenting and tracking a selected plane area or object as a notepad for handwritten notes.

### 4.2 Independent connectivity

- eSIM


### 4.3 2D Interface Emulation

| Feature                  | Description                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------|
| **Mapped On-Screen Controls**   | Maps traditional on-screen controls from smartphones into the VR space, allowing users to interact with familiar layouts in a 3D environment.       |
| **Virtual Keyboard**     | A virtual keyboard that includes haptic/sound feedback to enhance typing accuracy and user experience in a spatial environment.               |
| **Virtual Mouse**        | A virtual mouse that enables cursor control via eye-tracking and hand gestures, enhancing precision for selections while providing haptic or auditory feedback for actions. |

## 5. Key Opportunities

Some incoming key opportunities with XR.

### 5.1 Web-Desktop (but not for Desktop)

- An opportunity exists to create a spatial “web desktop” where web apps will be the new native, unlike desktop elements.
- If we could package the backend within WebAssembly (WASM), most web applications should be able to serve locally; however, there will be limitations due to sandboxing (like no access to local files).

### 5.2 RISC-V

- This XR can be to RISC-V what Smartphones were to ARM, especially as XR hardware represents a new category of devices where open hardware standards may thrive.

### 5.3 Game Engine: Games + FrontEnd
- A unified approach to creating interfaces for both games and applications using game engines will also provide a real alternative to JavaScript fatigue.
