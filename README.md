# Word Counter Program

This project is a simple **Java console application** that counts the frequency of words in a sentence entered by the user.  
It demonstrates **basic Java programming concepts** such as classes, packages, user input, arrays, and object interaction.

---

## 📂 Project Structure
src/<br>
├── Main.java # Entry point of the program<br>
├── program/<br>
│ └── Program.java # Controls the flow of the program<br>
└── task/<br>
└── Words.java # Handles sentence input, word storage, and counting<br>

 📌 Features
- Takes a sentence from the user.
- Converts all words to lowercase.
- Splits the sentence into words (using spaces).
- Counts how many times each word appears.
- Displays word counts without repeating duplicates.

---

 ▶️ How It Works
1. Main calls the `Program` class.
2. `Program` creates a `Words` object.
3. `Words`:
   - Accepts user input.
   - Splits the input into an array of words.
   - Counts how many times each word appears.
4. Results are printed in the console.

---

## 🖥️ Example Output
Enter Sentence
Hello world hello Java world
hello : 2
world : 2
java : 1


---

## 🛠️ How to Run
1. Clone or download the project.
2. Open in any Java IDE (e.g., IntelliJ, Eclipse, VS Code) or use the terminal.
3. Compile and run:
   ```bash
   javac Main.java program/Program.java task/Words.java
   java Main
