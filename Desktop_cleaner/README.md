# Desktop Cleaner Script

## Overview:
This Python script helps you organize files in a folder by grouping them into subfolders based on their file types. For example, all `.jpg` files will be moved into a subfolder called "JPG Files", and `.txt` files will go into "TXT Files". It automatically creates the necessary subfolders if they don't already exist.

### Features:
1. **Automatic Folder Creation**: The script will create subfolders based on file extensions (e.g., JPG, TXT).
2. **File Organization**: Files are moved into their corresponding subfolders, cleaning up the main directory.
3. **Customizable Folder Path**: You can specify any folder to organize (by editing the `folder_path` variable in the script).

### How to Use:
1. **Set the Folder Path**:
   - Open the script and replace `'EDIT THIS'` in the `folder_path` variable with the path to the folder you want to clean.
   
2. **Run the Script**:
   - Execute the script in a Python environment.
   - The script will create subfolders and move files accordingly.

3. **Example**:
   - If the folder contains `image.jpg` and `document.txt`, the script will create "JPG Files" and "TXT Files" subfolders and move the respective files into them.

### Output:
- Files are moved into subfolders within the specified folder based on their file extensions.

### Customization:
- You can modify the script to handle different file organization schemes, such as grouping by date or size, or even changing how subfolders are named.

### Error Handling:
- The script checks if the folder path is valid before running. If the folder does not exist, an error message is displayed.

