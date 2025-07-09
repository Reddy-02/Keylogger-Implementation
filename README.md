# 🔐 Keylogger Implementation – Ethical Hacking Project



A professional-grade Python-based keylogger tool built strictly for **educational and ethical cybersecurity demonstrations**. This project was developed as part of a **Cybersecurity & Ethical Hacking Internship** by D. Sai Srinivas Reddy to understand keystroke logging mechanisms and raise awareness about potential risks posed by malicious keyloggers.



---



## 📘 Overview

This tool captures keyboard input using the `pynput` library and logs all keystrokes with timestamps into a local file. The application runs silently in the background and demonstrates how keyloggers work internally — intended for learning, awareness, and ethical red-teaming exercises.



---



## 🚀 Features



- ✅ Captures and logs **all key presses**

- 🕒 Saves logs with **timestamped sessions**

- 📁 Automatically creates `logs/` directory

- ⚠️ Includes **ethical disclaimer** in code

- 👻 Supports **stealth `.exe` mode** (no console)

- 📦 Packaged `.exe` version with `PyInstaller`

- 🧵 Runs on **background thread** for smooth execution



---



## 🧠 Learning Objectives

- Understanding real-world keystroke interception methods

- Building awareness around malware & spyware vectors

- Strengthening blue-team defensive thinking

- Applying threading, logging, and file I/O in Python



---



## 🛠️ Technologies Used

| Area                 | Tools / Libraries       |

|----------------------|--------------------------|

| Language             | Python 3.12              |

| Keyboard Logging     | `pynput`                 |

| Log Management       | `logging`, `datetime`    |

| Threading            | Python `threading`       |

| Executable Packaging | `pyinstaller`            |



---



## 🗂️ Folder Structure

```

Keylogger_Project/

├── keylogger.py                # Main script

├── keylogger.exe              # Compiled executable

├── logs/                      # Directory for log files

│   └── keystroke_log_*.txt

├── README.md                  # Documentation

└── Project_Report_Keylogger.pdf  # Internship submission PDF

```
key-logger.exe (Link) -https://drive.google.com/file/d/114_3s_zpTkE5ywKZP3ur3xHDHBVEeBlg/view?usp=drivesdk

key-logger.py (Link) -https://drive.google.com/file/d/10QmqYAL4TIsLeX8F-oGWTh70zNkc974K/view?usp=drivesdk

---



## ▶️ How to Use



### 🔸 Running via Python:

```bash

python keylogger.py

```

- Starts listening for keystrokes

- Press `Ctrl + C` to stop



### 🔸 Running `.exe` (Silent Background):

```bash

pyinstaller --onefile --noconsole keylogger.py

```

- Produces `keylogger.exe` in `dist/`

- Run by double-clicking — logs silently



### 🔸 View Logs:

All logs will appear inside the `logs/` folder with timestamps.



---



## ⚠️ Disclaimer

> This tool is created strictly for **educational and ethical cybersecurity purposes only**. Unauthorized use for spying, monitoring, or any illegal activity is prohibited and punishable by law. Use only in environments you own or have permission to test.



---



## 👨‍💻 Author

**D. Sai Srinivas Reddy**  

B.Tech – Computer Science and Engineering  

Vignan's LARA Institute of Technology and Science  

📧 saisrinivasreddy456@gmail.com  

🔗 [LinkedIn](https://www.linkedin.com/in/sai-srinivas-reddy)  

🐙 [GitHub](https://github.com/Reddy-02)



---



## 📌 Notes

- Python must be installed for `.py` version

- `.exe` works offline without Python installed

- Log files are plain `.txt` for easy review



---



## 📦 Zip Submission

> Before submission, compress your project folder:

```

Keylogger_Project_SaiSrinivas.zip

```

Include:

- `keylogger.py`

- `keylogger.exe`

- `logs/`

- `README.md`



---



## 🔒 Project 3 Completed ✅

This tool showcases the practical understanding of how keyloggers work — helping raise awareness of potential threats and fostering stronger cybersecurity defense thinking.
