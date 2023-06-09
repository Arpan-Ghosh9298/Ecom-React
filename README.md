# React Project

Welcome to the React project! This README file will guide you on how to run the project locally after downloading the folder from GitHub.

## Prerequisites

Before running the project, ensure that you have the following softwares installed on your local system:

- Node.js (version 10 or above)
- npm (Node Package Manager) or yarn

## Getting Started

To run the React project locally, follow these steps:

1. Clone or download the project folder from GitHub.

2. Open your terminal or command prompt and navigate to the project directory.

3. Install project dependencies by running the following command:

   ```
   npm install
   ```
   
   or if you are using yarn:
   ```
   yarn install
   ```
4. Once the dependencies are installed successfully, start the development server by running the following command:
    ```
    npm start
    ```
   or if you are using yarn:
    ```
    yarn start
    ```
5. Your default browser should automatically open and load the project at http://localhost:3000. If it doesn't, manually open your browser and go to that URL.

6. You should now see the React project up and running locally! Any changes you make to the source code will automatically refresh the page in the browser.

7. Commands to install packages required in this project 
    
   ```
   npm install redux
   npm install react-redux
   npm install axios
   npm install react-router-dom
   ```
8. Semanitc UI link tag
   
   ``` 
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.5.0/semantic.min.css" integrity="sha512-KXol4x3sVoO+8ZsWPFI/r5KBVB/ssCGB5tsv2nVOKwLg33wTFP3fmnXa47FdSVIshVTgsYk/1734xSk9aFIa4A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
   ```
9. API Links
   
   ```
   'https://fakestoreapi.com/products'  for all products
   'https://fakestoreapi.com/products/1' for single product
   ```
10. Add this extension for redux as the third argument in legacy_createStore() in store.js file
   
   ```
   window.__REDUX_DEVTOOLS_EXTENSION__ && window.__REDUX_DEVTOOLS_EXTENSION__() 
   ```
11. Hooks that we used in this project
   
    a. useEffect
    b. useSelector
    c. useDispatch
    d. useParams
   
