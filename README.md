# 📌 Shopping App - Profile Page with Biometric Authentication

## 📌 Overview
This project is a **Shopping App** that includes a **Profile Page** with **Biometric Authentication** (Fingerprint). The profile page displays user details such as their **profile picture, full name, and email**. To enhance security, users must **authenticate using their fingerprint** before accessing their profile.

---

## 📌 What the Code Does?
✅ **Displays a profile icon** in the app bar.  
✅ **Implements a Profile Page** containing user information (profile picture, name, email).  
✅ **Uses biometric authentication** (fingerprint) to restrict access to the profile page.  
✅ **Enhances the UI** with a modern design, gradients, shadows, and buttons.  

---

## 📌 How the Code Works?

### 1️⃣ Profile Icon in AppBar
- A **profile icon** is placed in the top-right corner of the home page.
- When clicked, it triggers **biometric authentication**.

### 2️⃣ Biometric Authentication
- The app checks if the device **supports biometric authentication**.
- If the user **successfully authenticates**, they can access the **Profile Page**.

### 3️⃣ Profile Page UI
- Uses a **CircleAvatar** for the profile image with a **shadow effect**.
- Displays the user's **name and email** in a structured, modern layout.
- Includes an **"Edit Profile" button** for future enhancements.

---

## 📌 Technologies & Packages Used
📌 **Flutter SDK** – for building the UI.  
📌 **Material Design Components** – for styling and structuring the UI.  
📌 **local_auth package** – for **fingerprint authentication**.  
📌 **Dart Programming Language** – for logic and UI development.  

---

## 📌 How to Run the Project?

1️⃣ **Install dependencies**  
```bash
flutter pub get
```  
2️⃣ **Run the application**  
```bash
flutter run
```  
3️⃣ **Test Biometric Authentication**  
- Click on the **Profile Icon**.  
- If prompted, scan your **fingerprint**.  
- If successful, you will be **redirected to the Profile Page**.  

---


