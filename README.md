# Tkinter CSV CRUD Application

## 📌 Project Description
This is a **desktop application** built using **Python Tkinter** that allows users to **perform CRUD (Create, Read, Update, Delete) operations** on CSV files. The application provides an interactive UI for loading, searching, filtering, sorting, and modifying CSV data.

## ✨ Features
- 📂 **Load CSV File**: Users can select and open a CSV file.
- 🔍 **Search & Filter**: Search data within the loaded file.
- 📊 **View Data**: Display CSV content in a user-friendly table format.
- 📝 **Add New Data**: Insert new rows into the CSV.
- ✏️ **Edit Existing Data**: Modify existing rows.
- ❌ **Delete Rows**: Remove selected entries.
- 🔀 **Sort Data**: Click column headers to sort ascending/descending.
- 💾 **Save Changes**: Save modifications directly to the CSV file.
- 📦 **Standalone Application**: Runs as a desktop application without needing a code editor.

## 🚀 Setup & Installation
### Prerequisites
Ensure you have **Python 3.x** installed on your system. If not, download it from [Python.org](https://www.python.org/downloads/).

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/tkinter-csv-crud.git
cd Project 1
```

### 2️⃣ Install Dependencies
1. Open **Command Prompt (cmd)** or **Terminal**.
2. Navigate to your project folder:
   ```bash
   cd path\to\Project 1
   ```
3. Install required dependencies:
   ```bash
   pip install pandas
   ```

### 3️⃣ Run the Application
1. In the same terminal, run:
   ```bash
   python app.py
   ```
2. The Tkinter application window should open.

## 🖥️ Convert to Executable (Optional)
To run the app **without Python**, create an `.exe` file using PyInstaller:
```bash
pip install pyinstaller
pyinstaller --onefile --windowed app.py
```
The `app.exe` file will be inside the `dist` folder.
