# S3D_QuickSwitch
Blender Add-on | A One-click solution to quickly switch between Editor Areas
# Documentation 

## INDEX  

**Click the links below to directly jump to desired chapter**

- [**Overview**](#overview) 
- [**Key Features**](#key-features) 
- [**Installation**](#installation)   
- [**Usage Instructions**](#usage-instructions)   
- [**Supported Editor Areas**](#supported-editor-areas)   
- [**Support & Feedback**](#support--feedback)   
- [**License**](#license)   
## Overview

**S3D_QuickSwitch** is a Blender addon designed for users with limited screen real estate, such as those working on laptops or single-monitor setups. The addon helps reduce UI clutter and allows users to get things done faster by offering a simple, efficient way to switch between different editor areas with just one click. It is especially useful for users who frequently navigate between Blender's various editors but want to maintain a clean and organized workspace.

## Preview

<img src="Preview/Addon_Cover.png" alt="Addon Cover">


## Key Features
- **Header Integration**: Quick switch buttons are automatically added to editor headers, allowing for a one-click solution to switch between editor areas without having to navigate menus.
- **Custom Editor Switching**: Define custom switches between editor areas, such as switching from the **3D Viewport** to the **Shader Editor**.
- **Two-Way Switching**: Optional two-way switching feature lets users toggle back and forth between editors with ease.
- **Simple UI**: A minimalistic interface in the preferences panel allows for easy configuration of switches.

<div style="display: flex; justify-content: space-between;">
  <img src="Preview/Preferences_Setup.png" alt="Preferences Setup 1" width="48%">
  <img src="Preview/Preferences_Setup_2.png" alt="Preferences Setup 2" width="48%">
</div>


## Installation

1. **Official Installation**:  

   Open Blender (**requires version 4.2 or above**), go to **Edit > Preferences > Get Extensions**, search for **"Quick Switch"** and click **Install** to install directly.  
    
3. **Alternate Installation**:

   Alternatively, visit the [Blender Extensions platform](https://extensions.blender.org/add-ons/s3d-quickswitch) and click **Get Add-on** to download from the Official page of the add-on.
   
   Or,
   
   Download the "S3D_QuickSwitch_vX.X.X.zip" file from the latest [Release](https://github.com/Silvie3D/S3D_QuickSwitch/releases).

5. Once installed, make sure the addon is enabled under the **Add-ons** tab in **Preferences**.  

6. Start creating switches and configure them to your liking!

## Usage Instructions

1. After enabling the addon, go to **Edit > Preferences > Add-ons** and locate the Add-on.
2. Click the **Add Switch** button to define a new editor switch.
3. Configure the following options for each switch:
   - **From Area**: Select the editor area you want to switch from (e.g., 3D Viewport).
   - **To Area**: Select the editor area to switch to (e.g., Shader Editor).
   - **Two-way**: Enabled by default, this option allows to switch between One-way and Two-way mode.
4. A switch button will appear in the header of the active editor area, allowing quick access to your configured switches.

### Example Setup:
- Create a switch from **3D Viewport** to **Shader Editor**.
- A button will appear in the **3D Viewport** and **Shader Editor** header right most end (Refer [Preview images](#preview) ), allowing you to switch instantly between then.

## Supported Editor Areas
- 3D Viewport
- Shader Editor
- Video Sequencer
- Properties
- Outliner
- Python Console
- Image Editor
- Text Editor
- And many more.

## Support & Feedback
For any questions, issues, or suggestions, please contact:
- **Maintainer**: Rabah Ahmed (Silvie3D)              
- **Email**: rabahahmed95@gmail.com

## License
© 2024 Silvie3D

**This addon is licensed under [GNU GENERAL PUBLIC LICENSE 3.0].**
