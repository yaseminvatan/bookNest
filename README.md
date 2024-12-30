# BookNest

BookNest is a MERN (MongoDB, Express.js, React.js, Node.js) stack application that allows users to search for books using the Google Books API, save their favorite books, and manage their saved book collection. The application utilizes Apollo Server to implement a GraphQL API, providing a modern and efficient way to interact with the backend.

---

## Features

- **Search for Books**: Search for books by title, author, or keywords using the Google Books API.
- **User Authentication**: Sign up and log in securely using JWT-based authentication.
- **Save Books**: Save favorite books to your account for easy access.
- **View Saved Books**: Manage your saved book collection, view details, and remove books when no longer needed.
- **Responsive Design**: Mobile-friendly and optimized for various screen sizes.

---

## Technologies Used

### Frontend:
- React.js
- Apollo Client
- React-Bootstrap

### Backend:
- Node.js
- Express.js
- Apollo Server
- MongoDB (Atlas)
- Mongoose

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yaseminvatan/booknest.git
   cd booknest
   ```

2. Install dependencies for both the client and server:
   ```bash
   npm install
   cd client && npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following variables:
   ```env
   MONGODB_URI=<your_mongodb_atlas_uri>
   SECRET_KEY=<your_secret_key>
   ```

4. Start the development servers:
   ```bash
   npm run develop
   ```

5. Access the application at `http://localhost:3000`.

---

## Usage

1. **Search for Books**:
   - Use the search bar on the homepage to look for books by entering a title, author, or keyword.

2. **Sign Up/Login**:
   - Create a new account or log in to your existing account to save books.

3. **Save Books**:
   - Click the "Save This Book" button under any search result to save it to your account.

4. **View Saved Books**:
   - Navigate to the "Saved Books" page to view or manage your saved books.

5. **Log Out**:
   - Click "Logout" to securely log out of your account.

---

## Deployment

BookNest is deployed using Render with a MongoDB Atlas database. Access the live application here: [BookNest Live](https://booknest-k414.onrender.com)

---

## References

1. **[Google Books API Documentation](https://developers.google.com/books)**
   - Official documentation for understanding how to interact with the Google Books API.

2. **[JavaScript Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)**
   - Learn how to use the Fetch API for making HTTP requests in JavaScript.

3. **[Error Handling in Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch#checking_that_the_fetch_was_successful)**
   - Best practices for handling errors when using the Fetch API.

4. **[Async/Await in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Promises#async_and_await)**
   - A guide to understanding and using async/await for handling asynchronous code.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or new features.

---

## Contact

For questions or support, please contact Yasemin Vatan at [yvatan0@ivc.edu](mailto:yvatan0@ivc.edu).


