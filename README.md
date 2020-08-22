# Sort Duplicate Files Script
> Sorts duplicate files in given folder(s) as per the path arguments passed

## Installation

Simply download sortDuplicates python file and place it in a folder, on your desktop, or a place easily accessible via command line.

## Usage example
### Windows
Let's say you want to sort the duplicate files in X/Pictures, and that the .py script is located in X/Documents.

Via command line, navigate to the folder containing the .py: script

```
>cd C:/Users/username/Documents
```

To execute the file:

```
>py -<version prefix> sortDuplicates.py <Path/To/Folder/To/Sort>
```

Where version prefix is the main version you're using. For example, in version 3.X, you would use -3. The entire version ID would work as well, -3.6.6.

The path would be the path to the folder you want to sort. So given the example stated above, the command would look like:

```
>py -3 sortDuplicates.py C:/Users/username/Pictures
```

The script should run and create a new folder of duplicate files called SortedFiles

Note: More than one file paths may be passed as arguments if you wish to sort more than one file at a time. Let's say you want to sort Pictures and Videos:

```
>py -3 sortDuplicates.py C:/Users/username/Pictures C:/Users/username/Videos
```

### OS X

TODO

### Liux

TODO

## Requirements
Python 2+ (Built and tested in Python 3.6.6)
