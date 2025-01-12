/* Global Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    text-align: center;
}

header nav {
    margin-top: 10px;
}

header nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
}

header nav a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}

/* Content */
.container {
    padding: 20px;
    max-width: 800px;
    margin: 20px auto;
    background: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 10px 0;
}

/* Form */
form label {
    display: block;
    margin: 10px 0 5px;
}

form input, form textarea, form button {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    background-color: #333;
    color: white;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}
