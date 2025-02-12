# Sneh-Chatbot

**Sneh-Chatbot** is a React-based web application designed to provide users with an interactive chat experience. The application features a sidebar for navigation and a chat section for user interaction, aiming to simulate a conversational environment.

## Live Demo

Check out the live version of the project here:  
🔗 **[Sneh-Chatbot](https://sneh-chatbot.netlify.app/)**

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Interactive Chat Interface**: Engage in conversations through a user-friendly chat interface.
- **Sidebar Navigation**: Easily access different sections of the application via the expandable sidebar.
- **Responsive Design**: Optimized for various screen sizes to ensure a seamless user experience.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Sneh-sehrawat/Sneh-Chatbot.git
   cd Sneh-Chatbot
   ```

2. **Install Dependencies**:

   Ensure you have [Node.js](https://nodejs.org/) installed. Then, run:

   ```bash
   npm install
   ```

3. **Start the Development Server**:

   ```bash
   npm run dev
   ```

   The application will be accessible at `http://localhost:3000` or the port specified in your environment.

## Usage

Once the development server is running:

- **Interact with the Chat**: Type messages in the input field at the bottom of the chat section and press the send button to simulate a conversation.
- **Toggle Sidebar**: Click on the hamburger menu icon to expand or collapse the sidebar. In the expanded state, you can start a new chat or view recent prompts.

## Screenshots

Below are some screenshots of the application:
![image](https://github.com/user-attachments/assets/8b464da5-db80-44bb-bc53-4b3f11eb85f5)
![image](https://github.com/user-attachments/assets/9dc1a3df-ad08-4412-a466-59aefe5c7b13)
![image](https://github.com/user-attachments/assets/d4a2e4dd-348e-438a-9d14-a51837bd8c12)

## Project Structure

The project is organized as follows:

```
Sneh-Chatbot/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── assets/
│   │   ├── ai.png
│   │   └── user.jpg
│   ├── components/
│   │   ├── ChatSection/
│   │   │   ├── ChatSection.jsx
│   │   │   └── ChatSection.css
│   │   ├── Darkmode/
│   │   │   ├── Darkmode.jsx
│   │   │   └── Darkmode.css
│   │   └── Sidebar/
│   │       ├── Sidebar.jsx
│   │       └── Sidebar.css
│   ├── context/
│   │   └── UserContext.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .gitignore
├── package.json
├── README.md
└── vite.config.js
```

- **`public/`**: Contains static assets like the `index.html` file.
- **`src/`**: Main source code directory.
  - **`assets/`**: Images and other media assets.
  - **`components/`**: React components organized by feature.
  - **`context/`**: Contains context providers for state management.
  - **`App.jsx`**: Root component.
  - **`index.css`**: Global styles.
  - **`main.jsx`**: Entry point of the application.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.


