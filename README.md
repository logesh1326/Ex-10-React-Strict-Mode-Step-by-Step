# Ex. 10 React Strict Mode — Step by Step

## Exercise Number
Exercise 10

## Subject
AI1067 - Modern Web Application Development (React JS Lab)

## Student Details
- **Name:** LOGESH S
- **Roll No:** 2305001014
- **Department:** B.Tech CSE
- **College:** IST, NMV University

## Objective
React JS Lab Exercise

## Description
Ex. 10 React Strict Mode — Step by Step 
1. What is React Strict Mode? 
React Strict Mode is a development tool that helps identify potential problems in a React 
application. 
It does not affect the production build. 
It can help detect: 
• Unsafe or problematic code 
• Deprecated APIs 
• Unexpected side effects 
• Components that are not behaving correctly 
 
2. Import StrictMode 
In a typical React application, StrictMode is imported from React: 
import { StrictMode } from "react"; 
 
3. Wrap the Application 
In main.jsx: 
import { StrictMode } from "react"; 
import { createRoot } from "react-dom/client"; 
import App from "./App.jsx"; 
 
createRoot(document.getElementById("root")).render( 
  <StrictMode> 
    <App /> 
  </StrictMode> 
); 
Here: 
<StrictMode> 
  <App /> 
</StrictMode> 
m

## Technologies Used
- React JS
- Vite
- JavaScript (JSX)
- HTML5 / CSS3

## How to Run
```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
npm run dev
```

## Exercise Content
See `exercise.txt` for complete exercise content and source code.
