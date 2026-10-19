# Docklight-Project-Editor
A Windows GUI application to create and edit Docklight .ptp projects using ASCII commands, with automatic HEX conversion and configurable terminators (CR, LF, CRLF).

# Docklight Project Editor

A lightweight Windows application for creating and editing Docklight `.ptp` project files using human-readable ASCII commands.

## Features

- Create new projects from an embedded template
- Open existing `.ptp` project files
- Add, edit, and delete commands in a scrollable list
- Automatically convert ASCII commands to hexadecimal
- Choose command terminators: None, CR, LF, or CRLF
- Save projects in Docklight-compatible `.ptp` format
- Simple single-window interface
- No Python installation required

## Application Preview

![Docklight Editor Main Window](images/Docklight_Editor_Main.png)

## Download

Download the latest Windows executable from the [Releases](../../releases) page.

## How to Use

1. Download the latest `Docklight_Editor.exe`.
2. Double-click the executable to launch the editor.
3. Click **Open** to load an existing `.ptp` project, or start with the built-in template.
4. Click **+ Add Command** to create a new command.
5. Enter the command name and ASCII command text.
6. Select a terminator: **None**, **CR**, **LF**, or **CRLF**.
7. Click **Save** to generate or update the `.ptp` file.
8. Open the saved project in Docklight.

## Example

| Command Name | ASCII Command | Terminator |
|---|---|---|
| MODE_MASTER | RT+MODE=M | CRLF |
| MODE_SLAVE | RT+MODE=S | CR |
| STATUS | RT+STATUS? | None |

## Requirements

- Windows 10 or Windows 11
- Docklight for opening and using generated `.ptp` projects

## Distribution

This repository provides the Windows executable and user documentation. Python source code is not included.

## Disclaimer

This is an independent utility and is not affiliated with or endorsed by the developers of Docklight.
