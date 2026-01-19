# Blogify 📝

A modern, beautifully designed blog application built with Node.js, Express, and MongoDB.

## Features

- ✨ User authentication (Sign up / Sign in)
- 📝 Create, read, update, and delete blog posts
- 🎨 Modern mymind-style Pinterest/masonry grid layout
- 🔒 Secure password hashing with bcrypt
- 📱 Responsive design

## Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Templating:** EJS
- **Authentication:** JWT (JSON Web Tokens)

## Project Structure

```
blogify/
├── middleware/     # Authentication middleware
├── models/         # Mongoose models (User, Blog)
├── public/         # Static assets (CSS, images)
├── routes/         # Express routes
├── service/        # JWT authentication service
├── views/          # EJS templates
├── app.js          # Main application entry
├── seed.js         # Database seeder
└── package.json
```

## License

MIT License
