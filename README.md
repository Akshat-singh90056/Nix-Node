# Nix-Node
Nix-Node is a terminal-based text editor inspired by nano. Written in C within under 1300 lines of code, it features syntax highlighting and search functionality, making it a lightweight yet powerful tool for terminal users. Built using the guide from KILO - Build Your Own Text Editor by Antirez, with full credit for inspiration.

Link of the article - https://viewsourcecode.org/snaptoken/kilo/

### Table Of Contents
- [Installation](#installation)
- [USAGE](#usase)
- [IMAGES/VIDEOS](#IMAGES)
- [CREDITS](#credits)

## Images
### Syntax Highlighting
![MAIN EDITOR](https://github.com/Akshat-singh90056/Nix-Node/blob/main/Screenshot%20from%202024-11-20%2022-02-12.png)

### Main Editor
![SYNTAX](https://github.com/Akshat-singh90056/Nix-Node/blob/main/Screenshot%20from%202024-11-20%2022-03-37.png)


## Installation

### Prerequisites
- Ensure you have GCC (GNU c compiler)
- Make sure you have MAKE installed(optional)
- Ensure you have git installed

### METHOD 1 - using MAKE
#### STEPS TO INSTALL
1. Clone the repository OR just download nanopad.c:
    ```bash
        git clone https://github.com/Akshat-singh90056/Nix-Node
2. Navigate to Directory
    ```bash
        cd Nix-Node
3. Install Make(skip it if you have already)
    ```bash
        sudo apt install make
4. Compile using make
    ```bash
        make
5. RUN
    ```bash
        ./kilo

## USASE
- Search
    1. CTRL+F to search
    2. Use Arrow keys to go to next result or previous
    3. Use ESC to exit search

- Saving a File
    CTRL+S to save

- Quiting NanoPad
    1. CTRL+Q to quit
    2. Press CTRL+Q 3 times if your file is not saved!


## CREDITS

- [AKSHAT](https://github.com/Akshat-singh90056)
- [ANTIREZ'S KILO](https://viewsourcecode.org/snaptoken/kilo/) 
