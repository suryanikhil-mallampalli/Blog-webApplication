<!DOCTYPE html>
<html>
<body>
	<h1>Express Blog App</h1>
	<p>This repository contains the code for a simple blog app built using Express.js, EJS, and Lodash. Users can view the home page, read posts, and create new posts using a form. The blog posts are stored in an array on the server side and rendered dynamically using EJS templates.</p>
  <h2>Installation</h2>
<ul>
	<li>Clone the repository to your local machine.</li>
	<li>Install the required dependencies by running the command 'npm install' in your terminal.</li>
	<li>Run the command 'node app.js' to start the server.</li>
	<li>The app will be running on port 3000. Open your browser and go to 'http://localhost:3000/' to view the home page.</li>
</ul>

<h2>Dependencies</h2>
<ul>
	<li>Express.js - a fast and minimalist web framework for Node.js.</li>
	<li>Body-parser - middleware for handling HTTP request data.</li>
	<li>EJS - a simple templating engine for generating HTML markup with plain JavaScript.</li>
	<li>Lodash - a JavaScript utility library for working with arrays, objects, and other data types.</li>
</ul>

<h2>Routes</h2>
<ul>
	<li>GET / - displays the home page with a list of all posts.</li>
	<li>GET /about - displays the about page.</li>
	<li>GET /contact - displays the contact page.</li>
	<li>GET /compose - displays a form for creating a new blog post.</li>
	<li>GET /posts/:postName - displays the content of a specific blog post based on the post name in the URL.</li>
	<li>POST /compose - creates a new blog post and adds it to the posts array.</li>
</ul>

<h2>License</h2>
<p>This project is licensed under the MIT License.</p>
</body>
</html>
