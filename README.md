# arkhive
A macOS Service to Archive old InDesign and Illustrator files

## Ersatz Version Control
`Arkhive` is a macOS service that moves old InDesign and/or Illustrator files into a directory called 'Archived', leaving the most recent version of the file untouched.

The .workflow file is a simple bash script, wrapped with Automator, to create a native macOS Service.

## Installation
### Manual Install
Download and decompress the ZIP archive, then double-click the resulting `.workflow` file to initiate the installation process.

The Operating System will prompt you for permission to move the file to the correct location [ \~/Library/Services/ ]. Once installed its functionality is available immediately.

## Usage
### Working with Files
Selecting `Arkhive` from the 'Services' submenu with a *file* highlighted in the Finder will mark it as the file to preserve, and move all other InDesign and Illustrator files in the same folder to the 'Archived' folder.

### Working with Folders
Selecting `Arkhive` from the 'Services' submenu with a *Folder* highlighted in the Finder will mark the most recently modified file within that folder as the file to preserve, and move all other InDesign and Illustrator files to the 'Archived' folder
