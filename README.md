📄 Student Registration Form – README

This project allows a user to register student information using a web form and view all submitted data in a table – **without opening the database manually**.

## 📁 Files Included

* `index.html` – The main form where user enters data
* `insert.php` – Handles the form data and saves it to the database
* `view.php` – Displays all student records in a table

---

## 🛠️ How to Set Up

Follow these steps to make everything work:

### 1. 📥 Copy Files

Paste all three files into this folder on your computer:

```
C:\xampp\htdocs\db
```

Make sure the folder name is `db`.

---

### 2. 🗃️ Create Database and Table

1. Open your browser and go to:
   **[http://localhost/phpmyadmin/](http://localhost/phpmyadmin/)**

2. Create a new database:
   **student\_db**

3. Inside **student\_db**, create a new table:
   **students**

4. Add the following columns to the `students` table:

| Column Name | Type    | Length | Extra                        |
| ----------- | ------- | ------ | ---------------------------- |
| id          | INT     |        | AUTO\_INCREMENT, PRIMARY KEY |
| name        | VARCHAR | 100    |                              |
| email       | VARCHAR | 100    |                              |
| age         | INT     |        |                              |

*(You can change or add more fields based on your form.)*

---

## ▶️ How to Use

1. Open the form in your browser:
   **[http://localhost/db/index.html](http://localhost/db/index.html)**

2. Fill in the form fields (like name, email, age) and click **Register**.

3. The data will be automatically saved into your database (`student_db`, `students` table) using `insert.php`.

4. To view the saved data in a table (without using phpMyAdmin), open:
   **[http://localhost/db/view.php](http://localhost/db/view.php)**

---

## ✅ Requirements

* XAMPP must be installed and running (Apache & MySQL turned ON)
* A web browser (like Chrome, Firefox, etc.)

---

## 💡 Tip

If the form doesn't work, double-check:

* File names and paths
* If Apache & MySQL are running in XAMPP
* Database and table structure

---
