# 🖥️ Shutdown Windows System using C

This C program shuts down your Windows computer automatically when run. It uses the system command to call Windows' built-in `shutdown` utility. This is a simple automation example for beginners learning C and how it can interact with the operating system.

---

## ⚙️ What This Program Does

- When you run the program, it gives a warning and shuts down the system after 1 minute (default).
- Useful for testing automation, writing cleanup scripts, or learning how system-level commands work in C.

---

## 📋 Features

- ⚠️ Warning message before shutdown
- ⏱️ Custom shutdown delay can be set
- 💻 Uses `system()` call in C to interact with Windows

---

## 🧑‍💻 Code Used

```c
#include <stdlib.h>

int main() {
    system("shutdown -s -t 60");  // shuts down system after 60 seconds
    return 0;
}


🛠️ How to Compile and Run

1. Save the file as shutdown.c

2. Open Command Prompt or Terminal in the file’s folder

3. Compile the code using GCC:
![image](https://github.com/user-attachments/assets/25da1e1f-d5f5-4d5c-9952-c2b4f728bdd8)
4. Run the executable:
![image](https://github.com/user-attachments/assets/b7754e69-2f11-40b2-8de7-779a6aa4c3dc)

⚠️ Warning this program will turn off your computer.
Don't run it unless you are ready or just testing it.
Use responsibly and only on your own system.



