# python-keylogger
simple keylogger built with the support of jason madakor youtube videos

# ⌨️ Simple Python Keylogger (For Educational Use Only)

This project is a basic Python-based keylogger built for educational purposes. It demonstrates how keystroke logging works under the hood, and is intended to help learners understand how malicious actors might abuse this technique so defenders can better detect and prevent it.

⚠️ **Disclaimer:** This keylogger is for ethical and educational use only. Do not run this on any machine or network you do not own or have explicit permission to test.

---

## 📌 Features

- Records all keystrokes using `pynput`
- Appends logs to a local file
- Logs can be timestamped or obfuscated for demonstration purposes
- Lightweight and easy to modify

---

## 🛠️ Requirements

- Python 3.x
- `pynput` library

Install with pip:

```bash
pip install pynput
```

---

## 🚀 Usage

Clone the repo and run the script:

```bash
git clone https://github.com/your-username/simple-python-keylogger.git
cd simple-python-keylogger
python keylogger.py
```

This will log all keystrokes to `keylog.txt` in the same directory.

---

## 🔍 Example Output

```plaintext
[2025-04-22 10:32:04] H
[2025-04-22 10:32:04] e
[2025-04-22 10:32:05] l
[2025-04-22 10:32:05] l
[2025-04-22 10:32:05] o
[2025-04-22 10:32:06]   (space)
[2025-04-22 10:32:06] W
[2025-04-22 10:32:06] o
[2025-04-22 10:32:07] r
[2025-04-22 10:32:07] l
[2025-04-22 10:32:08] d
```

---

## 🧠 Educational Value

- Understand how basic keyloggers work
- Practice safe analysis and ethical tool development
- Learn about keystroke logging countermeasures

---

## 🔐 Ethics Reminder

Using keyloggers without consent is illegal and unethical. This tool is meant for **learning only**, and should **never be used in real-world scenarios** outside of legal test environments.

---

## 🤝 Contributions

Feel free to contribute by:
- Adding encryption or stealth features for demonstration
- Writing detection scripts for defensive labs
- Improving the logging format

---

## 📌 License

MIT License

---

## 📣 Final Note

Build responsibly. Learn deeply. Defend better.
