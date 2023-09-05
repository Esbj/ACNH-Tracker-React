# Animal Crossing: New Horizons tracker

## About

This project is a react implementation of a previous project of mine, written in only TypeScript. The aim of this project is to re-factor it into a react project and finish it to production, and host on Netlify or similar platform.

The program is developed by me, [Alexander Esbjörnsson](https://www.linkedin.com/in/alexander-esbjornsson/)

---

This application is aimed to "completionists" of the game Animal Crossint: New Horizons for the Nintendo Switch.

The app helps keeping track of what critters can be caught in the game at certain points in time, and where to catch them in order to catch every single one.
The data in the app is pulled from from the Animal Crossing wiki: [Nookipedia](https://nookipedia.com/wiki/Main_Page)

---

## Technologies

- React typescript
- SASS
- Vite
- <a href = "https://api.nookipedia.com/" target="_blank">Nookipedia API</a>

## Get started

To run the app start by

1. Clone the repository by typing the following into prefered terminal
   `git clone https://github.com/Esbj/ACNH-Tracker-React.git`
2. Install dependencies with `npm i`
3. Copy the .env_example file and name it .env Paste your own API key where it says `YOUR_API_KEY_HERE`
4. To start the app in development mode run `npm run dev`
5. Open up the site in your browser, default is [localhost:5173](https://localhost:5173/)
