# Blog App React Frontend

## Overview

This is the front end of a blog application built with React and Material UI. The app is designed to allow users to view, add, edit, and delete blog posts. It interacts with a Django backend API for CRUD operations.

Github link of Blog App Django Backend: https://github.com/chrisnumber49/Blog-App-Django-Backend

## Features

Responsive Design: The application adapts to various screen sizes, making it mobile-friendly.

State Management: Uses React's built-in state to manage application data.

User Interface: Developed with Material UI components for a modern and clean UI.

## Technologies Used
React for building the user interface.

Material UI for UI components and styling.

Axios for API requests.

React Router for navigation.

## Project Screen Shots
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo1.PNG" width="700" > 
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo2.png" width="700" > 
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo3.PNG" width="700" > 
<img src="https://github.com/chrisnumber49/Blog-App-React-Frontend/blob/master/screen%20shot/demo4.PNG" width="700" > 

## Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.  
 
Installation: `npm install create-react-app`  

To Start Server: `npm start`  

To Visit App: `localhost:3000/`

## Reflection 

This is my first side project of integrating full-stack development with React frontend and Django backend. In the React frontend, I built a React frontend interface for the blog application. In the frontend of this blog app, we first render the login page, after authentication succeeded the page will request the data from the backend API to render each post, and following users can create, modify, and delete their posts according to their login status or create and delete comments in any existing post. All of the information in each post will be stored in the database in the backend REST API.

I started this project by using the command `create-react-app` to create the boilerplate, then several additional libraries, `Bootstrap`, `react-cookie`, and `react-router-dom` were installed during the development of this project.  

In the frontend interface of this side project, I learned about more methods in the fetch function to implement the full stack CRUD and the concept of react-cookie for the token authentication in each request.
