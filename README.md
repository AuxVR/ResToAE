# ResToAE 
Web based Resolume Advanced Output .XML to After Effects composition converter

**ResToAE** is a lightweight, browser-based tool that bridges the gap between Resolume Arena's Advanced Output and Adobe After Effects. 

It parses your Resolume Advanced Output `.xml` file and generates a `.jsx` script. When run in After Effects, this script automatically reconstructs your input map composition, creating pre-comps for every slice with the correct position, rotation, and resolution.

## 🚀 Features

* **XML Parsing:** Extracts Slice names, dimensions, positions, and rotations from Resolume XML.
* **Automatic Pre-comping:** Creates individual compositions for every slice, organized in a folder.
* **Intelligent Filtering:** Automatically ignores slices named "Dummy" or "Deco".
* **Data Labels:** Option to create "Shy" text layers containing slice resolution and coordinates for easy reference.
* **Zero Dependencies:** Runs entirely in the browser. No data is uploaded to any server.

## 🛠 How to Use

### Step 1: Export from Resolume
1.  Open Resolume Arena.
2.  Go to **Output** -> **Advanced**.
3.  Click the dropdown on the top left (Screen Setup) and select **Save As...**
4.  Save your `.xml` file.

### Step 2: Convert
1.  Open **ResToAE** (via the hosted link or local `index.html`).
2.  Drag and drop your `.xml` file into the drop zone.
3.  (Optional) Adjust the input map resolution if auto-detect fails.
4.  Click **Generate Script**.
5.  Click **Download .jsx**.

### Step 3: Run in After Effects
1.  Open Adobe After Effects.
2.  Go to **File** -> **Scripts** -> **Run Script File...**
3.  Select the `.jsx` file you just downloaded.
4.  Wait a moment for the script to build your composition!

## 📦 Installation

This tool is a static web application. You can use it in two ways:

1.  **Hosted Version:** https://AuxVR.Github.io/ResToAE/
2.  **Local Version:** Simply download `index.html` and open it in any browser. No internet required!

## ❤️ Support

This tool is free and open source. If it saves you hours of manual pixel mapping on your next gig, consider supporting!

[![Support on Ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/AuxVR)

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
