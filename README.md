
# Blog Management System

This project is a blog management system built with Node.js and Express. It allows users to create, edit, and delete blog posts.

## Getting Started

### Prerequisites

Make sure you have the following software installed on your machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/omertzroya/Blog-FullStack-Project.git
   ```

2. Install dependencies:

   ```bash
   cd //Your current path 
   npm i 
   ```

3. Start the server:

   ```bash
   node index.js
   node server.js
   ```

   The server will start on [http://localhost:3000](http://localhost:3000).


 # Technology Used
<div>
  <img src='https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white' alt='JQUERY'/>
  <img src='https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E' alt='JavaScript'/>
  <img src='https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white' alt='CSS3'/>
  <img src='https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white' alt='HTML5'/>
  <img src='https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white' alt='Node.js'/>
  <img src='https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white' alt='Express'/>
  <img src='https://img.shields.io/badge/Axios-35495E?style=for-the-badge&logo=axios&logoColor=white' alt='Axios'/>
</div>

## Features

1. **View All Posts:**
   - Access all blog posts by visiting [http://localhost:3000](http://localhost:3000).

2. **Create a New Post:**
   - Add a new blog post by clicking on the "New Post" button.

3. **Edit a Post:**
   - Update an existing post by clicking on the "Edit" button next to the post.

4. **Delete a Post:**
   - Remove a post by clicking on the "Delete" button next to the post.

## Technology Stack

- **Backend:**
  - Node.js
  - Express
- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - EJS (Embedded JavaScript) for templating
  - 
- **External Libraries:**
  - Axios for making HTTP requests

## Folder Structure

- `public/`: Static files (stylesheets, images, client-side JavaScript)
- `views/`: EJS templates for rendering HTML pages
- `app.js`: Main application file

## API Endpoints

- `GET /`: Render the main page with all blog posts.
- `GET /new`: Render the page for creating a new post.
- `GET /edit/:id`: Render the page for editing a specific post.
- `POST /api/posts`: Create a new post.
- `POST /api/posts/:id`: Update a post.
- `GET /api/posts/delete/:id`: Delete a post.



## Contributing
Feel free to contribute to the project by opening issues or creating pull requests.

## License
![GitHub](https://img.shields.io/github/license/ItsAlexanderPopov/Simon-game)













