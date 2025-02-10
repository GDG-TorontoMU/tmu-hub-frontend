# TMU Hub Frontend

Welcome to the TMU Hub Frontend repository—a student-friendly project built with Next.js and React. This project is designed to help students learn modern web development by working with server-side rendering, static site generation, and React components.

## Why This Project?

This repository provides a hands-on way for students to:
- Learn the fundamentals of Next.js and React.
- Understand modern web development practices.
- Collaborate and contribute in a real-world development environment.

## Key Features
- **Next.js Framework:** Experience server-side rendering (SSR) and static site generation (SSG) for improved performance.
- **File-based Routing:** Discover automatic route creation through the file system in the `pages/` directory.
- **Responsive Design:** Learn how to build apps that perform well on both desktop and mobile devices.
- **Dynamic Components:** Work with reusable React components to build interactive and modular interfaces.
- **Built-in API Routes:** Explore how to create seamless API endpoints alongside your pages.
- **Performance Optimization:** Understand techniques like automatic code splitting and image optimization.
- **Testing:** Get started with unit and integration tests using Jest and React Testing Library.

## Tech Stack
- **Next.js** – A powerful React framework.
- **React** – For creating dynamic user interfaces.
- **Sass/CSS Modules** – Modular styling for components.
- **Jest & React Testing Library** – Testing tools to ensure your code works as expected.

## Getting Started

### Prerequisites
- **Node.js** (v14 or later recommended)
- **npm** or **yarn**
- Basic understanding of JavaScript (ES6+) and React

### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-org/tmu-hub-frontend.git
    cd tmu-hub-frontend
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```
    Or, if you prefer yarn:
    ```bash
    yarn install
    ```

3. **Set Up Environment Variables:**
    Create a `.env.local` file in the root directory to configure your environment. For example:
    ```env
    NEXT_PUBLIC_API_URL=http://localhost:5000
    ```

4. **Run the Application:**
    ```bash
    npm run dev
    ```
    Your app will start at [http://localhost:3000](http://localhost:3000).

### Building for Production
To make a production build, run:
```bash
npm run build
npm start
```

### Running Tests
To run tests:
```bash
npm test
```

## Project Structure
```
tmu-hub-frontend/
├── public/                # Static assets (images, fonts, etc.)
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Next.js pages for routing (e.g., index.js, about.js)
│   ├── styles/            # Global styles and theming
│   ├── utils/             # Utility functions and custom hooks
│   └── api/               # Client-side API utilities
├── .env.local             # Environment-specific settings (untracked)
├── next.config.js         # Next.js config file
├── package.json           # Project scripts and dependencies
└── README.md              # Project overview
```

## How to Contribute

Students and beginner developers are encouraged to contribute! Follow these steps:
- Check our [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.
- Create feature branches and submit pull requests.
- Join discussions and help improve the codebase.

## Code of Conduct
All contributors should follow our [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) to ensure a respectful and inclusive environment.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

Happy coding and learning!
