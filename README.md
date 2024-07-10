# MOOCTextEditor-solutions

This repository contains the solution for the MOOCTextEditor project, which is part of the Coursera course "Object Oriented Programming in Java Specialization" offered by the University of California, San Diego (UCSD).

## Project Description

The MOOCTextEditor is a simplified text editor that provides basic text editing functionalities. It is designed to demonstrate the application of object-oriented programming concepts in Java, including data structures, algorithms, and graphical user interface (GUI) development.

## Features

- **Text Editing:** Basic text editing functionalities such as inserting, deleting, and modifying text.
- **File Operations:** Open and save text files.
- **Statistics:** Display word count, character count, and other statistics about the text.
- **Spell Checking:** Basic spell check functionality with suggestions for corrections.

## Repository Structure

The repository is organized as follows:

```bash
MOOCTextEditor/
├── src/
│ ├── document/
│ │ ├── Document.java
│ │ ├── EfficientDocument.java
│ │ ├── BasicDocument.java
│ │ └── ...
│ ├── spelling/
│ │ ├── Dictionary.java
│ │ ├── DictionaryHashSet.java
│ │ ├── SpellingSuggest.java
│ │ └── ...
│ ├── textgen/
│ │ ├── MarkovTextGenerator.java
│ │ ├── MarkovTextGeneratorLoL.java
│ │ └── ...
│ ├── gui/
│ │ ├── TextEditorApp.java
│ │ └── ...
│ └── ...
├── data/
│ ├── sampleText.txt
│ └── ...
├── test/
│ ├── document/
│ │ ├── DocumentTest.java
│ │ ├── EfficientDocumentTest.java
│ │ └── ...
│ └── ...
└── README.md
```

## Getting Started

To get started with the MOOCTextEditor project:

1. **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/MOOCTextEditor.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd MOOCTextEditor
    ```
3. **Open the project in your preferred Java development environment (e.g., IntelliJ IDEA, Eclipse, VS Code).**

4. **Compile and run the application:**
    - Locate the `TextEditorApp.java` file in the `src/gui/` directory.
    - Run the `TextEditorApp.java` file to launch the text editor application.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- An IDE or text editor for Java development (e.g., IntelliJ IDEA, Eclipse, VS Code)

## Contributing

Contributions are welcome! If you have improvements or solutions to add, please follow these steps:

1. **Fork this repository.**
2. **Create a new branch:**
    ```bash
    git checkout -b feature-branch
    ```
3. **Make your changes and commit them:**
    ```bash
    git commit -am 'Add new feature'
    ```
4. **Push to the branch:**
    ```bash
    git push origin feature-branch
    ```
5. **Create a new Pull Request.**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Coursera](https://www.coursera.org/)
- [University of California, San Diego (UCSD)](https://ucsd.edu/)

---

Happy coding!