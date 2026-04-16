# Bat to EXE Converter

A lightweight, modern Python GUI tool that converts Windows Batch (.bat) files into standalone Executable (.exe) files. Unlike basic wrappers, this tool uses C# compilation to create a native bridge, allowing for more reliable execution and better console management.

---

### Key Features
* **C# Compilation Bridge:** Uses `csc.exe` (C# Compiler) to build a native executable that launches your batch script.
* **No Console Mode:** Option to create "consoleless" executables that run silently in the background.
* **Custom Icons:** Supports embedding custom `.ico` files directly into the generated executable.
* **Clean GUI:** A simple, intuitive interface built with Tkinter for quick conversions.
* **Auto-Cleaning:** Automatically manages temporary build files and intermediate C# source code.
<img width="240" height="240" alt="0416 (1)" src="https://github.com/user-attachments/assets/9398d3c2-2e2c-4454-8620-269025ba8613" />
---

### 📦 Prerequisites

The converter requires the following to be installed on your system:

1.  **Python 3.x**
2.  **Pillow (PIL):** Used for handling icon and image assets within the GUI.
3.  **.NET Framework:** Required for the `csc.exe` compiler (pre-installed on most Windows systems).

```bash
pip install Pillow
