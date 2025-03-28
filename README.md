# Passop - Password Manager App 🔒

Welcome to **Passop**, a secure and efficient Password Manager built with the MERN (MongoDB, Express.js, React, Node.js) stack. This application provides a user-friendly interface for managing passwords, including storing, viewing, editing, and deleting your sensitive information safely.

## Video Demo 📽️

Watch the demo of Passop on YouTube:
<a href="https://www.youtube.com/watch?v=9BVy_BAk7T0" target="_blank">
    <img src="https://img.youtube.com/vi/9BVy_BAk7T0/0.jpg" width="800" height="300">
</a>


## Features 🚀
- **Add New Passwords**: Securely save passwords for various sites.
- **View Passwords**: Access a list of saved passwords with an option to copy them to the clipboard.
- **Edit Existing Entries**: Update saved credentials easily.
- **Delete Passwords**: Remove any saved password when it’s no longer needed.
- **Toggle Password Visibility**: View or hide passwords for extra security.

## Tech Stack 🛠️
- **Frontend**: React, Tailwind CSS, and Toastify for notifications.
- **Backend**: Node.js, Express.js, MongoDB.
- **Database**: MongoDB Atlas or Local MongoDB.

## Installation 💻

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Passop.git
   cd Passop
   ```

2. **Install Dependencies**
   - For both `client` and `server` directories:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Environment Variables**
   - Create a `.env` file in the `server` directory:
     ```env
     MONGO_URI=your_mongodb_connection_string
     DB_NAME=your_database_name
     ```
     
4. **Run the Application**
   - Start the backend server:
     ```bash
     cd server
     npm start
     ```
   - Start the frontend client:
     ```bash
     cd client
     npm start
     ```

5. **Access the App**
   - Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage
1. **Add Passwords**: Enter site URL, username, and password.
2. **Edit Passwords**: Click on the edit icon to modify an entry.
3. **Delete Passwords**: Use the delete icon to remove an entry.
4. **Copy to Clipboard**: Click on the copy icon to copy passwords.



## Contributions
Feel free to contribute to the project by submitting issues or pull requests.

## License
This project is licensed under the MIT License.
