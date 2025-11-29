# 🎯 AngularHangman

* 🎮 A simple yet polished implementation of the classic Hangman game using **Angular**.  
* (ES) Una simple pero pulida implementación del clásico juego Hangman usando **Angular**.

<br>

* 🛠️ A full rewrite of my earlier [Redux Hangman](https://github.com/codenamecoffee/redux-hangman) project made in React + Redux Toolkit.
* (ES) Una reescritura completa de mi projecto previo [Redux Hangman](https://github.com/codenamecoffee/redux-hangman) hecho con React + Redux Toolkit.

<br>

## 🧠 Description / Descripción

**EN**  
This project was developed as a challenge to refactor a previous React app into Angular. I wanted to better understand how Angular manages state, components, and services — and compare it to React’s more functional and flexible approach.

**ES**  
Este proyecto fue desarrollado como un desafío personal para refactorizar una aplicación previa hecha en React. El objetivo fue entender mejor cómo Angular maneja el estado, los componentes y los servicios, y compararlo con el enfoque más funcional de React.

<br>


## 📦 Tech Stack / Tecnologías

- ✅ Angular CLI
- ✅ Angular Components
- ✅ Angular Services (for state and theme)  
- ✅ TypeScript
- ✅ CSS3
- ✅ JSON word list
- ✅ GitHub Pages Deployment

<br>

## 📸 Demo

| Feature         | Demo                                  |
|-----------------|---------------------------------------|
| **Gameplay**     | ![](./demo1.gif)                      |
| **Dark Mode**    | ![](./demo2.gif)                      |

<br>

## 🚀 Getting Started

Before running the project locally, make sure to restore all dependencies and start the development server:

1. **Install dependencies:**  
   Run the following command in your project directory to install all required packages:
   ```
   npm install
   ```

2. **Start the local server:**  
   Use Angular CLI to launch the app locally:
   ```
   ng serve
   ```

The application will be available at [http://localhost:4200](http://localhost:4200) by default.

<br>

## 🌍 Deploying to GitHub Pages

To deploy this Angular project to GitHub Pages:

1. **Build the project for production:**
   ```
   ng build --base-href "https://<YOUR_GITHUB_USERNAME>.github.io/<REPO_NAME>/"
   ```
   Replace `<YOUR_GITHUB_USERNAME>` and `<REPO_NAME>` with your actual GitHub username and repository name.

2. **Deploy the correct output folder:**
   If your build output is in `dist/<project-name>/browser`, run:
   ```
   npx angular-cli-ghpages --dir=dist/<project-name>/browser
   ```
   Make sure to use the actual folder name generated in `dist/`.

3. **Configure GitHub Pages:**
   - Go to your repository settings on GitHub.
   - In the "Pages" section, set the source to the `gh-pages` branch and root (`/`).

Your site will be available at:
```
https://<YOUR_GITHUB_USERNAME>.github.io/<REPO_NAME>/
```

**Note:**  
If you change the repository name, update the `--base-href` and redeploy.

<br>

## 🧩 Features / Características

> 🎨 Light and Dark theme toggle using a global service.  
> (ES) Modo claro/oscuro usando un servicio global.

<br>

> 🧠 Random word selection from a local JSON list.  
> (ES) Selección aleatoria de una palabra desde una lista local en formato JSON.

<br>

>🎹 On-screen keyboard with hover effects and disabled keys after selection.  
>(ES) Teclado virtual en pantalla con efectos visuales al posicionarse sobre él y teclas deshabilitadas después de ser seleccionadas.

<br>

>👀 Keyboard physical key support.  
>(ES) Soporte para jugar con el teclado físico. 

<br>

>📱 Responsive layout.  
>(ES) Diseño responsive. 

<br>

>🧩 Clean modular architecture using Angular CLI and services.  
>(ES) Arquitectura limpia y nmodular usando Angular CLI y servicios.

<br>

>🔄 Game restarts on pressing `Enter` or refreshing the page.  
>(ES) Se puede presionar `Enter` o recargando la página.

<br>

## 💡 Future Improvements / Posibles mejoras

* 🧑‍💼 User profiles and persistent score tracking.
* (ES) Perfiles de usuario y seguimiento de puntuaciones persistentes.

<br>

* 📊 Leaderboard with top winning streaks.
* (ES) Tabla con las rachas ganadoras más importantes.

<br>

* 🌐 Multilingual support.
* (ES) Soporte multilenguaje.

<br>

* 💾 `LocalStorage` to track game history.
* (ES) Uso de `LocalStorage` para rastrear el historial del juego.

<br>

## 🙏 Credits / Créditos

The original game logic idea was inspired by Web Dev Simplified's React project.
The Redux version and this Angular port were fully developed and adapted by me.

<br>

## ✨ Final Thoughts & Learning / Reflexión final y aprendizaje

(EN) Refactoring this project into Angular helped me better appreciate its architecture and principles. Its emphasis on components as classes, strong typing, and dependency injection reminded me of backend development in .NET.

<br>

(ES) Refactorizar este proyecto con Angular me ayudó a comprender mejor su arquitectura. El uso de clases, tipado fuerte y la inyección de dependencias me recordaron al desarrollo backend con .NET.

<br>

👨‍💻 Made with patience, curiosity, and a cup of coffee. ☕
> Created by Federico González Lage
