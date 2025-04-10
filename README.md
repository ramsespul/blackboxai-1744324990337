
Built by https://www.blackbox.ai

---

```markdown
# Figma-like Interface

## Project Overview
The **Figma-like Interface** is a web application that mimics the user interface of Figma, offering a design canvas where users can interact with various design tools. This project provides essential features for design creation, along with a user login interface.

## Installation
To set up the project locally, clone the repository and open the `index.html` or `login.html` file in your preferred web browser. No additional dependencies are needed to run the basic functionalities.

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/figma-like-interface.git
   ```
2. Navigate to the project directory:
   ```bash
   cd figma-like-interface
   ```
3. Open `index.html` or `login.html` in your browser:
   ```bash
   open index.html  # or open login.html
   ```

## Usage
The application comprises two main HTML files:

- **index.html**: This file contains the design interface where users can create and manipulate design elements on a canvas. It includes a top navigation bar and a sidebar with design tools.
  
- **login.html**: This file provides a user authentication interface where users can log into the application using their email and password. It contains fields for email and password input, along with options to remember the user and links for social media logins.

## Features
- User-friendly design interface resembling Figma.
- Top navigation bar with File, Edit, View, and Help buttons.
- Design tools in a sidebar for easy access (pointer, shapes, text, pen, and images).
- Design properties panel for adjusting dimensions and opacity of elements.
- Login interface with fields for email and password, and social media login options.

## Dependencies
Although the project does not include a `package.json` file, it relies on the following external libraries included in the `<head>` section of both HTML files:

- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Font Awesome**: For iconography.
- **Google Fonts**: For custom typography (Inter and Poppins fonts).

## Project Structure
The project consists of the following files:

```plaintext
/
├── index.html         # Main interface for design creation
└── login.html         # Login page for user authentication
```

Each HTML file is self-contained, linking the necessary styles and scripts for the corresponding interface. The structure is straightforward to facilitate understanding and further development.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to contribute to this project by submitting issues or pull requests. Happy designing!
```