# Blog_app

A simple blogging platform built with Node.js, Express, EJS, and MongoDB — allowing users to sign up, log in, and create, view, and manage blog posts.

## 🚀 Features

- ✅ **User Authentication**
  - Sign up and sign in via `services/authentication.js`
  - Passwords securely hashed using bcrypt

- 📝 **Blog Management**
  - Create, read, update, delete blog posts using `routes/blog.js`
  - Blog views built with EJS templates:
    - `home.ejs`, `blog.ejs`, `addBlog.ejs`

- 👤 **User Routes**
  - `routes/user.js` handles user-related routes: `/signup`, `/signin`, `/logout`

- 📁 **File Uploads**
  - Supports image uploads for blogs saved under `public/uploads/`
  - Default placeholder image ( `public/images/default.png` )


