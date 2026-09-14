# SocialMedia

SocialMedia is a simple social media web application where users can create, view, edit, and delete posts. The project is built using **Node.js, Express.js, EJS, and Bootstrap**.

## Features

* Create new posts
* View all posts
* View individual post details
* Edit existing posts
* Delete posts
* Responsive user interface
* Bootstrap-based design
* RESTful routes
* Server-side rendering using EJS

## Tech Stack

* **Frontend:** HTML, CSS, Bootstrap
* **Backend:** Node.js, Express.js
* **Templating Engine:** EJS
* **Database:** MongoDB
* **ODM:** Mongoose
* **Method Override:** method-override

## Project Structure

```text
SocialMedia/
│
├── models/
│   └── post.js
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── show.ejs
│   └── edit.ejs
│
├── public/
│   └── style.css
│
├── app.js
├── package.json
└── README.md
```

## Routes

| Method | Route             | Description                |
| ------ | ----------------- | -------------------------- |
| GET    | `/posts`          | Display all posts          |
| GET    | `/posts/new`      | Show form to create a post |
| POST   | `/posts`          | Create a new post          |
| GET    | `/posts/:id`      | Display a single post      |
| GET    | `/posts/:id/edit` | Show edit form             |
| PATCH  | `/posts/:id`      | Update a post              |
| DELETE | `/posts/:id`      | Delete a post              |

This project was created as a learning project to practice **Node.js, Express.js, MongoDB, Mongoose, EJS, and RESTful APIs**.
