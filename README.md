# RoboCopyGUI

The definitive solution to manage your backups and file copy operations with a simple and powerful interface

<img width="1920" height="1019" alt="hero-image" src="https://github.com/user-attachments/assets/780bae19-816f-4de8-a1e5-b6e6c0fcf7da" />

## Introduction

RoboCopy All In One GUI V1.0 is a free and intuitive graphical user interface (GUI) for the Windows command-line tool RoboCopy. Designed by Gianpaolo Aggiusti, this software simplifies file and folder copy and synchronization operations, making them accessible even to less experienced users. Its purpose is to provide complete control over RoboCopy through a user-friendly interface, eliminating the need to memorize complex commands. This application is a stable and complete project, designed to offer an efficient and trouble-free experience in managing your backups and data transfers.

## Installation

RoboCopy All In One GUI V1.1 is a portable software and does not require installation.

### Requirements:

* **Operating System:** Windows 7 or higher.
* **Dependencies:** No additional pre-installed dependencies are required, as the software is provided as a single, standalone executable file (.exe). The Python libraries `psutil` and `matplotlib` are included in the executable package.

### Installation Instructions:

1.  Download the `RoboCopy All In One GUI V1.0.exe` file from the distribution source.
2.  Move the `.exe` file to the desired folder on your computer.
3.  Double-click the `.exe` file to start the program.

No post-installation configuration is necessary.

### Usage Examples:

1.  **Mirror Copy:**
    * Enter the "Source Path" (e.g., `C:\ImportantData`).
    * Enter the "Destination Path" (e.g., `D:\Backup`).
    * Select the "Mirror Copy (`/MIR`)" checkbox.
    * Click "Start RoboCopy".
    This will create an exact copy of the source in the destination, deleting files from the destination that no longer exist in the source.
2.  **Incremental Copy:**
    * Enter the "Source Path" and "Destination Path".
    * Select the "Incremental Copy (Update only new/modified files)" checkbox.
    * Click "Start RoboCopy".
    This operation will only copy new or modified files.

3.  **Adding Custom Options:**
    * Type the options directly into the "Manual Options" field (e.g., `/XO /Z`).
    * Alternatively, click on "Options..." in the top menu for a complete list of common flags and their descriptions.

### Commands:

There are no specific command-line commands for the GUI itself, as it is a graphical interface application. The software generates and executes RoboCopy commands internally.

## Contributions

RoboCopy All In One GUI V1.0 is a project individually developed by Gianpaolo Aggiusti. Currently, there are no plans for direct collaboration through external code contributions.

### Bug Reporting:

If you encounter bugs or unexpected behavior, please report them by sending an email to [g.aggiusti@gmail.com](mailto:g.aggiusti@gmail.com). Please try to provide as much information as possible:
* Detailed description of the problem.
* Steps to reproduce the bug.
* Operating system versions.
* Relevant screenshots or log files, if applicable.

### FAQ:

* **Is the software really free?** Yes, it is freeware for personal and commercial use.
* **Can I use it on multiple computers?** Absolutely yes, you can use it on an unlimited number of PCs.
* **Do I need to install RoboCopy separately?** No, RoboCopy is a built-in utility in Windows and does not require additional installations.
* **Does the software modify my source files?** No, RoboCopy is a copy tool. If you do not use "move" options (`/MOV` or `/MOVE`), the source files are not modified or deleted.
* **Why doesn't verification work for move operations?** The verification based on SHA256 hashes compares files at the source and destination locations. In move operations, the files are removed from the source, making comparison impossible after completion.

## License and Contacts

### License:

This software is distributed under the terms of the End-User License Agreement (EULA) included in the software package (`Eula.txt`). It is freeware software: you can use, copy, and distribute it freely, provided it is unaltered and free of charge.

### Contact Information:

For any questions, suggestions, or bug reports, you can contact the developer:

Gianpaolo Aggiusti
Email: [g.aggiusti@gmail.com](mailto:g.aggiusti@gmail.com)
Web: https://robocopygui.com

Donations are always welcome to support future development and keep the project active! You can donate via PayPal at the following link:
https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=g.aggiusti@gmail.com&item_name=Donation+for+RobocopyGUI
