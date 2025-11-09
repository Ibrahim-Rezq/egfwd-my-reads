# My Reads

This is a solution for the **EGFWD React Fundamentals Nanodegree** project — *My Reads*. The app allows users to organize and track books they are reading, want to read, or have finished. It communicates with the **Udacity Books API** to retrieve and update book information dynamically.

## Overview

### The Challenge

Users should be able to:

* View books grouped by shelves: **Currently Reading**, **Want to Read**, and **Read**
* Search and add new books using the Udacity Books API
* Move books between shelves dynamically without page reload

### Preview

![My Reads Preview](./egfwd-my-reads.png)

### Links

* **Solution URL:** [GitHub Repository](https://github.com/Ibrahim-Rezq/egfwd-my-reads)
* **Live Demo:** [My Reads Live App](https://ibrahim-rezq.github.io/egfwd-my-reads/)

---

## My Process

### Built With

* **React.js** – Component-based UI
* **React Router** – For page navigation
* **JavaScript (ES6+)**
* **HTML5 & CSS3**
* **Udacity Books API** – For managing book data

### How to Use

1. **Clone this repository:**

   ```bash
   git clone https://github.com/Ibrahim-Rezq/egfwd-my-reads.git
   ```
2. **Navigate into the project folder:**

   ```bash
   cd egfwd-my-reads
   ```
3. **Install dependencies:**

   ```bash
   npm install
   ```
4. **Run the development server:**

   ```bash
   npm start
   ```
5. Open your browser at `http://localhost:3000`

---

### What I Learned

* How to use **controlled components** with state management in React
* Implementing **debounce** to optimize API calls during search
* Structuring data and managing multiple components efficiently
* Understanding how **React Router** manages client-side routing

---

## Project Structure

```
my-reads/
│
├── public/
│   ├── index.html
│   └── favicon.ico
│
├── src/
│   ├── components/
│   │   ├── Book.js
│   │   ├── BookList.js
│   │   └── SearchBooks.js
│   ├── App.js
│   ├── App.css
│   ├── BooksAPI.js
│   └── index.js
│
├── package.json
└── README.md
```

---

## Author

* **Ibrahim Rezq**
  * GitHub – [Ibrahim-Rezq](https://github.com/Ibrahim-Rezq)
