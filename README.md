![logo](https://github.com/user-attachments/assets/a8a04711-cfa8-4a40-a346-4d033f8ee4b4)


# LearnWisely - Innovative Learning with AI

**LearnWisely** is an interactive educational platform designed to revolutionize learning using AI-driven decision-making and immersive experiences. It aims to engage users by blending real-time choices, puzzles, and 3D storytelling to make learning both fun and effective.

## Table of Contents
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Challenges Faced](#challenges-faced)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Key Features
- **Interactive Storytelling**: Engage with educational content through real-time decision-making and dynamic storylines.
- **3D Learning Environments**: Explore immersive 3D game experiences that teach complex concepts in an interactive manner.
- **Puzzle Games**: Solve challenging puzzles to reinforce learning, making the process enjoyable and memorable.
- **Personalized Learning**: Tailored educational paths powered by AI to meet individual learning needs.
- **BIS Standards Integration**: Optionally includes modules to teach Indian Standards through gamified content.

## Project Structure
The platform is built using **React.js**, **Node.js**, and **Three.js**, with a focus on responsiveness, scalability, and seamless user interaction. Below is a summary of the core files and functionalities:

### Main Files
- `App.js`: The core file that manages the routes and page rendering. It includes:
  - Home page
  - 2D and 3D game experiences
  - Dark mode toggle functionality
  - Game settings and login page management

### Routes
- `/`: Home page with dark mode support.
- `/login`: Login page with dark mode support.
- `/rogue`: A 2D experience for puzzle-based learning.
  - `/rogue/new-game`: Start a new 2D game.
  - `/rogue/settings`: Modify settings for the 2D experience.
- `/3d`: Experience a fully immersive 3D learning environment.

## Technologies Used
- **React.js**: Frontend framework for building a dynamic and responsive user interface.
- **Node.js**: Backend runtime environment for managing API requests and game logic.
- **MongoDB**: NoSQL database for storing user data and game progress.
- **Three.js**: 3D rendering library for creating interactive visual experiences.
- **Tailwind CSS**: Utility-first CSS framework for custom and responsive UI design.
- **Local LLM**: AI-driven decision-making and personalization without external dependencies.
- **Framer Motion**: Smooth animations and transitions for enhanced user experience.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/learnwisely.git
   ```
2. Navigate to the project directory:
   ```bash
   cd learnwisely
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Usage
- Visit the home page to explore the various game experiences.
- Switch between 2D and 3D environments, each offering different interactive learning opportunities.
- Log in to save your progress and access personalized content.
- Adjust settings like dark mode and game preferences.

## Challenges Faced
One challenge was integrating a **local LLM** for AI-driven decision-making while ensuring smooth performance across various devices. Additionally, optimizing the 3D elements using **Three.js** posed challenges in maintaining visual quality without sacrificing performance.

## Contributing
We welcome contributions to LearnWisely! If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

Please make sure to update tests as appropriate and adhere to the [Contributor Covenant](https://www.contributor-covenant.org/) code of conduct.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any inquiries or contributions, please contact:
- **Govind Dubey**: govindd.it.22@nitj.ac.in

Project Link: [https://github.com/MrGovindDubey/LearnWisely/](https://github.com/MrGovindDubey/LearnWisely/)
