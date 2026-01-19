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

## Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or Atlas)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blogify.git
   cd blogify
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory:
   ```env
   PORT=8352
   MONGO_URL=mongodb://127.0.0.1:27017/blogify
   ```

4. (Optional) Seed the database with sample data:
   ```bash
   node seed.js
   ```

5. Start the application:
   ```bash
   npm start
   ```

6. Open your browser and navigate to `http://localhost:8352`

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
