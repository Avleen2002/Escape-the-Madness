# 🎭 Escape the Madness

> Solve the puzzles. Keep the lights on. Don't lose your mind.

🏆 **1st Place Winner, Mountain Madness Hackathon**

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?logo=css3&logoColor=white)

## 📖 About

**Escape the Madness** is a virtual escape room experience that keeps players on edge, where time, sanity, and survival are constantly slipping away. The chaotic blend of eerie visuals, unsettling messages, and adrenaline-pumping music was inspired by psychological horror games and real-time puzzle-solving experiences.

Solve puzzles under pressure while the darkness closes in, and escape before it's too late.

## ✨ Features

- 🧩 **Dynamic puzzle mechanics**: think fast, because the clock never stops
- 🧠 **Sanity meter**: drains over time, ramping up tension as it falls
- 💡 **Light switch mechanic**: your only source of safety, so use it wisely
- 🔊 **Fast-paced sound design**: audio that builds urgency and immersion
- 🧟 **Zombies and shadowy figures**: threats that creep closer as you struggle

## 🛠 Built With

| Technology | Purpose |
| --- | --- |
| [React](https://react.dev/) | Component-based UI and real-time game updates |
| [TypeScript](https://www.typescriptlang.org/) | Type-safe game logic and state management |
| [Vite](https://vitejs.dev/) | Fast dev server with HMR and optimized builds |
| CSS | Atmospheric visuals, animations, and effects |

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git

# Move into the project directory
cd <your-repo>

# Install dependencies
npm install

# Start the development server
npm run dev
```

Then open the local URL shown in your terminal (Vite defaults to `http://localhost:5173`).

### Other Scripts

```bash
npm run build     # Type-check and create a production build
npm run preview   # Preview the production build locally
npm run lint      # Run ESLint
```

> 🎧 **Tip:** Play with headphones and the lights off for the full experience.

## 🎮 How to Play

1. Solve each puzzle before time runs out.
2. Keep an eye on your **sanity meter**, because it drops constantly.
3. Use the **light switch** to stay safe from what lurks in the dark.
4. Escape before the zombies and shadows get you, or before madness takes over.

## 🧑‍💻 Development Notes

This project was bootstrapped with the Vite **React + TypeScript** template, which provides a minimal setup with HMR and some ESLint rules. Two official React plugins are available for Fast Refresh:

- [`@vitejs/plugin-react`](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/)
- [`@vitejs/plugin-react-swc`](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/)

<details>
<summary><strong>Expanding the ESLint configuration</strong></summary>

<br>

If you are developing a production application, we recommend enabling type-aware lint rules.

1. Configure the top-level `parserOptions` property:

   ```js
   export default tseslint.config({
     languageOptions: {
       // other options...
       parserOptions: {
         project: ['./tsconfig.node.json', './tsconfig.app.json'],
         tsconfigRootDir: import.meta.dirname,
       },
     },
   })
   ```

2. Replace `tseslint.configs.recommended` with `tseslint.configs.recommendedTypeChecked` or `tseslint.configs.strictTypeChecked`.
3. Optionally add `...tseslint.configs.stylisticTypeChecked`.
4. Install [`eslint-plugin-react`](https://github.com/jsx-eslint/eslint-plugin-react) and update the config:

   ```js
   // eslint.config.js
   import react from 'eslint-plugin-react'

   export default tseslint.config({
     // Set the react version
     settings: { react: { version: '18.3' } },
     plugins: {
       // Add the react plugin
       react,
     },
     rules: {
       // other rules...
       // Enable its recommended rules
       ...react.configs.recommended.rules,
       ...react.configs['jsx-runtime'].rules,
     },
   })
   ```

</details>

## 🧠 What We Learned

- Building game logic in React and TypeScript with smooth, dynamic UI updates
- Managing state so real-time interactions feel seamless
- Designing UX for high-pressure situations, balancing difficulty and engagement
- Integrating audio and visuals to create an immersive horror atmosphere

## 🔥 Challenges We Faced

- **Balancing difficulty:** making puzzles challenging but solvable under time pressure
- **Managing game state:** keeping sanity, puzzles, and threats updating in real time without performance issues
- **Crafting atmosphere:** finding the right mix of visuals, audio, and mechanics to build tension

## 👥 Team

<!-- Replace with your teammates -->
- [Irene](https://github.com/thanhha1210)
- [Aiden](https://github.com/aidandevaal)
- [Nathan](https://github.com/NDNathanRocks)
- [Avleen(Me!)](https://github.com/Avleen2002)

## 🏁 Final Thoughts

This project was an exciting dive into fast-paced puzzle-solving and horror storytelling. We pushed the boundaries of React and TypeScript to create a chaotic, immersive experience, and we hope players feel the thrill, the panic, and the rush of escaping insanity before it's too late.

## 📜 License

This project is licensed under the [MIT License](LICENSE). <!-- Update if you use a different license -->
