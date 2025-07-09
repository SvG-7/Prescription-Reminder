# 💊 Prescription Reminder for Elderly Patients

This project was created as part of our CSE 1320 course. It is a C-based application designed to help elderly patients manage and get reminders for their daily medication schedules.

---

## 🧠 Project Overview

The program:
- Lets users add and store prescriptions
- Displays scheduled medication reminders based on time
- Uses file handling to save data persistently
- Runs in a simple command-line interface (CLI)

---

## ⚙️ Features

✅ Add patient name and prescription schedule  
✅ Store data using file handling (`fopen`, `fprintf`, `fscanf`)  
✅ Trigger reminders based on system time  
✅ Simple menu-based interaction  
✅ Built using C and `struct` arrays  

---

## 📂 File Structure

| File Name      | Description                             |
|----------------|-----------------------------------------|
| `main.c`       | Main driver file                        |
| `reminder.c`   | Contains functions for scheduling logic |
| `patients.txt` | Stores patient and prescription data    |
| `README.md`    | This documentation file                 |

---
## 🧠 Code Overview

Here’s a breakdown of how the code works:

### 🔸 `main.c`
- Handles the **menu-driven interface**
- Allows the user to:
  - Add a patient and their prescriptions
  - View current prescriptions
  - Remove or update prescriptions
  - Exit the program
- Calls functions from `reminder.c`

### 🔸 `reminder.c`
- Contains functions for:
  - Setting up reminders
  - Comparing current system time with stored schedule
  - Alerting the user when it’s time for medication
- Uses `time.h` to fetch real-time info

### 🔸 `patients.txt`
- Stores all prescription details in a text format
- Acts as a simple file-based database
- Used with `fopen`, `fprintf`, and `fscanf`

### 🗂 Example Functions:
```c
void addPrescription() {
    // Takes user input for patient name, medicine, and time
    // Stores the data in patients.txt using fprintf
}


## 🚀 How to Run

1. Open Terminal or Command Prompt  
2. Compile the code:

   ```bash
   gcc main.c -o prescription

## 👨‍💻 Team Members

- Joseph Ramsay  
- Soham Panchal 
- Krishna Valkambe  
- Saish Gondkar
