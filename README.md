# Password Generator

A first-year team project focused on improving an existing Python password generator with a Tkinter graphical interface.  
The goal was to make the application more secure, user-friendly, and visually polished while clearly separating responsibilities between team members.

## 🔗 Original Project

Base project: **Advanced Password Generator**  
Source code: [PassGen.py](https://github.com/Aewass/Python-Password-Generator-w-TKinter-GUI/blob/master/PassGen.py)

## 🎯 Project Goal

The main goal of this project was to improve a password generator with a Tkinter GUI by adding better password generation logic, a more modern interface, password strength evaluation, password history, and improved error handling.

The project was divided into three main parts:

- Password generation and security logic
- Graphical user interface and layout design
- Additional features such as password strength checking, history, copying, and saving

---

## 👥 Team Roles & Contributions

### 🔐 Eligijus — Password Generation Logic

Eligijus was responsible for the core password generation logic.

#### Functions

- `get_selected_characters()` — collects the character groups selected by the user, such as letters, numbers, and symbols.
- `generate_password()` — generates the password, validates the selected length, and passes the result to other parts of the program.

#### Improvements

- Replaced basic random generation with a more secure approach using the `secrets` module.
- Added validation to check whether the user selected at least one character group.
- Ensured that the generated password contains at least one character from each selected group.
- Added error handling for invalid password length input.

---

### 🎨 Tomas — User Interface & Design

Tomas was responsible for the main application window, layout, and visual design.

#### Functions

- `create_window()` — creates the main program window.
- `create_interface()` — builds the interface elements such as labels, input fields, buttons, result display, and password history section.
- `toggle_fullscreen()` — enables or disables fullscreen mode.

#### Improvements

- Replaced the original light theme with a darker cyber / hacker-style design.
- Added green terminal-style text to improve the cybersecurity theme.
- Improved the layout to make settings, results, and history easier to read.
- Increased the window size so the password history section would be visible.
- Added a fullscreen button and `F11` keyboard support.

---

### 🧩 Matas — Additional Features

Matas was responsible for extra functionality that improved the usability of the application.

#### Functions

- `check_strength()` — evaluates the strength of the generated password.
- `password_actions()` — handles password history, copying, saving, and clearing history.

#### Improvements

- Added password strength evaluation.
- Added password history.
- Added copy-to-clipboard functionality.
- Added saving password history to `slaptazodziu_istorija.txt`.
- Added the ability to clear password history.

---

## 🛠️ Technologies Used

- **Python**
- **Tkinter**
- **secrets module**
- **File handling**
- **GUI design**
- **Input validation**

---

## ✅ Key Features

- Secure password generation using Python’s `secrets` module
- Custom password length selection
- Character group selection
- Password strength checking
- Password history
- Copy-to-clipboard support
- Save history to a `.txt` file
- Clear history option
- Dark cyber-style Tkinter interface
- Fullscreen mode support

---

## 📌 What We Learned

During this project, we improved our understanding of Python GUI development, secure random password generation, input validation, file handling, and teamwork in a programming project.

The project also helped us understand how small security-focused tools can be improved through better usability, clearer code structure, and stronger validation logic.

---

## 🚀 Future Improvements

- Add password entropy calculation
- Add unit tests with `pytest`
- Add an option to exclude similar-looking characters
- Add password export in CSV format
- Improve the GUI with more advanced styling
- Package the application as an executable file
