# NAND2TETRISPROJECTMANAGEMENTPART2-Project-0
PROJECT00

# NAND2TETRISPROJECTMANAGEMENTPART2-Project-0

## Project 0 – Setup & Environment

**Project Code:** PROJECT00
**Course:** Build a Modern Computer from First Principles (Nand2Tetris Part II)
**Institution:** Hebrew University of Jerusalem

---

## Overview

Project 0 is the **foundation project** of Nand2Tetris Part II. It focuses on **setting up the complete development environment** required for the course, including installation, configuration, and verification of all tools and simulators. This project ensures that you can successfully compile and run Jack programs, VM code, and Hack assembly programs in later projects.

---

## Objectives

* Install and configure **Java JDK 8+**.
* Set up the **Nand2Tetris Software Suite**.
* Configure **Hardware Simulator, CPU Emulator, and VM Emulator**.
* Verify installation by running a sample Jack program.
* Ensure proper environment setup for all subsequent projects.

---

## Folder Structure

```
Project0/
│── README.md
│── setup_scripts/
│   └── install_nand2tetris.sh
│── examples/
│   └── HelloWorld.jack
│── docs/
│   └── environment_setup_guide.pdf
```

---

## Getting Started

### Step 1: Install Java

Download and install **Java JDK 8 or later**.
Verify installation:

```bash
java -version
javac -version
```

### Step 2: Download Nand2Tetris Software Suite

* Official download: [Nand2Tetris Software](https://www.nand2tetris.org/software)
* Extract the software to a preferred directory.
* Make sure all path variables are set correctly for your OS.

### Step 3: Verify Environment

Run a sample program to confirm that the environment is working:

```bash
cd Project0/examples
java -jar path/to/JackCompiler.jar HelloWorld.jack
```

Check the output `.vm` file and run it in the VM Emulator or Hardware Simulator.

---

## Notes

* All folder paths must be correctly configured to avoid errors in compilation.
* This project lays the **foundation for all subsequent Nand2Tetris projects**.
* Follow the course honor code for all assignments.

---

## Author

**Aravind Kumar GS**
Email: `aravindkumar06062006@gmail.com`

---

## License

Educational purposes only. Do not distribute or claim as your own work.
