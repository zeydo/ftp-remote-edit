## 0.12.1 - Release
- Fix error reported in "Failed to load the ftp-remote-edit package" (issue-97)

## 0.12.0 - Release
- Added Option "Open in Atom Dock" - Open the view as tab in atom dock instead of panel. Only available from Atom 1.17.0
- Added FTP Message Log - Shows sent/received FTP commands in log
- Changed refreshing behavior of the TreeView
- Feature request: Drag-and-Drop (issue-25)
- Feature request: Copy / Cut / Paste files (issue-24)
- Feature request: Rename copied file if exists to prevent collision of names (issue-61)
- Feature request: Statusbar for upload/download (issue-69)
- Feature request: Option "Disable Notification on save/upload" (issue-55)
- Feature request: Option "Hide Ignored Names" (issue-78)
- Feature request: Option "Opening hidden files" (e.g. htaccess) (issue-66)
- Feature request: Preview opened file in pending pane to have the same behavior than in Atom (issue-83)
- Fixed error reported in "Refreshing directory when moving a file using Rename" (issue-51)

## 0.11.9 - Release
- Fixed error reported in "Image view doesn't work" (issue-58)
- Fixed error reported in "Undo just opened file" (issue-62)
- Fixed error reported in "Uncaught SyntaxError: Unexpected token ? in JSON at position 0" (issue-44)

## 0.11.8 - Release
- Fixed error while creating a folder (issue-32)
- Fixed error while renaming a file/folder (issue-42)

## 0.11.7 - Release
- Feature request: Added hotkey for toggling "ctrl+space" (issue-37)
- Hide password in server settings (issue-36)

## 0.11.6 - Release
- Added Option to enable debug mode
- Fixed error reported in "Unsyncing after idle" (issue-28)

## 0.11.5 - Release
- Checks connection status everytime the "connect" function is called. Fixes issue on sftp "keep connection alive" error. (issue-28)

## 0.11.4 - Release
- Added dialog to change the password. To open run command "ftp-remote-edit:change-password". Empty password caused error and will no longer be accepted.

## 0.11.3 - Release
- Fixed error while creating a folder (issue-20)
- Improved speed by keeping the connections open

## 0.11.2 - Release
- The path in the dialogs is now corrected so that it corresponds to the schema. Spaces within the path caused errors.

## 0.11.1 - Release
- Fixed styles for light theme (issue-17)

## 0.11.0 - Release
- Feature request: Added setting to define path for ssh/sftp private keyfile

## 0.10.0 - Release
- Feature request: Added setting to define initial directory.

## 0.9.0 - Release
- New action "ftp-remote-edit: find" added to search in tree for a folder

## 0.8.0 - Release
- Refactoring of the complete source code
- Added UI like TreeView
- Added Keyboard Navigation
- Added function to remember the password during the session
- Added promises for ftp and sftp classes
- Extends settings (sortFoldersBeforeFiles, showOnRightSide)

## 0.7.0 - Release
- Fix errors
- Refactoring

## 0.6.0 - Release
- Error and file saved response implemented

## 0.5.0 - Release
- Better configuration interface

## 0.4.0 - Release
- Sftp integrated

## 0.3.0 - Release
- Added function new file, new directory, delete file, delete directory, rename file and rename directory.

## 0.2.0 - Release
- Better usability

## 0.1.0 - Release
- First Release
