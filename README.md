# 📝 Tugas Harian 17 - Cypress Automation (POM OrangeHRM)

Project ini dibuat untuk **Tugas Harian 17 Sanbercode** dengan tujuan mengimplementasikan **automation testing menggunakan format Page Object Model (POM)** pada fitur **Login** di website [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/).

---

## 📂 Struktur Project
cypress/
 ┣ support/
 ┃ ┗ POM/
 ┃    ┗ Login-POM.js
 ┗ e2e/
     ┗ Sanbercode-POM-login/
         ┗ Login-Page.cy.js

🧪 Test Case Login (POM)
✅ Positive Test

LOG_001: Successfully login with valid username and valid password

❌ Negative Tests

LOG_002: Login failed with lowercase username

LOG_003: Login failed with valid username and wrong password

LOG_004: Login failed with invalid username and correct password

LOG_005: Login failed due to swapped username and password fields

LOG_006: Login failed when valid username is entered with @gmail.com

LOG_007: Login failed when password contains @ instead of a

LOG_008: User cannot login with empty credentials

LOG_009: Login failed when valid username is entered but password field is empty

LOG_010: Login failed when username field is empty but password is valid

👤 Author

Ajib Bahauddin
Sanbercode Bootcamp – Tugas Harian 17
Automation Testing with Cypress (Page Object Model)
