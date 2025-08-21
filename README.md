# Weekly Accountability Webapp

A modern web application for HaiShu and Eric to plan and track their weekly tasks together with a beautiful forest theme.

## Features

- **User Selection**: Choose between HaiShu and Eric
- **Personal Task Planning**: Add multiple individual tasks for the week
- **Collaborative Task**: Plan one task to work on together
- **Weekly Storage**: Save and view previous weeks' plans
- **Responsive Design**: Works on desktop and mobile devices
- **Local Storage**: Data persists between browser sessions

## Getting Started

### Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd daily_accountability
   ```

3. Open `index.html` in your web browser
   - Double-click the file, or
   - Drag and drop it into your browser window, or
   - Right-click and select "Open with" your preferred browser

That's it! The application runs entirely in your browser with no server setup required.

## Usage

### 1. User Selection
- Choose whether you are HaiShu or Eric
- Click the corresponding button to proceed

### 2. Personal Tasks
- Enter the week number for your planning
- Add multiple personal tasks by typing and clicking "Add Task"
- Remove tasks if needed
- Click "Next: Collaborative Task" when done

### 3. Collaborative Task
- Review your personal tasks
- Enter one task you will work on together
- Click "Next: Review & Save" to continue

### 4. Summary & Save
- Review all tasks for the week
- Click "Save Week X" to store your plan
- View previously saved weeks below

## Data Storage

- All data is stored locally in your browser using localStorage
- Data persists between browser sessions
- Each week's plan includes:
  - User name
  - Week number
  - Personal tasks list
  - Collaborative task
  - Timestamp

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - No frameworks required
- **Local Storage** - Browser-based data persistence


## Customization

You can easily customize:
- Colors and styling in the `<style>` section of `index.html`
- User names in the JavaScript code
- Number of personal tasks allowed
- Week numbering system
- Data storage format


## Advantages of This Approach

- **No Installation Required**: Runs directly in any modern browser
- **No Dependencies**: No Node.js, npm, or build tools needed
- **Portable**: Can be easily shared or moved between computers
- **Fast**: No compilation or bundling required
- **Simple**: Single file contains everything needed

## License

This project is open source and available under the MIT License. 
