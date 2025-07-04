# 🖼️ Neural Style Transfer Web App
Transform your photos into artwork — powered by Deep Learning and inspired by famous painters. This project uses Neural Style Transfer to combine the content of one image with the artistic style of another using a simple and intuitive web interface.




![Screenshot 2025-07-04 105552](https://github.com/user-attachments/assets/83141b34-66c4-42da-9e03-da235c419dfe)
![Screenshot 2025-07-04 120930](https://github.com/user-attachments/assets/618af975-3b8a-4f2f-9a05-087bc2cdab94)
![Screenshot 2025-07-04 120955](https://github.com/user-attachments/assets/f52432d1-339d-4e21-b63b-edbeed1b52df)
![sabeerrrrr](https://github.com/user-attachments/assets/be431db1-39bc-4cc4-97f6-070475c5839f)



## 🚀 Features
Upload your own content & style images

Real-time style transfer using TensorFlow Hub

Clean, responsive Flask web app interface

Supports JPG/PNG uploads

Download your styled result

## 🧠 How It Works
The app uses a pre-trained neural network that performs feature extraction and reconstruction.

Style and content are separated in latent space and then recombined to generate a new image.

💡 Did you know? Neural Style Transfer relies on Gram matrices to capture texture patterns — not just pixel values!

## 🛠️ Tech Stack
Python 3

TensorFlow & TensorFlow Hub

Flask

NumPy, Pillow (PIL)

HTML/CSS for front-end


## 📁 Project Structure
```
NeturalStyleTransfer/
├── static/ # CSS, JS, images
├── templates/ # HTML templates for Flask
├── app.py # Flask application backend
├── style_transfer.py # Neural Style Transfer logic
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```
Clone the repository

```bash
git clone https://github.com/yourusername/neural-style-transfer.git
cd neural-style-transfer
```
Install dependencies

```bash
pip install -r requirements.txt
Run the Flask app
```
```bash
python app.py
Visit http://127.0.0.1:5000 in your browser
```
## ✅ Requirements
Python 3.7+

Internet connection (for TensorFlow Hub model download)

## 📌 To Do / Future Improvements
Add multiple style fusion

Option to adjust style/content weights

Deploy with Streamlit or Hugging Face Spaces

Add dark mode front-end ✨

## 🤝 Credits
Pre-trained model: TensorFlow Hub
Nicholas Renotte
GitHub: https://github.com/nicknochnack
Inspired by the original NST paper by Gatys et al.

## 📜 License
MIT License © 2025 Sanjana Velma

