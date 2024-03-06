# BrainWave

Web application to demonstrate React.js and Tailwind CSS framework.

Deployed Site: [ConnorXCX.github.io/BrainWave](https://ConnorXCX.github.io/BrainWave/)

Commands to Run Locally:

1. `npm install`
2. `npm run dev`

How to Configure GitHub Pages Dependency:

1. Add `base` parameter to `vite.config.js`
2. Add `homepage` parameter to `package.json`
3. Add `predeploy` parameter with `npm run build` under `scripts` in package.json
4. Add `deploy` parameter with `gh-pages -d dist` under `scripts` in package.json
5. `npm install gh-pages --save-dev`

Command to Deploy to GitHub Pages:

1. `npm run deploy`

References:

1. [Build and Deploy a Modern UI/UX Website with React & Tailwind CSS](https://youtu.be/B91wc5dCEBA?si=Kj0j9sjL6MpeWw2E)
