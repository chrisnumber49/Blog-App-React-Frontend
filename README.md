# Blog App React Frontend

## Overview
This is the front end of a blog application built with React and Material UI. The app is designed to allow users to view, add, edit, and delete blog posts. It interacts with a Django backend API for CRUD operations.

Github link of Blog App Django Backend: https://github.com/chrisnumber49/Blog-App-Django-Backend

## Project Screen Shots
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo1.PNG" width="700" > 
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo2.png" width="700" > 
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo3.PNG" width="700" > 
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo4.PNG" width="700" > 

## Features
Responsive UI: Designed with basic CSS for a clean, minimal user interface.

Functional Components: Built entirely using React functional components and hooks (useState, useEffect, etc).

API Integration: Uses the native fetch API to send and receive data from the backend.

## Technologies Used
React for building the user interface

React Router DOM for client-side routing

Fetch API for handling HTTP requests

## Installation and Setup Instructions
Clone down this repository. You will need `node` and `npm` installed globally on your machine.  
 
Installation: `npm install create-react-app`  

To Start Server: `npm start`  

To Visit App: `localhost:3000/`

## Reflection 
This is my first side project of integrating full-stack development with React frontend and Django backend. I built a React frontend interface for the blog application. In this blog app, we first render the login page. After authentication succeeds, the page will request the data from the backend API to render each post, and following users can create, modify, and delete their posts according to their login status or create and delete comments in any existing post. All of the information in each post will be stored in the database in the backend REST API.

I started this project by using the command `create-react-app` to create the boilerplate, then several additional libraries, `Bootstrap`, `react-cookie`, and `react-router-dom`, were installed during the development of this project.  

In the frontend interface of this side project, I learned about more methods in the fetch function to implement the full stack CRUD and the concept of react-cookie for the token authentication in each request.
