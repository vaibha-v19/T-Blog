

---

# Travelers'

Travelers' is a travel blog application designed to capture, edit, and organize your travel experiences. Built with a modern tech stack using Vite + React on the frontend, and Node.js + Express with MongoDB on the backend, the app provides a seamless and responsive interface for travel enthusiasts to share their adventures.

## Project Demo

### Homepage and Dashboard
![Screenshot 2024-11-18 142601](https://github.com/user-attachments/assets/c51cfbea-aa41-466c-8154-90b7cec78798)

### Travel Story View
![Screenshot 2024-11-18 142616](https://github.com/user-attachments/assets/7e249f3d-8531-4e6b-9e95-80c3ac57436c)

### Login Page
![Screenshot 2024-11-18 142637](https://github.com/user-attachments/assets/4d2cf54f-4b6b-4317-b321-ad680d57ddf4)

### Add Travel Story
![Screenshot 2024-11-18 142714](https://github.com/user-attachments/assets/d2d6c119-9f5f-4a86-812b-fb9f337881ca)



## Features

- **User Authentication**: Secure login and signup.
- **Create & Manage Stories**: Users can upload new travel stories, edit them, or delete any entry.
- **Interactive Dashboard**: View your collection of stories with options to filter by destination or date.
- **Rich Text Editing**: Users can format their stories to include descriptive and engaging content.
- **Date Picker**: An integrated calendar to help sort or schedule stories.
- **Responsive Design**: Optimized for both desktop and mobile users.

## Tech Stack

- **Frontend**: Vite, React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Deployment**: Vercel (Frontend), Render (Backend)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/travelers.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd travelers
   ```
3. **Install dependencies for frontend**:
   ```bash
   cd frontend
   npm install
   ```
4. **Install dependencies for backend**:
   ```bash
   cd ../backend
   npm install
   ```

## Usage

1. **Start the backend server**:
   ```bash
   cd backend
   npm start
   ```
2. **Start the frontend server**:
   ```bash
   cd ../frontend
   npm run dev
   ```
3. Visit `http://localhost:5173` to use the application.

## Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file in the backend:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=your_preferred_port
```

## Deployment

The frontend of the Travelers' app is live at: [Travelers' Blog](https://t-blog-frontend.vercel.app/login)

For backend deployment, follow cloud service guidelines (e.g., AWS, Heroku, DigitalOcean).

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License.

---

