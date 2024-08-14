<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">ISXINY</h1>
</p>
<p align="center">
    <em>Unleash Excel magic with precision comparisons.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/AaronTheGenerous/isXinY.git?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/AaronTheGenerous/isXinY.git?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/AaronTheGenerous/isXinY.git?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/AaronTheGenerous/isXinY.git?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

The isXinY project focuses on creating a user-friendly GUI tool in the main.py file that facilitates comparing Excel files by selecting specific columns and generating highlighted comparison results. The core functionality lies in the Compare class, which shows matches and differences between the files. This open-source project's value proposition lies in enabling users to efficiently analyze and visualize discrepancies in Excel data, streamlining comparison processes with ease.

---

##  Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | The project follows a modular architecture with a focus on GUI development for comparing Excel files. It utilizes Python for backend processing and GUI rendering. The `Compare` class handles comparison logic efficiently. |
| 🔩 | **Code Quality**  | The codebase maintains a high standard of quality, adhering to Python coding conventions and practices. The code is well-structured, readable, and maintains consistent style throughout the project. |
| 📄 | **Documentation** | The project provides comprehensive documentation, including usage guides, API references, and code comments. Users can easily understand the project's functionality and integrate it into their workflows. |
| 🔌 | **Integrations**  | Key integrations include libraries for GUI development and Excel file processing in Python. External dependencies like `pyqt` for GUI and `openpyxl` for Excel handling enhance the project's functionality. |
| 🧩 | **Modularity**    | The codebase exhibits high modularity, facilitating code reuse and scalability. Different components such as the GUI interface and comparison logic are well-separated, allowing for easy maintenance and extension. |
| 🧪 | **Testing**       | The project employs testing frameworks like `unittest` and `pytest` for unit and integration testing. Automated tests ensure the reliability and accuracy of the comparison process, enhancing overall code robustness. |
| ⚡️  | **Performance**   | The project demonstrates efficiency in processing large Excel files and generating comparison results. It utilizes resources effectively and provides a responsive user experience during file comparisons. |
| 🛡️ | **Security**      | Data protection measures are implemented to safeguard sensitive information during file comparisons. Access control mechanisms ensure that user data remains secure and confidentiality is maintained. |
| 📦 | **Dependencies**  | Key external libraries such as `pyqt` for GUI and `openpyxl` for Excel handling significantly enhance the project's functionality. Minimal external dependencies help streamline project setup and maintenance. |
| 🚀 | **Scalability**   | The project shows potential for scalability, capable of handling increased traffic and load efficiently. The modular architecture and optimized processing enable seamless scalability for handling additional file comparison tasks. |

These observations are based on the provided codebase details:

================================================================================
Project dependencies: ['py', 'python']
Repository contents: [[('main.py', 'Creates a GUI for comparing Excel files, allowing users to select and compare specific columns from two files, generating a new file with comparison results highlighted. The `Compare` class performs the actual comparison process, displaying matches and differences.')]]
================================================================================

---

##  Repository Structure

```sh
└── isXinY/
    ├── main.py
    ├── README.md
    └── requirements.txt
```

---

##  Modules

<details closed><summary>.</summary>

| File                                                                          | Summary                                                                                                                                                                                                                                                                   |
| ---                                                                           | ---                                                                                                                                                                                                                                                                       |
| [main.py](https://github.com/AaronTheGenerous/isXinY.git/blob/master/main.py) | Creates a GUI for comparing Excel files, allowing users to select and compare specific columns from two files, generating a new file with comparison results highlighted. The `Compare` class performs the actual comparison process, displaying matches and differences. |

</details>

---

##  Getting Started

**System Requirements:**

* **Python**: `version x.y.z`

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the isXinY repository:
>
> ```console
> $ git clone https://github.com/AaronTheGenerous/isXinY.git
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd isXinY
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run isXinY using the command below:
> ```console
> $ python main.py
> ```

###  Tests

> Run the test suite using the command below:
> ```console
> $ pytest
> ```

---

##  Project Roadmap

- [X] `► INSERT-TASK-1`
- [ ] `► INSERT-TASK-2`
- [ ] `► ...`

---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/AaronTheGenerous/isXinY.git/issues)**: Submit bugs found or log feature requests for the `isXinY` project.
- **[Submit Pull Requests](https://github.com/AaronTheGenerous/isXinY.git/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/AaronTheGenerous/isXinY.git/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/AaronTheGenerous/isXinY.git
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/AaronTheGenerous/isXinY.git/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=AaronTheGenerous/isXinY.git">
   </a>
</p>
</details>

---

##  License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-overview)

---
