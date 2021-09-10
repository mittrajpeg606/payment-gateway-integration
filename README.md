#This is a React App 'Animal Ngo' integrated with payment gateway 'Razorpay' in test mode made for internship at The Sparks Foundation
Technologies used:
react.js
react bootstrap
Razorpay pages to integrate payment gateway
netlify to deploy the website

to create react app
npx create-react-app app_name
cd app_name
npm start // to start the developtment environment in your browser



For React-Bootstrap
paste these in app.js
import "bootstrap/dist/css/bootstrap.min.css";
import * as ReactBootStrap from "react-bootstrap";

run this in terminal in your app folder 
npm install react-bootstrap@next bootstrap@5.1.0

put this in public->index.js
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css"
  integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We"
  crossorigin="anonymous"
/>

src->App.js
import { BrowserRouter as Router, Switch, Route } from "react-router-dom";
import { Link } from "react-router-dom";

run this in terminal in your app folder
npm install react-router-dom

to make an optimised build for deployment run this command in terminal of app folder
npm run build 



