# Birthdays 🎂

A simple web application built with **Flask** and **SQLite** that allows users to store and view birthdays.

## 📌 About the Project

This project was developed as part of **CS50's Introduction to Computer Science**.

The application allows users to:

* View all saved birthdays
* Add a new birthday by entering a name, month, and day
* Store birthday information in a SQLite database
* Validate user input before saving it to the database

## 🛠️ Technologies Used

* **Python**
* **Flask**
* **SQLite**
* **SQL**
* **HTML**
* **CSS**
* **Jinja**


## ⚙️ How It Works

When the user visits the homepage, the application retrieves the birthdays stored in the `birthdays` database and displays them in a table.

Users can also submit a form containing:

* Name
* Birth month
* Birth day

The submitted information is validated and then inserted into the `birthdays` SQLite table.

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/mahya17/birthdays.git
```

Navigate to the project directory:

```bash
cd birthdays
```

Run the Flask application:

```bash
flask run
```

Then open the local URL provided by Flask in your browser.

## 🎯 Learning Objectives

Through this project, I practiced:

* Building web applications with Flask
* Handling `GET` and `POST` requests
* Working with HTML forms
* Receiving and validating user input
* Executing SQL queries with SQLite
* Connecting a Flask application to a database
* Rendering data using Jinja templates

## 📚 Course

This project is based on **CS50's Introduction to Computer Science** by Harvard University.
