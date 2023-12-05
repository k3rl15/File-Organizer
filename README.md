# File Organizer

This Python script organizes files from a source directory to a destination directory based on their file extensions.

## Usage

1. Run the script (`organize_files.py`) using Python:

    ```bash
    python organize_files.py
    ```

2. Enter the source and destination paths as prompted.

3. The script will organize files based on their extensions into specific folders in the destination directory.

## Features

- **Supported File Categories:**
    - Documents: txt, pdf, doc, docx, rtf, odt, log, xls, xlsx, ppt, pptx
    - Images: jpg, jpeg, png, gif, bmp, ico
    - Music: mp3, m4a, aac, wav, ogg, wma
    - Videos: mp4, wwv, avi, webm, flv, mov, mkv
    - Programming Files: c, cpp, java, js, py, html, css
    - Compressed Files: zip, 7z, tar, rar, tgz, gz
    - Data Structure Files: json, xml, csv
    - Executable: exe
    - Other Files: Any file not matching the above categories

- **Logging:**
    - Detailed logging information is displayed during program execution.

- **User Interaction:**
    - The script prompts the user to input source and destination paths.

## Requirements

- Python 3.x
- `shutil` library (part of the Python standard library)

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.


Make sure to include a `LICENSE` file with the appropriate license text if you choose a specific license for your project. You can customize this `readme.md` 
file further based on your preferences and project details.
