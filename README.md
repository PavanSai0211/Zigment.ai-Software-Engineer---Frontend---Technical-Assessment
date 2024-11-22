# Zigment.ai-Software-Engineer---Frontend---Technical-Assessment
Creating a dynamic form generator that takes a JSON schema and generates a styled, functional form in real-time. The application should display the JSON editor and the generated form side by side.
Initialize the Project:
npx create-react-app dynamic-form-generator --template typescript
cd dynamic-form-generator
npm install tailwindcss react-hook-form react-monaco-editor ajv
npm install --save-dev jest @testing-library/react playwright @testing-library/jest-dom


Configure Tailwind CSS:
npx tailwindcss init


Update tailwind.config.js and include the src directory:
content: ['./src/**/*.{js,ts,jsx,tsx}'],

Add Tailwind directives to src/index.css:
@tailwind base;
@tailwind components;
@tailwind utilities;

