# 🏥 User Face Authentication System

This project is a **User Face Authentication** application built with **Machine Learning** and **Flask**. It uses **OpenCV** and the **Face Recognition** library to authenticate users based on facial recognition.

---

## 🌟 Project Overview
This application allows users to sign up using their **username, password, and face image** and later log in using either **credentials** or **face recognition**. It enhances security and provides a seamless login experience.

---

## 🎯 Features
- 🤖 **Face Recognition Model**: Uses **OpenCV & Face Recognition Library** for authentication.
- 🌐 **Web Interface**: User-friendly interface built with **Flask**.
- 🖼 **Face Capture & Storage**: Stores user face images securely.
- 🔒 **Secure Authentication**: Login using either **credentials** or **face recognition**.
- 🏥 **Admin Panel**: View all registered users and manage data.

---

## 🛠 Technology Stack
- **Backend**: Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: OpenCV, Face Recognition, Flask-Login
- **Database**: SQLite / PostgreSQL (optional)

---

## 📂 Dataset
The application stores user images in the `static/faces/` directory for authentication.

**Note**: Ensure proper handling of images to maintain security and performance.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have **Python** installed on your system.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/user-face-authentication.git
   cd user-face-authentication
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

---

## 🌐 Access the Application
### Open a web browser and go to: http://127.0.0.1:5000/
### Register an account and try logging in with face authentication.

---

## 🧩 Project Structure
- **Backend**: Flask routes and authentication logic.
- **Frontend**: HTML, CSS, and JavaScript for the user interface.
- **Model**: Face Recognition logic using OpenCV.
- **Static Files**: Stores images and styling elements.

---

## ⚙️ How to Run the Code
Follow these steps to run the application:

1. **Install Dependencies**: Run `pip install -r requirements.txt`.
2. **Run the Server**: Start the Flask server using `python app.py`.
3. **Access the Application**: Open [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.

---


## 📜 License
This project is open-source and available under the MIT License.

## 📞 Contact
For any issues or suggestions, feel free to reach out or open an issue on GitHub.

