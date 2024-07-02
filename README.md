Single Page App with Flask and Vue.js
=====================================

This project is a single-page application (SPA) built with Flask on the backend and Vue.js on the frontend. It allows users to add, edit, and delete books.

Features
--------

*   **Add Books**: Users can add new books to the list.
    
*   **Edit Books**: Users can update details of existing books.
    
*   **Delete Books**: Users can remove books from the list.
    

Prerequisites
-------------

*   Python 3.x
    
*   Node.js and npm
    

How to run this project?
------------------------

### 1\. Fork/Clone the Repository

Fork the repository on GitHub, then clone your fork to your local machine:

`$ git clone https://github.com/issa-suleiman/book-manager-vue-flask.git` 

 `$ cd book-manager-vue-flask   `

### 2\. Run the Server-Side Flask App

Open a terminal window and navigate to the server directory. Create and activate a virtual environment, install dependencies, and run the Flask app:

`$ cd server`
`$ python3 -m venv env`
`$ source env/bin/activate`
`$ pip install -r requirements.txt`
`$ flask run --port=5001 --debug`

The server will be running at [http://localhost:5001](http://localhost:5001).

### 3\. Run the Client-Side Vue App

Open a different terminal window and navigate to the client directory. Install dependencies and run the development server:

`$ cd client`
`$ npm install`
`$ npm run dev   `

The client will be running at [http://localhost:5173](http://localhost:5173).