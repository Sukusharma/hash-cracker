# Hash-cracker
<h1 align="center">
  <br>
  <img src="https://image.ibb.co/bSwkMe/bitmap.png" alt="Hash Buster" width="150">
  <br>
  Hash Buster 🔐
  <br>
</h1>

<h4 align="center">Bust hashes in seconds + Convert your string to hash instantly</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.6%2B-blue.svg">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey">
</p>

---

## 💡 Features

- **UNIQUE Feature**✨ Easily Convert any plain string into multiple hash formats (MD5, SHA1, SHA256, SHA512
- ✅ Automatic hash type detection
- 🔓 Crack MD5, SHA1, SHA256, SHA384, SHA512 hashes
- 📂 Extract hashes from files or entire directories (recursive)
- ⚡ Multi-threaded for faster cracking
)

---

## 🛠 Installation

> ⚠️ Make sure you're using Python 3+

Clone the repo:

```bash
git clone https://github.com/yourusername/hash-buster.git
cd hash-buster
pip install -r requirements.txt 
```

Run it directly
```
python hash.py
```

⚙️ Usage
Crack a single hash:

```
python hash.py -s <hash>
```
Crack all hashes from a file:
```

python hash.py -f hashes.txt
```
Crack hashes from a directory recursively:
```

python hash.py -d /path/to/folder
```

✨ Convert a string to hashes :

```
python hash.py --string "anything"
```


🧠 **About**

This is a modified version of the original Hash Buster tool with added support for converting strings into multiple hash formats. Improved and maintained by our group as a learning + practical cybersecurity utility.
