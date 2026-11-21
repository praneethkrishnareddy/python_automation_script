# Python Automation Scripts

## 📌 Overview
This project contains a collection of Python automation scripts that perform common file and system automation tasks. These scripts help automate repetitive work, improve productivity, and demonstrate Python's automation capabilities.

## 🚀 Features
- Bulk File Renamer
- Automatic Folder Organizer
- Log File Generator
- Current Date & Time Display
- File Backup Automation

## 🛠️ Technologies Used
- Python 3
- os module
- shutil module
- logging module
- datetime module

## 📂 Project Structure

```
Python-Automation/
│── bulk_file_renamer.py
│── folder_organizer.py
│── log_generator.py
│── datetime_script.py
│── backup_automation.py
│── README.md
```

## 📜 Script Descriptions

### 1. Bulk File Renamer
Renames all files in a selected folder using sequential numbering while preserving their original file extensions.

### 2. Automatic Folder Organizer
Automatically sorts files into folders based on their file extensions (e.g., PDF, JPG, TXT).

### 3. Log Generator
Creates a log file that records automation activities with timestamps using Python's logging module.

### 4. Date & Time Script
Displays the current system date and time in a readable format.

### 5. File Backup Automation
Copies a file from a source location to a destination folder to create a backup.

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Python-Automation.git
```

2. Navigate to the project folder.

```bash
cd Python-Automation
```

3. Run any script.

```bash
python bulk_file_renamer.py
```

or

```bash
python folder_organizer.py
```

or

```bash
python log_generator.py
```

## 📷 Sample Output

```
Enter folder path:
D:\Documents\Test

Renamed: image1.jpg -> file_1.jpg
Renamed: report.pdf -> file_2.pdf

All files renamed successfully!
```

## 🎯 Learning Outcomes
- Python File Handling
- Automation using Python
- Working with Directories
- Logging in Python
- File Backup Techniques
- Date and Time Handling

## 📌 Future Improvements
- Add a graphical user interface (GUI)
- Schedule scripts to run automatically
- Add support for cloud storage backups
- Improve error handling and logging
