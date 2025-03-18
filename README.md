# Notes App

## Description
The Notes App is a simple React application that allows users to create and manage notes efficiently. The app includes an intuitive interface for adding notes with a title and content. It also displays notes dynamically and provides a seamless user experience across different screen sizes.

## Features
- Add new notes with a title and content
- Responsive design for different screen sizes
- Styled using Styled Components
- Empty Notes View when no notes are available

## Technologies Used
- React.js
- Styled Components
- HTML5 & CSS3
- JavaScript (ES6+)

## Setup Instructions
### Prerequisites
Make sure you have the following installed on your system:
- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation Steps
```sh
# Clone the repository
git clone https://github.com/your-username/notes-app.git

# Navigate to the project directory
cd notes-app

# Install dependencies
npm install

# Start the development server
npm start
```

## Folder Structure
```sh
src/
│── components/
│   ├── Notes/
│   │   ├── index.js
│   │   ├── styledComponents.js
│   ├── NoteItem/
│   │   ├── index.js
│   │   ├── styledComponents.js
│── App.js
│── index.js
│── styles.css
```

## Design Specifications
### Colors
```css
Primary: #4c63b6;
Text: #475569, #1e293b;
Background: #ffffff, #cbd5e1;
Border: #d8d8d8, #aab8c8;
```

### Fonts
- `Bree Serif` (For headings)
- `Roboto` (For body text)

## Functionality
1. Initially, the title and note input fields are empty, displaying an Empty Notes View.
2. When a user enters a title and note content and clicks the "Add" button:
   - A new note is added to the list.
   - The note appears dynamically on the UI.
3. Responsive layout ensures a smooth experience across devices.

## Screenshots
![Image](https://github.com/user-attachments/assets/18efac6d-1ae6-46b8-bce6-54e73ccf7d30)

## Deployment
To deploy the app:
```sh
# Build the project
npm run build

# Deploy to GitHub Pages (or other hosting platforms)
```

## License
This project is licensed under the MIT License.

## Author
- **Your Name**
- GitHub: [Your GitHub Profile](https://github.com/your-username)
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

## Contributions
Contributions are welcome! Feel free to open issues and pull requests.

## Acknowledgments
- CCBP for project guidelines
- React Community for support

---
Happy Coding! 🚀

