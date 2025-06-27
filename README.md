# Task 4: Java File I/O – Notes App

## 🚀 Objective
Create a simple **text-based notes manager** using Java File I/O. This app allows users to add and view notes by reading from and writing to a text file.

## 🛠️ Tools Used
- Java (JDK)
- VS Code or any Java IDE
- Terminal or Command Prompt

## 📁 Files Included
- `NotesApp.java` – Main source code.
- `notes.txt` – Created automatically to store notes.

## 📌 Features
- Add new notes.
- View all saved notes.
- Persist notes using `FileWriter` and `BufferedReader`.

## 🧠 Concepts Demonstrated
- File Handling in Java (`FileWriter`, `FileReader`, `BufferedReader`)
- Exception Handling
- Console-based User Interface
- Data Persistence

## ▶️ How to Run

1. **Clone or Download the project**  
   Save the code file as `NotesApp.java`

2. **Compile the program**  
   Open terminal or command prompt in the project folder:
   ```bash
   javac NotesApp.java
   ```

3. **Run the application**
   ```bash
   java NotesApp
   ```

4. **Choose from the menu**  
   - Option 1: Add Note  
   - Option 2: View Notes  
   - Option 3: Exit

## 📂 Output
- Notes are saved in a file named `notes.txt`.
- Each note is stored on a new line.

## ✍️ Sample Usage

```bash
=== NOTES APP ===
1. Add Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Finish Java Task 4
Note saved successfully!
```

```bash
=== NOTES APP ===
1. Add Note
2. View Notes
3. Exit
Enter your choice: 2

=== Saved Notes ===
1. Finish Java Task 4
```

## ✅ Outcome
You will learn:
- How to **persist user input** into a text file.
- How to **read and display file contents** in Java.
- How to handle basic **file I/O exceptions**.

---

🔖 **Internship Project Submitted By:**  
**Jatin Gangare**  
Java Developer Internship – Task 4
