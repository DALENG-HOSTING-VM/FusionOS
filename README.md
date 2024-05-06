# FusionOS

FusionOS is a simple operating system developed in C++ with support for both Bash and PowerShell.

## Features
- Bash and PowerShell support
- Simple user interface with GUI elements
- Support for wireless and wired networks
- Option to create virtual network switches
- Text editor with functionality to open multiple tabs, search and replace
- Control Panel application with similar functionality to Windows
- Settings application with similar functionality to Windows
- Taskbar and taskbar inspired by macOS and Windows

## Folder structure
FusionOS/
├── Applications/ # The source code of the applications
│ ├── Browser/
│ ├── Calculator/
│ ├── ControlPanel/
│ ├── Settings/
│ └── TextEditor/
├── GUI/ # The source code of the GUI elements
│ ├── Taskbar/
│ ├── Dock/
│ └── WindowManager/
├── Kernel/ # The source code of the operating system kernel
│ ├── MemoryManager/
│ ├── NetworkSettings/
│ └── WindowManager/
├── README.md # Documentation
├── FusionOS.sln # Visual Studio solution file
└── main.cpp # The entry point for the operating system

## Installation
1. Clone the project from GitHub: `git clone https://github.com/DALENG-HOSTING-VM/FusionOS.git`
2. Open the project in Visual Studio 2022
3. Build the project by pressing "Build Solution" in Visual Studio
4. Run FusionOS by pressing "Local Windows Debugger"

## Contribution
We welcome contributions to the development of FusionOS! If you have suggestions for improvements or want to contribute code, you are welcome to open a pull request.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
