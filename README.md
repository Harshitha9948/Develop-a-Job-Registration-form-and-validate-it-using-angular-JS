# 💼 Job Registration Form (AngularJS)

This is a basic job registration form built using **AngularJS**. It demonstrates **form validation**, **input binding**, and **conditional styling** for invalid inputs.

---

## 🧩 Technologies Used

- **AngularJS 1.8.2** (CDN)
- **HTML5 & CSS3**

---

## 🎯 Features

- Validates:
  - Name (required)
  - Email (required, valid format)
  - Phone (10-digit number)
  - Position (dropdown selection)
- Highlights invalid fields using red borders.
- Displays error messages under each field.
- Shows a success message on valid submission.
- Alerts user if the form contains errors.

---

## 🗂️ File

- `job_registration.html`: Main HTML file with embedded AngularJS and styles.

---

## 🚀 How to Run

1. Open `job_registration.html` in a web browser.
2. Fill the form fields.
3. Click **Submit**.
4. If all inputs are valid, a success message will appear.

---

## 🔍 How It Works

- Uses AngularJS directives:
  - `ng-model` to bind data
  - `ng-show` for conditional error/success messages
  - `ng-disabled` to prevent invalid form submission
  - `ng-pattern` for custom regex on phone number
- AngularJS dynamically updates the form state and validation feedback.

---
