# Documentation
Blender Add-on | A One-click solution to quickly switch between Editor Areas

<img src="Preview/cover.png" alt="Addon Preview">



## INDEX

**Click the links below to directly jump to the desired chapter**

- [Documentation](#documentation)
  - [INDEX](#index)
  - [Overview](#overview)
  - [Key Features](#key-features)
  - [Installation](#installation)
    - [**Official Installation**](#official-installation)
    - [**Alternate method**](#alternate-method)
  - [Usage Instructions](#usage-instructions)
    - [**Creating Editor Groups**](#creating-editor-groups)
    - [**Using Quick Switch Buttons**](#using-quick-switch-buttons)
    - [**Example Setup**](#example-setup)
  - [Supported Editor Areas](#supported-editor-areas)
  - [Support \& Feedback](#support--feedback)
  - [License](#license)

---

## Overview

**Quick Switch** is a Blender add-on designed for users with limited screen space, such as those working on laptops or single-monitor setups. The addon helps reduce UI clutter and improves workflow efficiency by providing a one-click solution to switch between different editor areas.

With **v2.0.0**, the add-on has undergone a complete UI overhaul and now introduces **Grouped Editor** Switching feature, enabling users to define sets of editors and switch between them like browser tabs.


---

## Key Features

- **Header Integration**: Quick switch buttons are automatically added to right most end of the editor headers for seamless navigation.
 
   <img src="Preview/preview.png" alt="Addon Preview">

- **Grouped Editor Switching (New!)**: Users can define groups of editors and switch between them effortlessly.

   <img src="Preview/groups.png" alt="Addon Preview">
   
- **Reorder Editors**: Move editors up or down within a group to customize the switch sequence.  

   <img src="Preview/reorder.png" alt="Addon Preview">
   
- **Separator Toggle**: Option to enable or disable a visual separator between editor switches and other header operators for better UI clarity.  

   <img src="Preview/separator.png" alt="Addon Preview">
   
---       

## Installation

### **Official Installation**

1. Open **Blender 4.2+**
2. Navigate to **Edit > Preferences > Get Extensions**
3. Search for **"Quick Switch"**
4. Click **Install**

### **Alternate method**

1. Visit the [Blender Extensions platform](https://extensions.blender.org/add-ons/s3d-quickswitch)
2. Click **Get Add-on** to download from the official page

Or manually download the latest release:

- Download the latest **S3D_QuickSwitch_v2.0.0.zip** from the [GitHub Releases](https://github.com/Silvie3D/S3D_QuickSwitch/releases)
- In Blender, go to **Edit > Preferences > Add-ons**
- Click **Install**, select the downloaded `.zip` file, and enable the add-on

---

## Usage Instructions

### **Creating Editor Groups**

1. Go to **Edit > Preferences > Add-ons**
2. Locate **Quick Switch**
3. Under the preferences panel:
   - Click **Add Editor Group** to create a new group
   - Assign editors to the group (e.g., **3D Viewport, Shader Editor, Geometry Nodes**)

### **Using Quick Switch Buttons**

- Buttons will appear in the right most end on the **header** of editor areas included in your groups.
- Click the a switch of your choice to cycle through the editors in the group.

---

### **Example Setup**

- **Group 1**: **3D Viewport → Preferences→ Image Editor**
- **Group 2**: **Shader node Editor → Geometry node Editor→Compositor**
- **Group 3**: **Outliner → Properties → Python Console**

---

## Supported Editor Areas

All Editor areas are supported except:    

    ❌Asset Browser

    ❌File Explorer

---

## Support & Feedback

For any questions, issues, or suggestions, feel free to reach out:

- **Maintainer**: Rabah Ahmed (**Silvie3D**)
- **Email**: [rabahahmed95@gmail.com](mailto:rabahahmed95@gmail.com)
- **Issues**: [S3D_QuickSwitch Issues](https://github.com/Silvie3D/S3D_QuickSwitch/issues)

---

## License

© 2025 Silvie3D

**This add-on is licensed under [GNU General Public License 3.0](https://www.gnu.org/licenses/gpl-3.0.html).**