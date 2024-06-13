# Frontend Restaurant

This project is built with React and Vite, utilizing several modern web development tools and libraries.

- **React**: ^18.2.0
- **TypeScript**: ^5.2.2

How to Start Project?

- npm install
- npm run dev

## Hosting

### Why Vercel?

I chose to host this project on Vercel instead of Netlify due to issues with registration and authentication on Netlify. Vercel offers several advantages:

- Easy Integration: Vercel provides seamless integration with GitHub, allowing for automatic deployments on push.
- Fast Builds: Vercel's build process is optimized for speed, providing quick feedback during development.
- Serverless Functions: Vercel supports serverless functions, which can be very useful for building full-stack applications.
  Global CDN: Vercel uses a global CDN to ensure fast load times for users around the world.

![verify](/frontend/assets/netlify1.jpeg)
![authentication](/frontend/assets/netlify2.jpeg)

## Notes:

According to the requirements, the categories section needs to be server-side. I have researched several restaurant APIs, such as those from Dicoding, etc., but I have not found an open API that provides the specific functions or data required by the assignment, like category filtering. Therefore, I have decided to create my own

# If you want to see the backend go checkhout

- [restaurant-backend](https://github.com/nandaglhp/restaurant-backend)

# If you want to see my project using Open API go chechout

- [forum-app](https://github.com/nandaglhp/react-app-forum)
- [notes-app](https://github.com/nandaglhp/react-notes)

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
