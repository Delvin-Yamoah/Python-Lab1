# Python-Lab1

# File Downloader and Modifier Script

This Python script performs several tasks related to file management, including downloading a file from a remote URL, modifying its content based on user input, and handling local filesystem operations such as directory creation and file renaming.

## 🧰 Features

- Deletes an existing folder named `delvin_yamoah` (if it exists).
- Creates a new folder named `delvin_yamoah`.
- Downloads a file from a GitHub URL and saves it locally as `delvin_yamoah.txt`.
- Prompts the user to input a sentence describing what they’ve learned.
- Writes the user input and current timestamp to the downloaded file.
- Displays the content of the modified file.
- Attempts to rename the file.

## 🚀 Getting Started

### Prerequisites

Ensure Python 3 is installed. The script also uses the `requests` library, which can be installed using:

```bash
pip install requests
```

## Usage

Run the script using Python:

```bash
python script_name.py
```

## Replace script_name.py with the actual name of your Python file.

## 🛠 Notes

The script overwrites the downloaded file with the user input and timestamp.

The final file rename step may fail if the target file path is incorrect or the file doesn't exist. You may need to adjust the filename accordingly.

## 📁 File Structure

Copy
Edit
.
├── delvin_yamoah/
│ └── delvin_yamoah.txt
├── script_name.py
└── README.md
