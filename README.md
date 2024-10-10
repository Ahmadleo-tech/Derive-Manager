Here’s your customized `README.md` file:

---

# CS Link Manager

## Overview

The **CS Link Manager** is a Python-based application designed to manage and access course links for various subjects within a Computer Science (CS) degree. The program allows users to select their semester, search for subjects, and open the corresponding online resources (such as Google Drive links) directly in a web browser. Additionally, the program includes a text-to-speech feature to guide the user throughout the interaction.

## Features

- **Degree Management**: Pre-defined subject links for a Bachelor of Science in Computer Science (BSCS).
- **Semester Selection**: Choose from 8 semesters in the CS degree to view available subjects.
- **Subject Search**: Search for specific subjects within a semester.
- **Link Access**: Open subject links directly in a web browser.
- **Text-to-Speech**: Audible instructions and feedback provided using `pyttsx3` (text-to-speech).

## Installation

To run the CS Link Manager on your local machine, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:
- **Python 3.x**
- `pyttsx3` library for text-to-speech functionality
- `webbrowser` and `re` modules (standard in Python)

You can install `pyttsx3` using pip:

```bash
pip install pyttsx3
```

### Running the Program

1. Clone the repository or download the source code:
   ```bash
   git clone https://github.com/ahmadleo-tech/CS-Link-Manager.git
   ```

2. Navigate to the project directory:
   ```bash
   cd CS-Link-Manager
   ```

3. Run the Python script:
   ```bash
   python cs_link_manager.py
   ```

4. Follow the on-screen instructions to select a semester, search for subjects, and open links.

## Usage

### Menu Options

1. **Select Semester**: Browse through different semesters and select a semester to access the subject links.
2. **Exit**: Exit the program.

### Searching for Subjects

- After selecting a semester, you can enter the subject name or a keyword to search for the subject. If the subject is found, the corresponding resource link will be opened in your default web browser.

## Example

Here's an example of what using the program looks like:

```
=== CS Link Manager ===
1. Select Semester
2. Exit
Choose an option: 1

Available Semesters for Computer Science:
Semester 1
Semester 2
Semester 3
...
Select a semester number: 1

Enter the subject name to search for: OOP
Opening link for OOP: https://drive.google.com/drive/folders/1hgH7wC7H6if9s-95wpKbHiTfVpWOfdBw
```

## Contributing

Contributions to this project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes.
4. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
5. Push the branch:
   ```bash
   git push origin feature-branch
   ```
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or issues, feel free to contact:
- **Ahmad Leo** - [ahmadleo498@gmail.com](mailto:ahmadleo498@gmail.com)
- GitHub: [@ahmadleo-tech](https://github.com/ahmadleo-tech)

---

This `README.md` is ready to be uploaded to your GitHub repository! Let me know if you need any further customizations.
