# Data-Privacy-Security
# 🛡️ Steganography Project 

## 📌 Overview

This project demonstrates basic techniques of **steganography**, the practice of hiding secret data within ordinary files such as images. It includes two practical implementations:

1. Using **OpenStego software**
2. Using **Command Prompt (CMD)**

---

## 🎯 Objectives

* Learn how to conceal sensitive information inside image files.
* Understand password-protected data hiding.
* Explore command-line techniques for file embedding.

---

## 🧪 Practical 1: Steganography Using OpenStego

### 🔧 Requirements

* OpenStego software
* A cover image file
* A message file (text or other data)

### 🚀 Steps

1. Download and install **OpenStego**.
2. Launch the application.
3. Select **"Hide Data"** option.
4. Choose the file to hide under **Message File**.
5. Select an image under **Cover File**.
6. Enter a secure password.
7. Specify the output file location.
8. Click **"Hide Data"** and wait for completion.

### 🔓 Extracting Data

1. Open OpenStego.
2. Select **"Extract Data"**.
3. Choose the stego-image.
4. Enter the password to retrieve the hidden file.

### ✅ Output

The secret message is successfully embedded within the image and can only be retrieved using the correct password.

---

## 🧪 Practical 2: Hiding Files Using Command Prompt (CMD)

### 🔧 Requirements

* A cover image (e.g., `.jpg`)
* A file to hide (e.g., `.zip`, `.txt`)
* Windows Command Prompt

### 🚀 Steps

1. Place both files in the same directory.

2. Open Command Prompt in that directory.

3. Run the following command:

   ```
   copy /b image.jpg + secret.zip output.jpg
   ```

4. Press **Enter**.

5. Verify the output file (`output.jpg`).

### 📂 Accessing Hidden Data

* Rename the output file extension from `.jpg` to `.zip`.
* Extract using any archive tool.

### ✅ Output

The secret file is successfully embedded inside the image file.

---

## ⚠️ Notes

* Always remember the password used in OpenStego.
* Ensure file extensions are handled correctly when extracting data.
* These techniques are for educational purposes only.

---

## 📚 Conclusion

This project highlights simple yet effective methods of hiding information using both GUI-based tools and command-line operations. It builds foundational understanding of data security and steganographic techniques.

---
