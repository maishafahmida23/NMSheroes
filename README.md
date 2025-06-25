# 🚨 NMSHeroes – Emergency Assistance App for Women

**NMSHeroes** is an Android-based emergency assistance application that provides quick access to emergency contacts, SOS alerts, and secure user login and signup functionality. Built using **Java** and **XML**, it is designed with a clean and responsive UI, ensuring user-friendly interaction during urgent situations.

---

## 📱 Features

### 🔐 **User Authentication**

* **Login screen** with fields for username and password.
* **Signup screen** collecting first name, last name, username, and password.
* Navigation between login and signup activities.

### 🧭 **Dashboard**

* Prominent **SOS button** for emergency alerts.
* Quick access to:

  * **Emergency Contacts**
  * **Helpline Numbers**

### 📇 **Contacts Screen**

* Placeholder view showing emergency contact section.

---

## 🛠 Tech Stack

| Component  | Technology        |
| ---------- | ----------------- |
| Language   | Java              |
| UI Layouts | XML               |
| Platform   | Android (API 21+) |
| IDE        | Android Studio    |

---

## 📂 Project Structure

```plaintext
com.example.nmsheroes/
├── MainActivity.java          # Login screen logic
├── signup.java                # Signup screen logic
├── dashboard.java             # Main menu/dashboard after login
├── contacts.java              # Emergency contacts placeholder
└── res/
    └── layout/
        ├── activity_main.xml      # Login screen UI
        ├── activity_signup.xml    # Signup screen UI
        ├── activity_dashboard.xml # Dashboard UI
        └── activity_contacts.xml  # Contacts screen UI
```

---

## 🔄 Navigation Flow

```plaintext
MainActivity (Login)
    ├── [Log In] → dashboard.java
    └── [Sign In] → signup.java
                         └── [Sign Up] → dashboard.java
dashboard.java
    └── [Emergency Contacts] → contacts.java
```

---

## 📝 To-Do / Future Enhancements

* Add **input validation** on login/signup fields.
* Connect app to **Firebase** or SQLite for storing credentials and contacts.
* Implement **SOS functionality** (e.g., send SMS/location to predefined numbers).
* Display and manage **emergency contact list** dynamically.
* Add **helpline numbers screen** with call functionality.

---


