# ThreeJSApp

![Current Version](https://img.shields.io/badge/version-v0.1-blue)
![GitHub contributors](https://img.shields.io/github/contributors/madhur-taneja/README-Template)

Open and view the Project using the `.zip` file provided or at my [GitHub Repository]

The project is also hosted on [Official Site]

## Table of Contents
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
- [Running the App](#running-the-app)
- [Deployment](#deployment)
- [Authors](#authors)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Getting Started

* `master` contains aggregate code of all branches

```
ThreeJSApp
	├── README.md
	├── .gitignore
	├── server      
	│   ├── routes
        │   │	└── dalleRoutes.js        
	│   ├── index.js
	│   ├── .gitignore
	│   ├── package-lock.json
	│   └── package.json
	└── client
		├── public
		│	└── ...
		├── src
		│	├── assets
              	│	│	└── ...
		│	├── canvas
              	│	│	└── ... 
		│	├── components
              	│	│	└── ...     
 		│	├── config
              	│	│	└── ...    
 		│	├── pages
               	│	│	└── ...   
 		│	├── store
               	│	│	└── ...   
 		│	├── App.jsx
 		│	├── index.css
		│	└── main.jsx
		├── package-lock.json
		├── package.json
		├── postcss.config.cjs
		├── index.html
		├── tailwind.config.cjs
		└── vite.config.js
```

### Tools Required

* Any web development IDE can be used, but I would recommend Visual Code.
* React, Tailwind CSS, ThreeJS, React-Fiber, React-Drei and React-Color.
* Third Party Tools: Mongoose, OpenAI, Cloudinary, Dotenv, Express, Nodemon, Cors, Maath, Valtio and Framer-Motion.


### Installation

Note: All installations are done using npm.

* Installing ThreeJS
  ```
    npm i three
  ```

* Installing React-Fiber
  ```
    npm i @react-three/fiber
  ```

* Installing React-Drei
  ```
    npm i @react-three/drei
  ```
  
* Installing React-Color
  ```
    npm i @react-color
  ```
  
* Installing Framer-Motion
  ```
	npm i framer-motion
  ```

* Installing Mongoose
  ```
	npm i mongoose
  ```

* Installing OpenAI
  ```
	npm i openai
  ```

* Installing Cloudinary
  ```
	npm i cloudinary
  ```

* Installing Dotenv
  ```
	npm i react-dotenv
  ```

* Installing Express
  ```
	npm i express
  ```

* Installing Nodemon
  ```
	npm i nodemon
  ```
  
* Installing Cors
  ```
	npm i cors
  ```
  
* Installing Maath
  ```
	npm i maath
  ```

* Installing Valtio
  ```
	npm i valtio
  ```
  

## Running the App
There are two ways in running the app:

* Client Side:
  ```
    npm run dev
  ```

* Server Side:
  ```
    npm start
  ```

## Deployment

The app is deployed on **Netlify**.

### Steps in Deploying App

1. Create Netlify account.
2. Go to *Sites*.
3. Click on *Add New Site*.
4. Select *Import an existing project*.
5. Use any of the Git Providers (Note: I'll continue with GitHub as it's the most common used)
6. After connecting to your GitHub account, choose the existing repositiry you would like to deploy.
7. Click on *Deploy Site*.
8. Wait for site to build and deploy.

## Authors

#### Omar Adam Mostafa
* [GitHub]
* [LinkedIn]

## License

`ThreeJSApp` is open source software [licensed as MIT][license].

## Acknowledgments

* This app was developed through a tutorial on Udemy called **Build and Deploy an AI-Powered 3D Website Using React** by JavaScript Mastery.

[//]: # (HyperLinks)

[GitHub Repository]: https://github.com/OmarAdamMostafa/ThreeJSApp
[Official Site]: https://threejsapp-omar-adam.netlify.app/

[GitHub]: https://github.com/OmarAdamMostafa
[LinkedIn]: https://www.linkedin.com/in/omar-adam-mostafa-a445a3259/

[license]: https://github.com/OmarAdamMostafa/ThreeJSApp/blob/main/license
