
# 🔐 Password Breach Checker

A simple Python script that checks if your password has ever been exposed in known data breaches, using the [Have I Been Pwned](https://haveibeenpwned.com/API/v3) API.

## 🚀 Features
- Uses SHA-1 hashing and the k-Anonymity model to ensure privacy.
- Sends only the first 5 characters of the hash to the API.
- Tells you if your password appears in any data breaches.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** `hashlib`, `requests`
- **Tools:** Sublime Text, Terminal

## 📦 How to Run

1. **Install requirements:**
   ```bash
   pip install requests
   ```

2. **Run the script:**
   ```bash
   python password_checker.py yourpasswords 
   ```
   Multiple passwords can be checked by seperating with space.

3. It will check if it has been compromised.

## 📌 Example Output

```
Your password was found 1472 times! You should probably change it!
```
or
```
Good news — no matches found. Your password has not been leaked.
```

## 🔐 Privacy Note
This script uses k-Anonymity, meaning **your full password or its full hash is never sent** to the API.

## 👨‍💻 Author
Tanishq Goyal  
B.Tech CSE @ Thapar Institute  
[LinkedIn](https://www.linkedin.com/in/tanishq-goyal-50b989309/)

---

*Built with Python, curiosity, and a bit of frustration with weak passwords.*
