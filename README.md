# Clickjacking Detection & Prevention Techniques

This project demonstrates multiple techniques to **detect and prevent clickjacking attacks** on web applications using both **server-side** and **client-side** strategies.

> **Live Demo**: [Click to View the App](https://amankumar025.github.io/clickjacking-demo/)

---

## Project Objectives

-  Simulate a vulnerable web application (susceptible to clickjacking)
-  Demonstrate a clickjacking attack using a hidden iframe and overlay
-   Implement protection techniques including:
  - X-Frame-Options header
  - Content Security Policy (CSP)
  - Frame-busting JavaScript
  - Intersection Observer API
-   Log clickjacking detection events for analysis

---

## What is Clickjacking?

> Clickjacking is a web-based attack that tricks users into clicking on elements disguised or hidden behind legitimate UI, often through transparent iframes.

---

## Project Structure

```plaintext
appproject1/
├── index.html                ← Homepage with navigation
├── style.css                 ← Shared styling
├── target/                   ← Vulnerable version
│   └── index.html
├── attacker/                 ← Simulated attack using iframe
│   └── index.html
└── protected/                ← Fully protected version
    └── index.html
```
images
<img width="1911" height="778" alt="Screenshot 2025-07-27 134711" src="https://github.com/user-attachments/assets/5558a874-99b1-41a9-9ad3-f221698034f7" />
<img width="1356" height="685" alt="Screenshot 2025-07-27 134725" src="https://github.com/user-attachments/assets/5c3a56c9-2433-46f8-bc0e-aa1deb6a7b9e" />
<img width="1341" height="663" alt="Screenshot 2025-07-27 134745" src="https://github.com/user-attachments/assets/809fc25f-ce06-4cc8-9aba-f793a68f2752" />
<img width="1494" height="559" alt="Screenshot 2025-07-27 134800" src="https://github.com/user-attachments/assets/fa59db27-4ef7-4ca1-b83f-ebdef0380a7c" />
<img width="1359" height="515" alt="Screenshot 2025-07-27 134829" src="https://github.com/user-attachments/assets/f8f95b94-00bf-46e5-a2d7-1829256d8915" />

# Clone the repo
git clone https://github.com/amankumar025/clickjacking-demo.git
cd appproject1

# Open in VS Code or any editor
# Use Live Server

# Author
Aman Kumar
BTech Student

# Resources
[PortSwigger Web Security Academy - Clickjacking](https://portswigger.net/web-security/clickjacking)

[Auth0 - Clickjacking Attacks and How to Prevent Them](https://auth0.com/blog/preventing-clickjacking-attacks)

[Mozilla Developer Network (MDN) - Content-Security-Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy)

# License
**This project is licensed under the MIT License**


