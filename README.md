# 📝 TODO List Application

A simple, efficient To Do List application built with Node.js and Express that allows users to add and complete tasks on a single page with real-time updates.

## 🚀 Features

- **Add Tasks**: Create new tasks with a simple input form
- **Mark Complete**: Mark tasks as completed with a single click
- **Task Management**: Separate arrays for new and completed tasks
- **Real-time Updates**: Dynamic page updates without refresh
- **Clean Interface**: Simple and intuitive user experience
- **Persistent Session**: Tasks remain during the session

## 🛠️ Technologies Used

- **Node.js**: Server-side JavaScript runtime
- **Express.js**: Web application framework
- **EJS**: Embedded JavaScript templating engine for dynamic HTML
- **Body-parser**: Middleware for parsing incoming request bodies
- **HTML/CSS**: Frontend markup and styling

## 📋 Prerequisites

Before running this application, make sure you have:

- **Node.js** (v12 or higher) installed on your system
- **npm** (Node Package Manager) installed

## 🔧 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shreyasvp26/TODO-List.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd TODO-List
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start the server**:
   ```bash
   node index.js
   ```

5. **Open your browser**:
   Navigate to `http://localhost:3000/` to view the application

## 📂 Project Structure

```
TODO-List/
│
├── index.js          # Main server file
├── package.json      # Project dependencies and scripts
├── views/            # EJS templates
│   └── index.ejs     # Main page template
├── public/           # Static files (CSS, JS, images)
│   └── styles.css    # Application styling
└── README.md         # Project documentation
```

## 🎯 How It Works

1. **Task Creation**: Users enter a task in the input field and submit
2. **Server Processing**: Express server receives the POST request via body-parser
3. **Array Management**: New tasks are stored in the `newTasks` array
4. **Template Rendering**: EJS renders the updated page with new tasks
5. **Task Completion**: Users can mark tasks as complete, moving them to `completedTasks` array
6. **Dynamic Updates**: The page displays both active and completed tasks separately

## 🔧 Technical Implementation

### Backend (Node.js + Express)
- Express server handles GET and POST requests
- Body-parser middleware extracts form data
- Arrays store task data during session
- EJS templating engine renders dynamic content

### Frontend (HTML + EJS)
- Simple form for task input
- Dynamic task list rendering
- Separate sections for new and completed tasks
- Clean, responsive design

## 🚀 Usage

1. **Adding a Task**:
   - Enter your task in the input field
   - Click "Add Task" or press Enter
   - Task appears in the "New Tasks" section

2. **Completing a Task**:
   - Click the checkbox or "Complete" button next to a task
   - Task moves to the "Completed Tasks" section

3. **Viewing Tasks**:
   - New tasks appear at the top
   - Completed tasks are shown separately below

## 🎨 Customization

You can easily customize the application by:

- **Styling**: Modify `public/styles.css` for different themes
- **Templates**: Edit `views/index.ejs` for layout changes
- **Features**: Add database integration for persistent storage
- **Functionality**: Implement task editing, deletion, or categories

## 🔮 Future Enhancements

- **Database Integration**: Add MongoDB/PostgreSQL for persistent storage
- **User Authentication**: Multi-user support with login system
- **Task Categories**: Organize tasks by categories or priorities
- **Due Dates**: Add deadline functionality with reminders
- **Search & Filter**: Find tasks quickly with search functionality
- **Mobile Responsive**: Optimize for mobile devices
- **API Endpoints**: Create RESTful API for mobile app integration

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Shreyas VP**
- GitHub: [@shreyasvp26](https://github.com/shreyasvp26)
- Email: shreyasvp2605@gmail.com

---

⭐ **If you found this project helpful, please give it a star!** ⭐
