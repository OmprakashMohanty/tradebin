# Project Alpha

A full-stack web application built with React frontend and Express backend.

## 🚀 Features

- **Frontend**: React 19 with Vite for fast development
- **Backend**: Express.js server with MongoDB support
- **Styling**: Tailwind CSS for modern, responsive design
- **Development**: Hot reload and ESLint configuration

## 📁 Project Structure

```
Project_alpha/
├── client/                 # React frontend
│   ├── src/
│   │   ├── App.jsx        # Main application component
│   │   ├── main.jsx       # Application entry point
│   │   └── index.css      # Global styles
│   ├── public/            # Static assets
│   └── package.json       # Frontend dependencies
├── server/                # Express backend
│   ├── index.js          # Server entry point
│   └── package.json      # Backend dependencies
└── README.md             # Project documentation
```

## ️ Technologies Used

### Frontend
- **React 19** - Modern React with latest features
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **ESLint** - Code linting and formatting

### Backend
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database (with Mongoose ODM)
- **CORS** - Cross-origin resource sharing

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Project_alpha
   ```

2. **Install frontend dependencies**
   ```bash
   cd client
   npm install
   ```

3. **Install backend dependencies**
   ```bash
   cd ../server
   npm install
   ```

### Running the Application

#### Development Mode

1. **Start the backend server**
   ```bash
   cd server
   npm start
   ```
   The server will run on `http://localhost:3000`

2. **Start the frontend development server**
   ```bash
   cd client
   npm run dev
   ```
   The frontend will run on `http://localhost:5173`

#### Production Build

1. **Build the frontend**
   ```bash
   cd client
   npm run build
   ```

2. **Start the production server**
   ```bash
   cd server
   npm start
   ```

## 📝 Available Scripts

### Frontend (client/)
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

### Backend (server/)
- `npm start` - Start the server
- `npm test` - Run tests (currently not configured)

##  Configuration

### Environment Variables

Create a `.env` file in the server directory for environment-specific configuration:

```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string
NODE_ENV=development
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Om Prakash**

##  Acknowledgments

- React team for the amazing framework
- Vite team for the fast build tool
- Tailwind CSS team for the utility-first CSS framework
- Express.js team for the web framework

---

**Note**: This is a basic setup. You may want to add more features like authentication, database models, API routes, and additional frontend components based on your specific requirements. 