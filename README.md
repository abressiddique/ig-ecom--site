# Project Overview

This project consists of two main parts: a backend server and an admin frontend. The backend is built using Node.js with Express, and the admin frontend is a React application powered by Vite.

---

## Backend

### Technologies Used
- **Node.js**: JavaScript runtime for building the server.
- **Express**: Web framework for Node.js.
- **Mongoose**: MongoDB object modeling for Node.js.
- **Bcrypt**: Library for hashing passwords.
- **Cloudinary**: Cloud-based image and video management.
- **CORS**: Middleware for enabling Cross-Origin Resource Sharing.
- **Dotenv**: Module for loading environment variables.
- **EJS**: Templating engine for generating HTML markup.
- **JSON Web Token (JWT)**: For authentication and authorization.
- **Multer**: Middleware for handling multipart/form-data, primarily used for file uploads.
- **Razorpay**: Payment gateway integration.
- **Stripe**: Payment processing platform.
- **Validator**: Library for string validation and sanitization.

### Scripts
- `start`: Start the server using `node server.js`.
- `server`: Start the server with `nodemon` for development.

### Installation
1. Clone the repository.
2. Navigate to the backend directory:
   ```bash
   cd backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the root of the backend directory and add your environment variables.
5. Start the server:
   ```bash
   npm start
   ```
   or for development:
   ```bash
   npm run server
   ```

---

## Admin Frontend

### Technologies Used
- **React**: JavaScript library for building user interfaces.
- **React Router DOM**: For routing in the React application.
- **Axios**: Promise-based HTTP client for making API requests.
- **React Toastify**: For displaying toast notifications.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Vite**: Build tool and development server.

### Scripts
- `dev`: Start the development server.
- `build`: Build the project for production.
- `lint`: Run ESLint to check for code issues.
- `preview`: Preview the production build locally.

### Installation
1. Navigate to the admin directory:
   ```bash
   cd admin
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

---

## Environment Variables

Both the backend and admin frontend require certain environment variables to be set. Make sure to create a `.env` file in the respective directories and include the necessary variables.

### Backend `.env` Example
```plaintext
PORT=5000
MONGO_URI=mongodb://localhost:27017/yourdatabase
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### Admin `.env` Example
```plaintext
VITE_API_BASE_URL=http://localhost:5000
```

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to the branch.
4. Submit a pull request.

---

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for more details.

---

## Acknowledgments

- Thanks to all the open-source projects and libraries used in this project.
- Special thanks to the contributors and maintainers of the libraries and frameworks used.

---

