 📝 Java File I/O – Notes App

## 📌 Objective
A simple **Command Line Interface (CLI)** program in Java to create and manage notes using **file handling**.  
Users can add notes, view all saved notes, and store them in a text file (`notes.txt`).

---

## 🛠 Tools & Technologies
- **Java**
- **VS Code**
- **Terminal / Command Prompt**
- **File I/O** (`FileWriter`, `FileReader`, `BufferedReader`)

---

## 📂 Project Structure
NotesApp.java # Main Java program file
notes.txt # Text file where notes are stored (created automatically)

yaml
Copy
Edit

---

## 🚀 Features
- ➕ **Add Note** – Saves new notes to `notes.txt` without deleting old ones.
- 📄 **View Notes** – Reads and displays all saved notes from file.
- 💾 **Persistent Storage** – Notes remain saved even after closing the program.
- 🖥 **CLI Based** – Works directly from the terminal.

---

## 📜 How to Run
1. **Save** the file as `NotesApp.java`.
2. Open a **terminal** in the project folder.
3. **Compile** the program:
   ```bash
   javac NotesApp.java
Run the program:

bash
Copy
Edit
java NotesApp
Use menu options:

1 → Add Note

2 → View Notes

3 → Exit

🧠 Key Concepts Used
FileWriter – Appends notes to a file.

BufferedReader – Reads notes line by line.

Try-with-resources – Ensures files close automatically.

Exception Handling – Handles missing file or I/O errors.

📌 Example Output
markdown
Copy
Edit
--- Notes Manager ---
1. Add Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Buy milk
Note saved successfully!

--- Notes Manager ---
1. Add Note
2. View Notes
3. Exit
Enter your choice: 2

--- Your Notes ---
- Buy milk
