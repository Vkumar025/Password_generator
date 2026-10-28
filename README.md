#  Python Password Manager & Generator

A lightweight, user-friendly desktop application built with Python and Tkinter for generating strong passwords and managing user credentials securely on your local system.

---

## Features

* **Customizable Password Generation:** Create passwords of variable length (from 8 to 32 characters).
* **Multiple Complexity Levels:**
  * **Low:** Lowercase letters only
  * **Medium:** Uppercase and lowercase letters
  * **Strong:** Uppercase, lowercase, numbers, and special symbols
* **Clipboard Integration:** Instantly copy generated passwords directly to your clipboard with a single click using `pyperclip`.
* **Local Storage:** Automatically saves web credentials (username, password, and website URL) locally into a structured text file (`info.txt`).
* **View Credentials:** Retrieve and print all saved logins directly into the terminal window.

---

##  Tech Stack & Requirements

* **Language:** Python 3.x
* **GUI Framework:** `tkinter`, `tkinter.ttk`
* **Dependencies:** `pyperclip`

---

##  Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git
   cd <your-repo-name>
