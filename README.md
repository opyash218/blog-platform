# Blog Writing Platform

A blog writing platform built using Node.js, allowing users to create, edit, and share blog posts with an intuitive interface.

## Features
- User Authentication (Register/Login)
- Create, Edit, and Delete Blog Posts
- Rich Text Editor for Writing Blogs
- Commenting System
- Like & Share Features
- User Profiles

## Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB/MySQL (Choose based on preference)
- **Authentication:** JWT, bcrypt
- **Frontend (Optional):** React.js, EJS, or any preferred framework
- **Deployment:** AWS, Heroku, or Vercel

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/blog-writing-platform.git
   cd blog-writing-platform
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```sh
   PORT=5000
   DB_URI=your_database_url
   JWT_SECRET=your_secret_key
   ```
4. Run the application:
   ```sh
   npm start
   ```
5. Open in browser:
   ```sh
   http://localhost:5000
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | User login |
| POST | /api/blogs | Create a new blog post |
| GET | /api/blogs | Get all blog posts |
| GET | /api/blogs/:id | Get a single blog post |
| PUT | /api/blogs/:id | Edit a blog post |
| DELETE | /api/blogs/:id | Delete a blog post |
| POST | /api/blogs/:id/comment | Add a comment |
| POST | /api/blogs/:id/like | Like a blog post |

## Contributing
You can fix this repository and submit pull requests with improvements.


