# Contact Form with JavaScript Validation

This is a simple contact form built using HTML, CSS, and JavaScript. It includes client-side validation to ensure users fill out the form correctly before submitting.

## 🚀 Features

- Input fields for Name, Email, and Message
- Real-time validation on form submit
- Email format checked using regular expressions
- Error messages shown below each field
- Success message on valid submission (no actual message is sent)

## 🛠 Tools Used

- HTML
- CSS
- JavaScript
- VS Code (Editor)
- Chrome (Browser)

## 📋 How to Use

1. Open `contact-form.html` in your browser.
2. Fill out the form fields:
   - Name (required)
   - Email (must be in correct format like `example@mail.com`)
   - Message (required)
3. Click "Submit".
4. If the input is valid, a success message will appear.
5. If there are any errors, messages will appear under the corresponding fields.

## ✅ Validation Rules

- Name: Cannot be empty
- Email: Must match standard email format (example@example.com)
- Message: Cannot be empty

## 📁 Files

- `contact-form.html`: Main file containing HTML, CSS, and JavaScript

## 🔍 Example Email Regex

```js
/^[a-zA-Z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$/i
