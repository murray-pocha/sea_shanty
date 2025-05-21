# Sea Shanty - Semantic HTML Teaching Tool

Ahoy! This Node.js app serves a tutorial-style HTML page styled like a sea shanty, walking users through the basics of semantic HTML. From `<header>`s to `<form>`s, and `<ul>`s to `<table>`s, this project wraps web structure lessons in a lighthearted theme.

---

## What It Does

- Serves a single EJS-based HTML page via Express.js
- Teaches semantic HTML markup:
  - Headers, articles, and sections
  - Lists (`<ul>`, `<li>`)
  - Tables and table structure
  - Forms and input fields
  - HTML classes, IDs, and attributes
- Styled with custom CSS for clarity and fun
- Creative "sea shanty" references used to reinforce learning

---

## Project Structure

| File / Folder            | Purpose |
|--------------------------|---------|
| `server.js`              | Sets up Express server and renders the main page |
| `views/htmlSeaShanty.ejs`| Contains the full tutorial content with semantic HTML examples |
| `public/css/style.css`   | Styling for the EJS-rendered HTML page |
| `package.json`           | Declares dependencies (`express`, `ejs`) |

---

## How to Run

### 1. Install Dependencies

```bash
npm install

2. Start the Server
node server.js


3. View in Browser
Visit: http://localhost:3000