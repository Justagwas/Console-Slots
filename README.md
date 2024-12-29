# Console Slots/Slots Machine

A simple C++ console application that mimics a slot machine game using fake money.  

Play with $100 starting cash, spin the slots, and see if you can win big-no real money involved!

---

## 📋 Features

1. **Gameplay**  
   Spin the slot machine with a cost of $10 per spin and see if you win or lose.

2. **Interface**  
   Clear and minimal ASCII art design.

3. **Data**  
   Saves your current game progress (money, spins, etc.) to a text file, which is reused the next time you play.

4. **No Real Money**  
   This game is for entertainment only, using fake currency.

---

## ❓ How to Use

### Running the Precompiled Executable
1. **Download the Executable**  
   Visit the [Latest Release](https://github.com/Justagwas/Console-Slots/releases/latest) and download `Slots_Machine.exe`.

   [![Download Slots_Machine.exe](https://img.shields.io/badge/▼%20Download▼-Slots_Machine.exe-blue?style=for-the-badge)](https://github.com/Justagwas/Console-Slots/releases/latest/download/Slots_Machine.exe)

2. **Run the Executable**  
   Simply double-click the downloaded file to launch the game.  

3. **Gameplay**  
   Use the instructions displayed in the console to spin the slots or quit the game.

**Game Progress**  
The application creates a **text file** in the same directory as the executable to store your game progress (money balance, spin counts, etc.).

---

## 📦 Packaging Instructions

### Building with Visual Studio 2022
1. **Clone the Repository**  
   Clone or download the repository to your local machine.

2. **Open the Project**  
   Open the `.sln` file (`Slots Machine.sln`) in Visual Studio 2022.

3. **Build the Executable**  
   - Go to **Build** → **Build Solution** or press **Ctrl + Shift + B**.  
   - The compiled executable will be located in the `Release/` or `Debug/` folder.

4. **Run the Executable**  
   Navigate to the output folder and double-click the executable file.

### Building without Visual Studio
If you do not have Visual Studio installed, follow these steps:

#### Using `g++` (MinGW or any C++ Compiler)
1. **Install a C++ Compiler**  
   Ensure you have a C++ compiler installed. For Windows, you can use [MinGW](https://sourceforge.net/projects/mingw/).

2. **Compile the Code**  
   Open a terminal in the project folder which has `Slots Machine.cpp` and run the following command:
   ```bash
   g++ "Slots Machine.cpp" -o Slots_Machine.exe
   ```

3. **Run the Executable**  
   The generated `Slots_Machine.exe` will be located in the same directory. Double-click to run.

---

## ⚠️ Warnings
- **Text File Creation**  
   This application will create a text file (e.g., `data.txt`) in the same directory as the executable. This file is used to store and load your game progress.

- **Fake Money Only**  
   This application is strictly for entertainment. No real monetary transactions are involved.

---

## 📷 Preview

![image](https://github.com/user-attachments/assets/0a4e598c-1506-475c-a80b-22367e358987)


---

## 🔗 Links & Statistics

[![Latest Release](https://img.shields.io/badge/🔖%20Latest%20Release-blue?style=for-the-badge)](https://github.com/Justagwas/Console-Slots/releases/latest)  
[![Issues](https://img.shields.io/badge/🐛%20Issues-orange?style=for-the-badge)](https://github.com/Justagwas/Console-Slots/issues)  
[![Contributors](https://img.shields.io/github/contributors/Justagwas/Console-Slots?label=👥%20Contributors&style=for-the-badge)](https://github.com/Justagwas/Console-Slots/graphs/contributors)  
[![Download Count](https://img.shields.io/github/downloads/Justagwas/Console-Slots/total?label=⬇️%20Total%20Downloads&style=for-the-badge&color=blue)](https://github.com/Justagwas/Console-Slots/releases)  
[![Open Issues](https://img.shields.io/github/issues/Justagwas/Console-Slots?label=🐛%20Open%20Issues&style=for-the-badge)](https://github.com/Justagwas/Console-Slots/issues)  
[![Last Commit](https://img.shields.io/github/last-commit/Justagwas/Console-Slots?label=🕒%20Last%20Commit&style=for-the-badge)](https://github.com/Justagwas/Console-Slots/commits)  

---

## 📜 License

[![License](https://img.shields.io/github/license/Justagwas/Console-Slots?label=📝%20License&style=for-the-badge)](LICENSE.txt)
