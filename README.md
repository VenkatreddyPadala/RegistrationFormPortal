<h2>Registration Form</h2>

<p>Visit the live site: <a href="https://registrationformportals.onrender.com/">Registration Form</a></p>

<h3>Overview</h3>
<p>The Registration Form project allows users to register with their first name, last name, email, and password. It utilizes Express.js for server-side handling, MongoDB for database storage, and provides a simple HTML form for user interaction.</p>

<h3>Features</h3>
<ul>
    <li>User Registration: Users can register by providing their first name, last name, email, and password.</li>
    <li>Duplicate Email Check: Checks for existing users with the same email address to prevent duplicate registrations.</li>
    <li>Success and Error Pages: Displays success and error pages based on the registration outcome.</li>
    <li>Static File Serving: Serves static HTML, CSS, and JavaScript files for the frontend interface.</li>
</ul>

<h3>Modules Used</h3>
<pre><code>
const express = require("express");
const mongoose = require("mongoose");
const bodyParser = require("body-parser");
const dotenv = require("dotenv");
</code></pre>

<h3>Setup</h3>
<ol>
    <li>Clone the repository:</li>
    <pre><code>git clone &lt;repository_url&gt;</code></pre>
    
  <li>Install dependencies:</li>
    <pre><code>npm install</code></pre>
    
  <li>Set up environment variables: Create a .env file in the project root directory and specify the following variables:</li>
    <pre><code>PORT=&lt;port_number&gt;
MONGODB_USERNAME=&lt;mongodb_username&gt;
MONGODB_PASSWORD=&lt;mongodb_password&gt;</code></pre>
</ol>

<h3>Running the Application</h3>
<p>The server will start running on the specified port.</p>
<pre><code>npm start</code></pre>

<h3>API Endpoints</h3>
<pre><code>
const app = express();

app.post("/register", async (req, res) => {
    // Registration logic
});

app.get("/success", (req, res) => {
    // Success page logic
});

app.get("/error", (req, res) => {
    // Error page logic
});
</code></pre>

<h3>Contributing</h3>
<p>Contributions are welcome! Please fork the repository and submit a pull request with your enhancements or bug fixes.</p>
