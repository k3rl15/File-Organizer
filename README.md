# File Organizer

This Python script organizes files from a source directory to a destination directory based on their file extensions.

## Usage

1. Run the script (`file_organizer.py`) using Python:

    ```bash
    python file_organizer.py
    ```

2. Enter the source and destination paths as prompted.

3. The script will organize files based on their extensions into specific folders in the destination directory.

### Using the Executable (Windows)

If you're using a Windows operating system and don't have Python installed, you can use the provided executable file. Follow these steps:

1. **Download the ZIP file:**
   - Download the ZIP file named `File Organizer.zip`.

2. **Extract the ZIP file:**
   - Extract the contents of `File Organizer.zip` to a location of your choice.

3. **Run the Executable:**
   - Inside the extracted `File Organizer` folder, go into the 'dist' folder, double-click on `file_organizer.exe`.
   - The script will run, and you can follow the on-screen prompts.


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

## Requirements (if using the python script)

- Python 3.x
- `shutil` library (part of the Python standard library)

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.
