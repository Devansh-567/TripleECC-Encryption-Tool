# 🔐 Triple ECC Encryption Tool

An advanced encryption tool that uses **Triple Curve Elliptic Curve Cryptography (ECC)** for secure message encryption, decryption, and performance comparison. This tool leverages three different ECC curves in parallel, significantly boosting security and resistance against cryptographic attacks.

---

## 🚀 Features

- 🔁 **Triple ECC Encryption** using three parallel elliptic curves (secp256k1, Curve25519, NIST P-224)
- 🧠 **Message Encryption/Decryption**
- 📊 **Security Comparison** with traditional ECC
- 🧪 **Attack Resistance Simulation**
- 🖼️ GUI interface using `Tkinter` and `Matplotlib`

---

## 📌 What It Is

Traditional ECC uses a single curve to secure data. This project explores the idea of **parallel multi-curve encryption** — applying three elliptic curves simultaneously to encrypt the same message. This increases entropy, unpredictability, and resistance against attacks.

It's a simple but powerful **educational simulation** of how layered cryptography could improve modern encryption schemes.

---

## 🧠 What It Does

- 🔐 Encrypts and decrypts messages using **three different ECC curves**
- 📊 Benchmarks the **performance** (time) of traditional ECC vs. triple ECC
- 🛡️ Simulates and visualizes **attack resistance**
- 📈 Displays graphs using `matplotlib`
- 🖼️ Includes a clean, intuitive GUI using `tkinter`

---

## 📈 Results

### ✅ Security Time Comparison

- **Triple ECC Average Time (10 runs)**: `~702.3745 ms`
- **Traditional ECC Average Time (10 runs)**: `~1.9203 ms`

💡 Triple ECC is slower (as expected), but exponentially harder to break due to multi-curve encryption.

### ✅ Attack Resistance Simulation

This shows how many simulated attacks were successfully resisted across 10 runs.

- 🟩 **Triple ECC** resists **5x–10x** more attacks than traditional ECC in all runs
- 🟥 **Traditional ECC** fails under heavier brute-force attempts

### ✅ Decryption Check

After decryption, the same message is recovered from each of the three curves:

```python
['Devansh', 'Devansh', 'Devansh']
```

---

## 🧰 Technologies Used

- Python Language
- tkinter – GUI
- matplotlib – plotting performance graphs
- Built-in: math, time, random, hashlib

---

## ⚙️ How to Run

```bash
git clone https://github.com/Devansh-567/TripleECC-Encryption-Tool.git
cd TripleECC-Encryption-Tool
pip install -r requirements.txt
python app.py

```
