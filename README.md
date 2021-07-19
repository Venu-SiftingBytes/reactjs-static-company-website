## Website 
#### Technology Stack
        I.ReactJS
       II.React Hooks
      III.React Router
       IV.React Icons 
_______________________________________________________________________________________________________________________________________________________________________________
### Steps
#### 1. To install a React app
         $npx create-react-app react-website-one
         $cd react-website-one
         //To open current project in VS Code
         $code .
         
#### 2. Start the development server
         $npm start
         (or)
         $yarn start
         
#### 3. Clean up project
        //Delete all files from src(folder) except three files: index.js, App.js, App.css
        
        //Update Index.js :
        import React from 'react';
        import ReactDOM from 'react-dom';
        import App from './App';       
        ReactDOM.render(  
            <App />,
            document.getElementById('root')
        );
        
       //Update App.js
       import './App.css';
       function App() {
         return (
           <div className="App">
             <h1>Hello World!</h1>
           </div>
         );
       }      
       export default App;
       
       //Update App.css
       * {
           box-sizing: border-box;
           margin: 0;
           padding: 0;
           font-family: 'PT Sans', sans-serif;
       }

#### 4. Create a folder structure for our components
        //Create sub-directories: src/components/pages/
        //Create a file for Navbar in components/Navbar.js
        //Create a file for Navbar in components/Navbar.css
        //Copy images(folder)/*.svg downloaded from GitHub into public(folder)/images/*.svg in VS Code

#### 5. Developing Navbar using: Navbar.js, Navbar.css
        //Pre-requisites: React Router
        $npm install react-router-dom
        (or)
        $yarn add react-router-dom
        //---------------------------------------------
        //Pre-requisites: React Icons
        $npm install react-icons --save
        (or)
        $yarn add react-icons
        //---------------------------------------------
        //components/Navbar.js
        //components/Navbar.css
        //components/Button.js
        //components/Button.css
        //---------------------------------------------
        
