<h1>My First Website</h1>

<p>Welcome to my first website! This project is a simple notes web application built using Python and Flask. It includes user authentication, login/logout functionality, and the ability to sign up for a new account. The project also uses SQLAlchemy for database management.</p>

<h3>Features</h3>
<ul>
  <li>User Authentication: Users can sign up for a new account, log in, and log out securely.</li>
  <li>Password Hashing: Passwords are securely hashed using the werkzeug.security library, ensuring the safety  of user credentials.</li>
</ul>

<h2>Getting Started</h2>
To run this project locally, follow these steps:

<ol>
  <li>Clone the repository: <code>git clone <repo-url></code>
</li>
  <li> Install dependencies: <code> pip install -r requirements.txt </code> </li>
  <li>Run the application: <code>python main.py</code> </li>
  <li>Open your web browser and navigate to http://127.0.0.1:5000/ to access the website.</li>
</ol>

<h3>Project Structure</h3>

<ul>
  
<b>app.py: </b>Contains the Flask application setup and configuration.

<b>views.py:</b> Handles the main views and routes of the application.

<b>auth.py:</b> Manages user authentication, including login, logout, and sign-up.

<b>models.py:</b> Defines the database models, such as the User model.

<b>templates/:</b> Contains HTML templates for rendering the web pages.

</ul>

<h3>Dependencies</h3>
<ul>
<li>Flask</li>
<li>Flask-SQLAlchemy</li>
<li>Flask-Login</li>
</ul>



 

