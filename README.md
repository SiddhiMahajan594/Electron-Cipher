# 🔐 Electron-Cipher: Orbital Logic + AES Encryption

> A hybrid encryption system combining custom orbital-based bit permutation, Feistel networks, and AES for enhanced data security and visualization.

---

## 🌟 Key Features

- ✅ **Custom Orbital-Based Bit Permutation** using dynamic S-boxes (`s`, `p`, `d`, `f` shells)
- 🔁 **Feistel Mixing** for non-linear scrambling
- 🔒 **AES-256 Encryption (CBC mode)** for robust final encryption
- 🔑 **Password-Based Key Derivation** using PBKDF2 + SHA256
- 🎯 **Interactive UI** using IPyWidgets in Google Colab
- 📊 **Visualizations** for bit transformations and permutation mappings

---

## 🌟 Highlights

- ✅ **Custom Bit Permutation** using orbital shells (`s`, `p`, `d`, `f`)
- 🔁 **Feistel Mixing** for layered confusion
- 🔒 **AES (CBC Mode)** encryption with dynamic key derivation
- 🎨 **Bit-Level Visualizations** using Matplotlib
- 🧩 **Interactive UI** using IPyWidgets in Google Colab

---

## 🛠 How It Works

1. **Plaintext Input** → Binary Conversion  
2. **Feistel Mixing** (4 rounds) with orbital-specific nonlinear functions  
3. **Orbital S-box Permutation** using dynamic lookup tables  
4. **AES Encryption (CBC)** of permuted bits  
5. **Decryption Process**: AES → Inverse S-box → Reverse Feistel → Binary → Plaintext

---

## 🔑 Technologies Used

- `Python 3`
- `PyCryptodome` for AES encryption & key derivation
- `IPyWidgets` for interactive UI
- `Matplotlib` for bit-level visualizations
- `Google Colab` as the runtime environment

---

## 🖼 Example Output

- **Ciphertext** in Base64
- **Recovered Plaintext**
- Bit visualizations:
  - Original bits
  - Permuted bits
  - Orbital permutation diagram

---

## 📌 Instructions to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/19EmEYk3PvSRTErx660UR4R0hyD8En-Hf)
2. Run all cells (`Runtime > Run all`)
3. Enter plaintext and password in the widgets
4. Click `Encrypt & Decrypt`

---

## 🙋‍♀️ Author

**Siddhi Mahajan**  🔗 [GitHub](https://github.com/SiddhiMahajan594)

**Parth Lohia**  🔗 [GitHub](https://github.com/lohiaparth)

**Ayush Kothari**  🔗 [GitHub](https://github.com/ayushkothariii)

---

