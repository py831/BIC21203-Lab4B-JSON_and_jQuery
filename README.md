# BIC21203-Lab4B: JSON_and_jQuery

## Student Information

| Details | Information |
|---|---|
| Student Name | Ho Pei Yi |
| Student ID | AI240161 |
| Course Code | BIC21203 |
| Lab | Lab 4B – JSON_and_jQuery |

---

## 1. Introduction

This repository contains the completed lab assignments for Lab 4B of BIC21203. The objective of this lab is to practice creating valid JSON datasets, fetching and displaying data asynchronously using modern native JavaScript (fetch()), and comparing native DOM manipulations with jQuery methods.

The repository is organised into three sections: Question 1 (Q1), Question 2 (Q2), and Question 3 (Q3). Each question contains its respective source code and output evidence.

## 2. Repository Structure

BIC21203-Lab4A-JavaScript/
│
├── Q1/
│   ├── books.json
│
├── Q2/
│   ├── books.html
│
├── Q3/
│   ├── jquery-dom.html
│
└── README.md

## 3. Question Descriptions

### Question 1 (Q1)

A correctly structured JSON file containing a top-level "books" array with validated properties (title, author, publication Year, and genres), ensuring no trailing commas and proper data typing.

**Output Screenshot:**

<img width="693" height="403" alt="image" src="https://github.com/user-attachments/assets/792137cc-2c6e-4e33-881d-98116847476d" />

# Explanation:
This question involves creating a structured dataset named books.json to store a collection of books. The file uses a top-level “books” array containing individual book objects with strictly validated data types, including strings for titles and authors, a number for publication year, and an array of strings for genres. Formatting rules such as double-quoted property names and the absence of trailing commas are strictly enforced to ensure valid JSON syntax.

### Question 2 (Q2)

Successfully fetches books.json asynchronously and displays:
a. The title of the first book.
b. The author of the second book.
c. The genres of both books grouped by their titles.

**Output Screenshot:**

<img width="839" height="162" alt="image" src="https://github.com/user-attachments/assets/bc7e7216-6a74-4315-ba76-b839b1d1944d" />

# Explanation:
Question 2 requires developing books.html to asynchronously load and display data from books.json using the native JavaScript fetch() API and async/await. By validating the HTTP response and parsing the JSON data, the script extracts specific items, specifically the first book's title, second book's author, genre groupings, and renders them safely onto the webpage using textContent and createElement() while incorporating robust error handling.

### Question 3 (Q3)

Loaded with jQuery 4.0.0 full-build CDN, performing:
a. Text replacement on #myElement using .text().
b. Class addition (.myStyle with coral background and padding) on #myDIV using .addClass().
c. Click event handling on #myButton using .on("click", ...) to trigger an alert popup.

**Output Screenshot:**

<img width="1050" height="143" alt="image" src="https://github.com/user-attachments/assets/9fd2fa29-217d-4404-84d3-5eb1c908efbf" />
<img width="469" height="147" alt="image" src="https://github.com/user-attachments/assets/85f5051b-b508-4e97-b862-006f196dd6e9" />

# Explanation:
This question demonstrates client-side DOM manipulation and event handling using jQuery 4.0.0 imported via an official CDN. It implements jQuery equivalents to native JavaScript operations by utilizing .text() to update element text, .addClass() to apply styling classes like .myStyle, and .on("click", ...) to bind interactive event listeners that trigger alert popups upon button interaction.

## 4. Advantages of native JavaScript
•	Zero Library Overhead: Native JavaScript requires no external library downloads or third-party CDN scripts, resulting in faster initial page load times and lighter bandwidth usage.
•	Direct Browser Execution: It runs natively and directly within the browser engine without any abstraction layers, ensuring optimal performance.
•	No Dependency Management: Projects built entirely on native JavaScript do not need to worry about library version updates, deprecations, or security vulnerabilities tied to external dependencies.
