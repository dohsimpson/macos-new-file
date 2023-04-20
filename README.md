# MacOS New File

This repository contains a macOS workflow that adds a "Create New File" action to the right-click context menu in Finder. This feature is a welcome addition for users who find the native macOS Finder lacking this essential functionality.

![demo.gif](./demo.gif)

## Features

- Add a "Create New File" action to the right-click context menu in Finder
- File names will automatically increment to avoid collision with existing new file

## Installation

1. Clone this repo
2. Double-click the "Create New File.workflow" package to install the workflow.
3. Follow the on-screen instructions to add the workflow to your system.

After installation, you should see the "Create New File" action in the right-click context menu when you **click on a folder** or **on a Finder tab**.

## Usage

1. Right-click on a folder or on a Finder tab.
2. From the context menu, under "Quick Actions", choose the "Create New File" action.
3. A new file will be created in the folder, with file name "untitled.txt". You can then rename the file and modify its extension as needed.

## Customization

To change the default file name for newly created files, follow these steps:

1. Open the `Automator` app on your Mac.
2. In Automator, choose "Open" from the File menu, and navigate to the installed workflow (`~/Library/Services/MacOS_New_File.workflow`).
3. Locate the `bash` script action in the workflow.
4. Edit the `bash` script to replace the default file name with your preferred file name.
5. Save your changes and close the Automator app.

## Contributing

If you have any suggestions, bug reports, or enhancements, feel free to submit a pull request or create an issue. We appreciate your contribution and feedback!

## License

This project is released under the [MIT License](LICENSE).
