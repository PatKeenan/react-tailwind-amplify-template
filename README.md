# React - Tailwind - Amplify Starter

```terminal
npx create-react-app my-app --template with-tailwind
```

## Update package.json after intalling the template

```json
{
  "name": "Name-of-your-app", //replace this line with the name of your app
  "version": "0.1.1",
  "private": true,
  "dependencies": {
    "@craco/craco": "^6.1.2",
    "@testing-library/jest-dom": "^5.11.4",
    "@testing-library/react": "^11.1.0",
    "@testing-library/user-event": "^12.1.10",
    "react": "^17.0.2",
    "react-dom": "^17.0.2",
    "react-scripts": "4.0.3",
    "web-vitals": "^1.0.1"
  },
  "scripts": {
    "start": "craco start",
    "build": "craco build",
    "test": "craco test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": ["react-app", "react-app/jest"]
  },
  "browserslist": {
    "production": [">0.2%", "not dead", "not op_mini all"],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  },
  "devDependencies": {
    "autoprefixer": "^9.8.6",
    "postcss": "^7.0.36",
    "tailwindcss": "npm:@tailwindcss/postcss7-compat@^2.1.4"
  }
}
```

## Install Tailwind

```terminal
npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9
```

## Run the app

```terminal
cd your-app/
npm run start
```

## You can find the colors for overriding amplify in the css
