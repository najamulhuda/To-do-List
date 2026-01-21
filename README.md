# To-Do List App

A clean and intuitive to-do list application built with vanilla JavaScript, HTML, and CSS. Organize your tasks efficiently with a beautiful gradient interface and persistent storage.

## Features

- **Add Tasks** - Quickly add new tasks with a simple input field
- **Mark as Complete** - Click on tasks to mark them as done with a strikethrough effect
- **Delete Tasks** - Remove tasks with a single click on the × button
- **Local Storage** - Your tasks are automatically saved and persist even after closing the browser
- **Responsive Design** - Works seamlessly on desktop and mobile devices
- **Beautiful UI** - Modern gradient background with smooth animations

## Live Demo
https://najamulhuda.github.io/To-do-List/

## Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling with gradient backgrounds and animations
- **JavaScript (ES6)** - Task management and DOM manipulation
- **Local Storage API** - Data persistence
- **Google Fonts** - Poppins font family

## Getting Started

### Prerequisites

No special requirements needed! Just a modern web browser.

### Installation

1. Clone the repository
```bash
git clone https://github.com/najamulhuda/todo-list-app.git
```

2. Navigate to the project directory
```bash
cd todo-list-app
```

3. Open `index.html` in your web browser
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or simply drag and drop the `index.html` file into your browser.

## Project Structure
```
todo-list-app/
│
├── index.html          # Main HTML file
├── style.css           # Styling and layout
├── script.js           # To-do list logic and functionality
├── assets/             # Image assets folder
│   ├── icon.png        # Header icon
│   ├── checked.png     # Checked task icon
│   └── unchecked.png   # Unchecked task icon
└── README.md           # Project documentation
```

## How to Use

1. Open the application in your web browser
2. Type your task in the input field
3. Click the "Add" button or press Enter to add the task
4. Click on a task to mark it as complete (strikethrough effect)
5. Click on the × button to delete a task
6. Your tasks are automatically saved to local storage

## Features in Detail

### Add Tasks
- Enter your task in the input field
- Click "Add" button to add it to the list
- Empty tasks are not allowed (alert notification)

### Complete Tasks
- Click on any task to toggle its completion status
- Completed tasks show a strikethrough and change color
- Visual indicator changes from unchecked to checked icon

### Delete Tasks
- Click the × button on the right side of any task
- Task is immediately removed from the list
- Changes are automatically saved

### Data Persistence
- All tasks are saved to browser's local storage
- Tasks remain even after closing the browser
- Automatically loads saved tasks on page load

## Customization

### Changing Colors

Modify the color scheme in `style.css`:
```css
.container {
    background: linear-gradient(135deg, #153677, #4e085f);  /* Change gradient colors */
}

button {
    background: #ff5945;  /* Change button color */
}

.todo-app h2 {
    color: #002765;  /* Change heading color */
}
```

### Modifying Styles

You can customize:
- Background gradient colors
- Button colors and styles
- Task item appearance
- Border radius and spacing
- Font sizes and weights

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

**Note:** Requires browser support for Local Storage API.

## Future Enhancements

- [ ] Add task categories/tags
- [ ] Implement task priority levels
- [ ] Add due dates for tasks
- [ ] Include task search/filter functionality
- [ ] Add task editing capability
- [ ] Implement drag-and-drop reordering
- [ ] Add dark mode toggle
- [ ] Include task statistics/analytics
- [ ] Add export/import functionality
- [ ] Multi-language support

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Known Issues

- Tasks with only whitespace are accepted (can be improved with better validation)
- No confirmation dialog when deleting tasks

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Your Name**
- GitHub: [@najamulhuda](https://github.com/najamulhuda)

## Acknowledgments

- Inspired by modern to-do list applications
- Font provided by Google Fonts (Poppins)
- Built as a practical project for learning JavaScript and Local Storage

---

⭐ If you found this project helpful, please consider giving it a star!
