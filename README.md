# Tagman CLI 3.Woah - Lightweight Tagging System for Linux 🏷️✨
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Shell Script](https://img.shields.io/badge/Built%20With-Bash-green)](https://www.gnu.org/software/bash/)
[![Tagman Version](https://img.shields.io/badge/Tagman-3.Woah-red)](#)

Welcome to **Tagman CLI 3.Woah**, a lightweight, yet robust file and directory tagging system for Linux. Designed for project management and general organization, Tagman delivers a simple, intuitive interface for tagging files and directories. Its lightweight nature ensures that it integrates seamlessly with any Linux environment, making it ideal for developers, project managers, or anyone looking to organize their files in a snap.

---

## **Features**
- **System-wide tagging:** Assign tags to files or directories from anywhere in your Linux system.
- **Lightweight and fast:** Pure Bash implementation—no external dependencies required.
- **Easy tag management:** Add, list, and search for tags with minimal effort.
- **Inspiration:** The more you use it, the better you are.

---

## **Getting Started**

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Tagman-CLI.git
   cd Tagman-CLI
   ```
   
2. Install the script:
    ```bash
    chmod +x tagman
    mv tagman ~/.local/bin/
    ```
3. Ensure `~/.local/bin` is in your `PATH`. Add this to you `.bashrc` or `.zshrc` if needed:
    ```bash
    export PATH=$PATH:~/.local/bin
    ```
    
4. Reload your shell:
    ```bash
    source ~/.bashrc
    ```
    
5. Run the program:
    ```bash
    tagman
    ```

---

## **Usage**
### **Main Menu**

Tagman CLI starts with a simple menu:
  ```bash
  -----------------
  Tagman CLI 3.Woah
  -----------------
  Choose an option:
  1. Tag a file or directory
  2. Search for a file or directory by tag
  3. List current directory tags
  4. Exit
  ```

1. **Tag a File or Directory:** Assign one or more tags to a file or directory.
2. **Search by Tag:** Find files or directories by their assigned tags.
3. **List Current Directory Tags:** View tags assigned to the current working directory.
4. **Exit:** Leave the program.


## Examples

1. **Tagging the Current Directory**
  ```bash
  Tag the current directory? (y/n): y
  Enter tags (comma-separated): project, important, notes
  Tags updated for /home/user/my-project: project, important, notes
  ```

2. **Searching for Tags**

    ```bash
    Enter tag to search: important
    Searching for tag 'important'
    Results:
    /home/user/my-project
    ```
3. **Listing Current Directory Tags**

    ```bash
    Current tags for /home/user/my-project:
    project, important, notes
    ```
**How It Works**

- Tags Database: Stored in a lightweight file at `~/.tags.db`, making Tagman fast and portable.
- Bash-powered: Built entirely in Bash for simplicity and compatibility.
- Effortless Management: Minimalist input prompts ensure you’re always one step ahead of file chaos.

**Peace be with you, starlight.**