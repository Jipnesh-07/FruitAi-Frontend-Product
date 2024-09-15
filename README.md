# FruitAI - Frontend

**FruitAI** is a health management product designed to provide users with various services, including a chatbot to get information on fruits, a language translator, FAQs, and an about section. This is the **Frontend** component of the FruitAI Fullstack assignment, built with **React**.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [Pages Overview](#pages-overview)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project involves designing and developing the frontend interface for the FruitAI product. The frontend is built using React, with mobile-friendly UI/UX design, closely following the provided Figma design. Users can navigate between different sections like the chatbot for fruit information, a translator, FAQs with basic CRUD functionality, and an about page.

## Features

- **Login Page:** A simple login interface using dummy credentials. Successful login redirects users to the homepage.
- **Homepage:** Displays all four services (Chatbot, Translator, FAQs, About page) and navigates to respective pages.
- **Chatbot:** Provides a list of fruits in card format, each containing individual details that can be viewed upon clicking.
- **Translator:** Translates input text into regional languages.
- **FAQs Page:** Displays a list of FAQs with basic CRUD functionality to create, update, and delete FAQs related to fruits.
- **About Page:** General information about the FruitAI product.

## Technologies Used

- **React** - Main frontend framework.
- **CSS** - For styling the application and ensuring mobile responsiveness.
- **React Router** - For navigation between different pages.
- **Axios or Fetch API** - To interact with the backend API.

## Setup Instructions

### Prerequisites
Before you begin, ensure you have the following installed:
- Node.js (>=14.x.x)
- NPM or Yarn

### Installation Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/Jipnesh-07/FruitAi-Frontend-Product.git
   cd FruitAi-Frontend-Product
   ```

2. **Install Dependencies**
   Using npm:
   ```bash
   npm install
   ```
   Or using yarn:
   ```bash
   yarn install
   ```

3. **Start the Application**
   ```bash
   npm start
   ```
   The app will be accessible at `http://localhost:3000`.

## Project Structure

```
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── About.js
│   │   └── FAQ.js
│   │   └── Translator.js
│   │   └── Home.js
│   │   └── Login.js
│   │   └── Chatbot.js
│   │   └── About.css
│   │   └── FAQ.css
│   │   └── Translator.css
│   │   └── Home.css
│   │   └── Login.css
│   │   └── Chatbot.css
│   └── App.js
│   └── index.js
├── package.json
└── README.md
```

- `components/`: Contains all the individual components and corresponding CSS files for each component.
- `App.js`: Main application routing and layout setup.
- `index.js`: Entry point of the app.

## Pages Overview

- **Login Page:** Simple form interface for logging in with dummy credentials.
- **Home Page:** Displays the four main services and navigates to the corresponding pages.
- **Chatbot Page:** Displays a list of fruits as cards, and individual fruit details upon selection.
- **Translator Page:** Provides input to translate text into regional languages.
- **FAQ Page:** Allows users to view, create, update, and delete FAQs related to fruits.
- **About Page:** Provides information about FruitAI.

## Future Enhancements

- **Authentication:** Implement real authentication using JWT tokens.
- **Multilingual Support:** Enhance the translator functionality to support more languages and regional dialects.
- **Responsive Design:** Improve mobile responsiveness for smaller screen devices.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests if you'd like to contribute to the project.

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
