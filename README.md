# Image-Encryption-and-Decryption

# 🖼️ Image Encryption and Decryption GUI using Python

A simple GUI application that allows users to **encrypt and decrypt images** using basic pixel-level numerical transformation. This project demonstrates how image data can be manipulated and visualized with Python using **Tkinter**, **NumPy**, **Matplotlib**, and **PIL**.

---

## 🚀 Features

- 📁 Browse and load any `.jpg` image from your computer.
- 🔐 Encrypt the image by applying a numeric transformation.
- 🔓 Decrypt it back to the original form using the same number.
- 👁️ Display the original and decrypted image using `matplotlib`.
- 🧠 Educational illustration of reshaping and transforming image matrices.

---

## 🧠 How It Works

### 🔐 **Encryption**
- Load an image and reshape its 3D pixel matrix to 2D.
- Multiply all pixel values by a user-provided encryption number.
- Save the transformed matrix (`shape.csv`) and original shape (`shape1.csv`).

### 🔓 **Decryption**
- Load the encrypted CSV file.
- Divide pixel values by the same encryption number.
- Reshape to the original image shape and reconstruct the image.

> ⚠️ This is **not** secure encryption. It's meant for learning and demonstration only.

---

## 🧰 Built With

- 🐍 Python
- 🖼️ Tkinter – for GUI
- 🧮 NumPy – for matrix manipulation
- 📷 PIL (Pillow) – for image processing
- 📊 Matplotlib – for image visualization
- 🧾 CSV – for saving matrix data

---

## 📁 Project Structure
ImageEncryptDecrypt/
├── main.py
├── imagepath.csv
├── shape.csv
├── shape1.csv
├── Foto.png
├── foo.jpg
└── README.md


---

## 🖱️ How to Run

1. Clone this repo
2. Install the required dependencies:
pip install pillow numpy matplotlib opencv-python scikit-image pandas
3. Run the GUI:
   python main.py

   📌 Use Case
This project can be useful for:

Understanding basic image matrix manipulation.

Learning how GUI applications are made using Tkinter.

Demonstrating how reshaping and transforming image data works.

📎 To-Do / Improvements
 Add proper AES encryption for real-world security.

 Show thumbnail previews of images in the GUI.

 Improve UI with resizing and theme options.

 Add file format support beyond JPG (e.g., PNG, BMP).

📜 License
This project is open-source and free to use under the MIT License.


