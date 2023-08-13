# File Organizer

This script is a simple Python tool for organizing files within a directory based on their file formats. It helps you declutter your workspace by grouping files into specific folders according to their respective types.

## How It Works

The script categorizes files into predefined directories based on their file extensions. Each directory corresponds to a particular type of file. Here are the available categories:

- HTML
- Images
- Videos
- Documents
- Archives
- Audio
- Plain Text
- PDF
- Python Scripts
- XML
- Executables
- Shell Scripts

For example, all files with `.jpg`, `.png`, `.gif`, etc., extensions will be moved to the "Images" directory, while files with `.pdf` extensions will be moved to the "PDF" directory.

## Requirements

- Python 3.x
- `pathlib` library

## Usage

1. Clone or download this repository to your local machine.

2. Navigate to the directory where you want to organize the files using your command-line interface.

3. Run the script using the following command:

```bash
python main.py
```

4. The script will scan the current directory for files and move them to their respective categorized folders.

5. After the organization is complete, any empty directories will be removed from the main directory.

## Customize

You can modify the `DIRECTORIES` dictionary in the script to add or remove categories based on your preferences. Make sure to follow the same format: `"Category Name": [".extension1", ".extension2", ...]`.

## Caution

- Use this script with caution and make sure to back up your files before running it.
- The script moves files, which might not be reversible if done incorrectly.
- Double-check the `DIRECTORIES` dictionary to ensure it meets your needs before running the script.

## License

This project is licensed under the [MIT License](LICENSE).
