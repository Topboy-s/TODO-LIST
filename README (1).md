# My To-Do List

A simple, elegant, and user-friendly web-based to-do list application for managing your daily tasks.

## Features

- **Add Tasks**: Quickly add new tasks using the input field
- **Mark as Complete**: Check off tasks as you complete them
- **Delete Tasks**: Remove tasks you no longer need
- **Task Statistics**: View total and completed task counts at a glance
- **Persistent Storage**: Your tasks are saved locally using browser storage, so they remain even after you close the app
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Beautiful UI**: Modern, clean interface with smooth animations

## How to Use

### Getting Started

1. Open `index.html` in your web browser
2. You'll see the "My To-Do List" application with an input field at the top

### Adding a Task

1. Type your task in the input field that says "Add a new task..."
2. Either click the **Add** button or press **Enter** on your keyboard
3. Your new task will appear in the list below

### Completing a Task

1. Click the **checkbox** next to any task to mark it as complete
2. Completed tasks will appear with a strikethrough and a different style
3. The "Completed" counter at the bottom will update automatically

### Deleting a Task

1. Click the **Delete** button next to any task you want to remove
2. A confirmation dialog will appear - click "OK" to confirm deletion
3. The task will be permanently removed from your list

### Viewing Statistics

At the bottom of the app, you'll see two counters:
- **Total**: Shows the total number of tasks in your list
- **Completed**: Shows how many tasks you've marked as complete

## Technical Details

### Files Included

- `index.html` - The main HTML structure of the application
- `script.js` - JavaScript functionality for adding, deleting, and managing tasks
- `style.css` - Styling and layout for the application
- `scri.js` - Additional script file (utility functions)

### Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling and responsive design
- **Vanilla JavaScript** - Core functionality without dependencies
- **LocalStorage** - Browser-based data persistence

## Browser Compatibility

This application works in all modern browsers that support:
- HTML5
- CSS3
- JavaScript ES6
- LocalStorage

## Data Storage

Your tasks are automatically saved to your browser's local storage. This means:
- ✅ Tasks persist even if you close the browser
- ✅ Tasks are stored locally on your device (not sent to any server)
- ✅ Each browser/device has its own separate task list

## Tips & Tricks

- **Quick Add**: Press Enter to quickly add a task without clicking the Add button
- **Focus**: The input field automatically focuses after adding a task for quick consecutive additions
- **Validation**: You can't add empty tasks - the app will alert you if you try
- **Mobile Friendly**: All features work on touch devices

## Troubleshooting

**Tasks are disappearing:**
- Check if LocalStorage is enabled in your browser
- Try refreshing the page to reload from storage

**Can't add tasks:**
- Make sure you're not trying to add an empty task
- Check browser console for any JavaScript errors

## Future Enhancements

Potential features for future versions:
- Task categories or tags
- Due dates and reminders
- Task priorities
- Dark mode theme
- Export/import functionality

---

Enjoy organizing your tasks! 📝✨
