# TrustID: Blockchain-Powered Digital Identity Verification

TrustID is a blockchain-powered digital identity verification system that ensures secure, tamper-proof, and verifiable credentials. Built on **Hyperledger Indy** and **PostgreSQL**, TrustID allows users to manage and share their credentials (e.g., National ID, Passports, Degrees) with organizations in a privacy-preserving, decentralized way.

---

## 📌 Our Mission
To provide a trustworthy, efficient, and privacy-centric digital identity system for seamless verification across industries like **finance, healthcare, and education**.

---

## 🔹 Key Features
- ✅ **Decentralized Identifiers (DIDs)** for secure user authentication.
- ✅ **Verifiable Credentials** stored on blockchain for authenticity.
- ✅ **Automated Data Extraction** using OCR/AI for easy document verification.
- ✅ **Revocation Registry** to track and prevent fraudulent credentials.
- ✅ **Seamless Integration** for organizations to verify credentials in real-time.

---

## 📊 Project Presentation

[➡️ Click here to view the Google Slides](https://docs.google.com/presentation/d/1P1hOViR7TNffz5H2b4t8dL0hz_HxIsuIRW3yM1SCKPs/edit#slide=id.g3446bf115aa_0_15)



# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
```




Here's a cleaner and more structured version of your README with improved clarity and formatting:  

```markdown
# ⚡ React + TypeScript + Vite Template

This template provides a minimal setup for developing a **React** application with **TypeScript** using **Vite**. It includes **Hot Module Replacement (HMR)** and basic **ESLint rules** for code quality.

## 🚀 Features

- ⚡ **Fast development** with Vite  
- 🔄 **Hot Module Replacement (HMR)** for instant updates  
- ✅ **ESLint configuration** for cleaner, more maintainable code  
- 🔥 **Choice of Babel or SWC** for Fast Refresh  

## 🛠 Plugins

Currently, two official plugins are available for React Fast Refresh:

- **[@vitejs/plugin-react](https://www.npmjs.com/package/@vitejs/plugin-react)** → Uses Babel  
- **[@vitejs/plugin-react-swc](https://www.npmjs.com/package/@vitejs/plugin-react-swc)** → Uses SWC  

## 🔍 Expanding the ESLint Configuration

For production applications, consider enabling **type-aware lint rules** for better TypeScript support:

```ts
export default tseslint.config({
  extends: [
    // Recommended configuration with type checking
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, enable stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
});
```

### 🧩 Additional React-Specific Lint Rules

For enhanced React linting, install **eslint-plugin-react-x** and **eslint-plugin-react-dom**:

```sh
npm install eslint-plugin-react-x eslint-plugin-react-dom --save-dev
```

Then, update your `eslint.config.js`:

```ts
import reactX from 'eslint-plugin-react-x';
import reactDom from 'eslint-plugin-react-dom';

export default tseslint.config({
  plugins: {
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // Enable recommended TypeScript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
});
```

## 📦 Getting Started

1. **Clone the repository**  
   ```sh
   git clone <repo-url>
   cd <project-name>
   ```

2. **Install dependencies**  
   ```sh
   npm install
   ```

3. **Start the development server**  
   ```sh
   npm run dev
   ```

4. **Build for production**  
   ```sh
   npm run build
   ```

## 📜 License

This project is licensed under the **MIT License**.

---

🎉 **Happy coding with React, TypeScript, and Vite!** 🚀
```

### 🔹 Key Improvements:
1. **Better Formatting**: Uses headings (`##`, `###`) and icons for clarity.  
2. **Structured Sections**: Divided into features, plugins, ESLint configuration, setup, and licensing.  
3. **Step-by-Step Setup**: Added instructions for getting started.  
4. **Code Blocks**: Improved readability with syntax highlighting.  

This makes the README **more professional, readable, and user-friendly**. 🚀

