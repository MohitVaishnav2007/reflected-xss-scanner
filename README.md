## 🛡 XSS Vulnerability Scanner (Basic)

This is a simple Python-based tool to detect basic reflected XSS (Cross-Site Scripting) vulnerabilities by injecting common payloads into URL parameters and analyzing the response.


---

## 🚀 Features

- Tests URL parameters for possible XSS vulnerabilities.

- Injects multiple common XSS payloads.

- Detects reflection of payloads in server responses.

- Easy to use and customize for testing purposes.



---

## 🧑‍💻 Technologies Used

- Python 3.x

- requests library

- urllib.parse for URL manipulation



---

## 🔧 Installation

1. Clone the repository:



git clone https://github.com/MohitVaishnav2007/xss-vulnerability-scanner.git

2. Navigate to the project directory:



cd xss-vulnerability-scanner

3. Install required dependencies:



pip install requests


---

## ⚙ Usage

python3 xss_scanner.py

You will be prompted to enter the target URL with query parameters. Example:

http://example.com/page.php?param=value


---

## 📌 Example Test URL

https://xss-game.appspot.com/level1/frame?query=test


---

## ⚠ Disclaimer

This tool is designed for educational purposes and authorized testing only.
Do NOT use it on websites without explicit permission.
The developer is not responsible for any misuse.


---

## 💜 Author

Developed by Mohit Vaishnav


---

## 🌟 Contribution

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


---