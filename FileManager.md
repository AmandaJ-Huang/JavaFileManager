# FileManager Documentation

## Commands
* `list`: Entering a specified file path will list all folders and files under that directory.
* `info`: Entering a specified file path will provide details about the directory including Name, Absolute path, Relative path, Size (in bytes), Created date and Last Modified date.
* `mkdir`: Creates a new folder with the specified name in the specified directory.
* `rename`: Renames a specified file or folder.
* `copy`: Copies or moves a specified file or folder.
* `move`: Appears to just delete a specified file or folder.
* `delete`: Deletes a specified file or folder.
* `quit`: Exits File Manager and terminates the program.

## Things to Consider
* Manipulation commands and input/output are kept separate for clean coding purposes (single responsibility) and potentially for easier testing. The file manager seems to only process user input and output, then the file operator has the logic to affect files/folders.
* Unsure as to why copy/move are in the same method. Move seems counterintuitive to its expected purpose (i.e., moving an actual file).
    

