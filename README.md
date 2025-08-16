# Cyberpunk 3D Portfolio
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/OmkarKudalkar23/Portfolio-new)

This is a dynamic and interactive personal portfolio website designed with a futuristic, cyberpunk aesthetic. It leverages modern web technologies like React and Three.js to create an immersive user experience with 3D models, fluid animations, and custom visual effects.

## ✨ Key Features

-   **Interactive 3D Hero Section:** A landing page featuring a `DamagedHelmet` GLTF model that reacts to mouse movement, rendered using `Three.js` with environment mapping and RGB shift post-processing.
-   **WebGL Fluid Cursor:** A mesmerizing smokey and colorful fluid simulation that follows the user's cursor across the entire viewport, built with a custom WebGL implementation.
-   **Smooth Scrolling Experience:** Integrated with `Locomotive Scroll` for a smooth, high-performance scrolling effect throughout the page.
-   **Animated Tech Stack Marquee:** Horizontally scrolling text showcases key technologies with unique color highlights, animated with `Framer Motion`.
-   **3D Tilt-Effect Project Cards:** Project cards that tilt and cast a reactive glow based on mouse position, creating an engaging 3D perspective effect.
-   **Futuristic UI/UX:** A cohesive theme using custom fonts (`Orbitron`, `Urbanist`), neon glows, and glitch effects to enhance the cyberpunk aesthetic.

## 🛠️ Tech Stack

-   **Framework:** React
-   **Build Tool:** Vite
-   **3D & Animation:** Three.js, GSAP (GreenSock Animation Platform), Framer Motion, Locomotive Scroll
-   **Styling:** Tailwind CSS
-   **UI Components:** `lightswind` for components like `SmokeyCursor` and `GlowingCards`.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Ensure you have Node.js and npm (or a compatible package manager) installed on your system.

### Installation & Setup

1.  Clone the repository to your local machine:
    ```sh
    git clone https://github.com/OmkarKudalkar23/Portfolio-new.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd Portfolio-new
    ```
3.  Install the required NPM packages:
    ```sh
    npm install
    ```

### Running the Application

To start the development server, run the following command. The application will be available at `http://localhost:5173`.

```sh
npm run dev
```

## 📜 Available Scripts

In the project directory, you can run:

-   `npm run dev`: Runs the app in development mode with Hot Module Replacement.
-   `npm run build`: Builds the app for production to the `dist` folder.
-   `npm run lint`: Lints the source files using ESLint.
-   `npm run preview`: Serves the production build locally to preview final changes.
