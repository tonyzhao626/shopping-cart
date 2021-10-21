# A shopping cart function app for ecommerce

<p align="center">
  <img src="https://img.shields.io/badge/React-16.3.1-blue.svg">
  <img src="https://img.shields.io/badge/Redux-3.7.2-blue.svg?colorB=764abc">
  <img src="https://img.shields.io/badge/Nodejs-6.10.2-blue.svg?colorB=90c53f">
  <img src="https://img.shields.io/badge/Express-4.16.3-blue.svg?colorB=47535e">
  <br/>
  <img src="./doc/img/react-store.gif">
</p>

## Features
- Add and remove products from the floating cart
- Sort products by highest to lowest and lowest to highest price
- Filter products by available sizes
- Products persist in floating cart even after page reloads
- Responsive design for desktop, tablets and mobile
- Product stoppers for free shipping

## Tech Stack
- React
- Redux
- Nodejs
- Express CORS Middleware
- Nodemon
- Axios
- Native local storage API 
- BEM methodology
- SASS

## Running
``` bash
npm install
// Run the API Server
npm run server
// Start the React App
npm start
```

The products API will be running on  `http://localhost:8001/api/products`
<br/>
The application will start automatically in browser on `http://localhost:3000`

## Todo
- [ ] Implement filters by URL params using react-router
- [ ] Write tests

