# MyReads

Book tracker from the EGFWD React fundamentals nanodegree. You organize books across three shelves (currently reading, want to read, read) and search for new titles through the Udacity Books API. Moving a book between shelves updates without a page reload, and your shelf assignments survive a refresh.

Live version: [my-react-book-library.vercel.app](https://my-react-book-library.vercel.app)

![MyReads preview](./egfwd-my-reads.png)

## What I was practicing

This is where I worked through the core React patterns: lifting state up, passing callbacks down, controlled components. The search page needed debouncing so it wouldn't hit the API on every keystroke, which was my first taste of a real performance fix rather than a tutorial one.

## Running it

```bash
git clone https://github.com/Ibrahim-Rezq/egfwd-my-reads.git
cd egfwd-my-reads
npm install
npm start
```

Runs on [http://localhost:3000](http://localhost:3000). `npm run build` makes a production build.

## How it's laid out

```
src/
├── components/
│   ├── Book.js          # single book card
│   ├── BookList.js      # one shelf
│   └── SearchBooks.js   # search page
├── BooksAPI.js          # API helpers: getAll, update, search
├── App.js
└── index.js
```

Two routes: `/` shows your shelves, `/search` finds new books.

## Stack

React, React Router, plain CSS. Book data comes from the Udacity Books API.
