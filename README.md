# Eztrack

npm install \
   prettier \
   eslint \ 
   lint-staged \
   husky \
   eslint-plugin-react-hooks \
   eslint-plugin-react \
   eslint-plugin-prettier \
   eslint-plugin-import \
   eslint-config-prettier

   {
  "name": "@vitest/example-testing-lib-react",
  "private": true,
  "scripts": {
    "build": "tsc && vite build",
    "coverage": "vitest run --coverage",
    "dev": "vite",
    "preview": "vite preview",
    "test": "vitest",
    "test:ui": "vitest --ui"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@testing-library/jest-dom": "^5.16.4",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^14.4.3",
    "@types/react": "^18.0.24",
    "@types/react-dom": "^18.0.8",
    "@vitejs/plugin-react": "latest",
    "@vitest/coverage-v8": "latest",
    "@vitest/ui": "latest",
    "jsdom": "latest",
    "typescript": "^4.8.4",
    "vite": "latest",
    "vitest": "latest"
  },
  "stackblitz": {
    "startCommand": "npm run test:ui"
  }
}