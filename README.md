# 🔳 QR Code Generator (Streamlit)

A simple and powerful **QR Code Generator** built with **Python**, **Streamlit**, and **qrcode**.  
Enter any text or URL and instantly generate a **high-quality QR Code**, with the option to download the PNG file.

---

## 🚀 Features

- Generate QR Codes from **text** or **links**
- High-resolution QR image (error correction: *High*)
- Downloadable PNG file
- Clean, responsive Streamlit interface
- Automatic state saving using `st.session_state`
- “Clear” button to reset input and QR code

---

## 🛠️ Technologies Used

- **Python 3**
- **Streamlit**
- **qrcode** library  
- **Pillow (PIL)** for image handling

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/qr-code-generator.git
cd qr-code-generator
```

Install dependencies with pip:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install streamlit qrcode pillow
```

---

## ▶️ Running the App

Start the Streamlit server:

```bash
streamlit run qr_generator.py
```

Streamlit will display a URL like:

```
http://localhost:8501
```

Open this link in your browser.

---

## 🌐 Hosting Options

You can host the app on:

- **Streamlit Community Cloud** (free)
- **Local server** inside your network
- **VPS / cloud server**  
- Your own PC (with port forwarding)

To allow LAN access:

```bash
streamlit run qr_generator.py --server.address 0.0.0.0
```

Then access it via:

```
http://YOUR_LOCAL_IP:8501
```

---

## 📁 Project Structure

```
qr-code-generator/
│
├── qr_generator.py      # Main Streamlit app
├── requirements.txt     # App dependencies
└── README.md            # Project documentation
```

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute it.

---

## ❤️ Acknowledgements

Built with ❤️ using **Python + Streamlit**.