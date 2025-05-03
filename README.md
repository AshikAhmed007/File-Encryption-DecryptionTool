# 🔐 File Encryption/Decryption Tool

A simple command-line tool to securely **encrypt** and **decrypt** files using Python and the `cryptography` library. This utility allows users to generate a secret key, encrypt any file with it, and decrypt it later using the same key.

---

## 📦 Features

- ✅ Generate a secure secret key (`secret.key`)
- ✅ Encrypt files with AES-based Fernet encryption
- ✅ Decrypt files with the correct key
- ✅ CLI-based interaction
- ✅ Basic error handling

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.x
- `cryptography` library

Install the required module:

```bash
pip install cryptography
```

---

## 🛠️ Usage

### ▶️ Run the Script

```bash
python your_script_name.py
```

You will see a menu like this:

```
File Encryption/Decryption Tool
1. Generate Key
2. Encrypt File
3. Decrypt File
Select an option (1/2/3):
```

---

### 1. Generate Key

Generates a key and saves it to `secret.key`.

```text
Select an option (1/2/3): 1
[+] New key generated and saved as 'secret.key'
```

---

### 2. Encrypt File

Encrypts any file using the secret key.

```text
Select an option (1/2/3): 2
Enter the path of the file to encrypt: myfile.txt
Enter the output encrypted file name: myfile_encrypted.txt
[+] File encrypted and saved as 'myfile_encrypted.txt'
```

---

### 3. Decrypt File

Decrypts a previously encrypted file.

```text
Select an option (1/2/3): 3
Enter the path of the file to decrypt: myfile_encrypted.txt
Enter the output decrypted file name: myfile_decrypted.txt
[+] File decrypted and saved as 'myfile_decrypted.txt'
```

---

## 📁 File Structure

```
.
├── your_script_name.py
├── secret.key
├── myfile.txt
├── myfile_encrypted.txt
├── myfile_decrypted.txt
```

---

## ⚠️ Security Tips

- **Keep `secret.key` safe and private.**
- Without the correct key, decryption will fail.
- Do not share encrypted or decrypted sensitive files without proper encryption and key management.

---

## 👨‍💻 Author

**Ashik Ahmed**  
Web Pentester | Cybersecurity Enthusiast  
📧 ashikahmedgd007@gmail.com  
🔗 [GitHub](https://github.com/AshikAhmed007) | [LinkedIn](https://www.linkedin.com/in/ashikahmedtoha/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
