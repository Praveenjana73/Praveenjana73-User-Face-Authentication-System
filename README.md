#  🔐  User Face Authentication System 🧑‍💻📸

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
##  🖼️Screenshot

**Home Page**

![Image](https://github.com/user-attachments/assets/1f76869e-af89-47c7-a141-27b8b54c39ed)

This is the **homepage** of the **User Face Authentication System**, a secure authentication platform using facial recognition.  

- **Header:** Displays the system name with navigation links (**Home, Login, Signup**).  
#### **Main Section:**  
  - **Title:** "WELCOME TO FACE AUTHENTICATION SYSTEM"  
  - **Description:** Explains how facial recognition improves security and convenience over traditional login methods.  
- **Call-to-Action:** A **"Get Started"** button encouraging users to sign up or log in.  

The design is **clean, modern, and user-friendly**, focusing on enhanced security and ease of access. 🚀

**Sign-Up Page**

![Image](https://github.com/user-attachments/assets/b1ffd2a8-3cda-454a-af56-ffab4259708c)
### **Sign-Up Page – User Face Authentication System**  

This is the **Sign-Up Page** of the **User Face Authentication System**, allowing users to create an account securely.  

#### **Header:**  
- Displays the system name with navigation links (**Home, Login, Signup**).  

#### **Main Section:**  
- **Title:** "SIGN UP"  
- **Input Fields:**  
  - Username field (e.g., "Praveen").  
  - Password field (hidden for security).  
- **Call-to-Action:**  
  - A **"Sign Up"** button to submit the registration form.  

This page enables new users to register and access the system using facial authentication. 🚀

**Login Page**

![Image](https://github.com/user-attachments/assets/c802de16-81ab-4b1f-8eef-cca37ad06e86) 
### **Login Page - User Face Authentication System**  
A secure authentication platform using facial recognition.  

#### **Header:**  
- Displays the system name: **"USER FACE AUTHENTICATION SYSTEM"**  
- Navigation links: **Home, Login, Signup** for easy access.  

#### **Main Section:**  
- **Title:** "LOGIN"  
- **Description:** Provides two login options for security and convenience.  
- **Traditional Login:**  
  - Input fields for **Username** and **Password**  
  - **"Login"** button (yellow) for standard authentication.  
- **Facial Authentication:**  
  - "OR" text separates login methods.  
  - **"Login with Face"** button (orange) to enable secure facial recognition-based login.  


**Dashboard**

![Image](https://github.com/user-attachments/assets/9ff52554-d87f-41c7-9e69-15879dc46b4a)

### **Dashboard - User Face Authentication System**  
A secure authentication platform using facial recognition.  

#### **Header:**  
- Displays the system name: **"USER FACE AUTHENTICATION SYSTEM"**  
- Navigation links: **Home, Admin, Logout** for quick access.  

#### **Main Section:**  
- **Title:** "WELCOME, PRAVEEN 👋"  
- **Description:** Confirms successful login with a personalized welcome message.  
- **Comparison Table:** Highlights the **advantages of the proposed face authentication system** over traditional login methods.  

#### **Existing System vs. Proposed System:**  
| **Existing System** | **Proposed System** |  
|-------------------|-------------------|  
| Uses only username & password for login | Uses **face authentication** for enhanced security |  
| Prone to password theft & hacking | Face authentication makes login **more secure** |  
| Users may forget passwords | No need to remember passwords, just use your **face** |  
| Login can be shared with others | Only the **registered face** can log in |  
| Traditional authentication system | **Advanced AI-based authentication system** |  




## 📜 License
This project is open-source and available under the MIT License.

## 📞 Contact
For any issues or suggestions, feel free to reach out or open an issue on GitHub.

