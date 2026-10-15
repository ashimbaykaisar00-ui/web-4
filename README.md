# Assignment 4 - Forms and Validation

**Name:** Ashimbay Kaisar
**Group:** SE-2540

---

## Overview
This is my submission for Assignment 4 on HTML forms, Bootstrap styling, and validation. I created a contact form and a full registration form with responsive layouts and client-side validation.

---

## What I Did

### Part 1 & Part 2: Contact Form
- Built a basic contact form with `Name`, `Email`, and `Message` fields using `<label>` tags
- Added standard HTML5 validation attributes like `required`, `minlength`, and `maxlength`
- Styled the form using Bootstrap classes (`form-control`, `form-label`, `btn`)
- Added Bootstrap validation visual feedback (`.valid-feedback` and `.invalid-feedback`)

![alt text](<screenshots/contact form.png>)
---

### Part 3: Registration Form
- Created a complete registration form with:
  - First Name & Last Name (placed side-by-side using Bootstrap Grid `row` and `col-md-6`)
  - Email
  - Password and Confirm Password
  - Gender (radio buttons)
  - Hobbies (checkboxes)
  - Country (select dropdown)
  - Submit & Reset buttons
- Added JS script to handle Bootstrap's `.was-validated` class on form submit.
- Added custom JavaScript check to make sure Password and Confirm Password match.
- Handled form reset to clear validation classes.

![alt text](<screenshots/registration form.png>)
![alt text](<screenshots/validation error.png>)

---

## Summary
In this task, I learned how to combine standard HTML forms with Bootstrap 5 components. I also practiced using both browser-native HTML5 validation attributes and custom JS-driven Bootstrap validation states.