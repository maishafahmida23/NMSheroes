# 🔷 NMSHeroes

# 📱 Project Type:
An Android application designed using Java and the XML layout system in Android Studio.

# 🎯 Purpose / Objective:
The purpose of NMSHeroes is to provide a quick-access emergency response app, featuring:

User authentication (Login & Sign Up)

Emergency dashboard with critical functionalities

Access to emergency contacts and helpline information

This could be targeted at users who need quick SOS or emergency access in critical situations.

# 📁 App Structure
🔹 Main Components:
MainActivity (Login Page)

Signup (User Registration)

Dashboard (Main User Panel)

Contacts (Emergency Contacts View)

🔹 Main Features
1. Login Screen – MainActivity
Consists of username and password input fields.

Two buttons:

Login → Opens the Dashboard directly.

Sign In → Navigates to the Signup screen.

Currently, login doesn’t perform real validation — this can be added later.

2. Signup Screen – signup
Collects user information:

First name, Last name, Username, Password

Clicking “Sign Up” takes the user to the Dashboard.

Back button icon is present but not yet functional.

3. Dashboard – dashboard
Main functionality panel post-login/signup.

Three primary buttons:

SOS! (Visually emphasized; actual functionality not coded yet — potential feature: trigger SMS or call)

Emergency Contacts → Opens contacts screen.

Helpline numbers (No action coded yet — can later lead to a helpline list or dialer).

4. Contacts – contacts
Displays a title: “Your Emergency Contacts”.

Background image applied for design.

Currently static — no actual list of contacts yet.

# 🎨 UI Design:
Uses RelativeLayouts and hardcoded margins.

ImageView as background for all screens (@drawable/faded).

Color-coded buttons and text views for readability.

Consistent font style (serif) and text coloring.

# 🎯 Key Takeaways for Interview:
🔸 Project Goals
"This app is designed as a personal safety and emergency contact tool. The idea is to help users access emergency contacts and SOS services quickly."

🔸 Technologies Used
Java (Android)

XML (UI layout)

Intent-based navigation between activities

Android Resources (colors, drawables, background image)

🔸 Limitations (Mentioning this shows awareness and planning)
No real login/signup validation (no database or authentication logic)

SOS button and helpline button don’t have functionalities

Contacts list is static; not dynamic or stored

🔸 Future Enhancements You Can Mention:
Firebase authentication for login/signup

Saving user data in SQLite or Firebase Realtime Database

Actual SOS functionality (send SMS, call emergency)

Dynamically load emergency contacts

Add helpline database and auto-call or copy-to-clipboard

