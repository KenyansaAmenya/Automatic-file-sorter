# Automatic-file-sorter
# Key Features of This Code:
- Folder Creation: Creates three folders ('csv files', 'image files', 'pdf files') if they don't already exist.

- File Sorting: Moves files to appropriate folders based on their extensions:

.csv files → 'csv files' folder

.png files → 'image files' folder

.pdf files → 'pdf files' folder

# Safety Checks:

- Checks if destination folder exists before moving files

- Checks if file already exists in destination before moving

- Provides feedback for files that weren't moved

- Error Handling: The else clause catches files that don't match any of the specified extensions.

# Potential Improvements:
- Could add more file extensions (like .jpg, .xlsx, etc.)

- Could make the folder names and extensions configurable

- Could add logging instead of simple print statements

- Could handle cases where files with the same name already exist in destination

- This script is useful for organizing cluttered directories by automatically sorting files into appropriate categories.