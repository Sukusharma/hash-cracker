# Hash-cracker
<h1 align="center">
  Hash cracker 🔐
  <br>
</h1>

<h4 align="center">Fast Hash Cracking + Instant String-to-Hash Conversion</h4>


A lightweight Python tool to crack hashes and now also convert strings to various hash formats in seconds. Designed for speed, simplicity, and real-world practicality.

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
