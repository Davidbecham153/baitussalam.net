/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and Page Layout */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header Styling */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 20px;
}

nav img {
    height: 50px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 18px;
    transition: color 0.3s ease;
}

nav a:hover {
    color: #f0a500;
}

nav input[type="text"] {
    padding: 5px 10px;
    font-size: 16px;
    margin-right: 10px;
    border: none;
    border-radius: 4px;
}

nav button {
    padding: 6px 15px;
    background-color: #f0a500;
    border: none;
    border-radius: 4px;
    color: white;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s ease;
}

nav button:hover {
    background-color: #e08700;
}

/* Main Section */
main {
    padding: 20px;
    background-color: white;
}

section {
    margin-bottom: 20px;
}

section h1 {
    font-size: 24px;
    color: #333;
}

section p {
    font-size: 16px;
    color: #555;
    line-height: 1.5;
}

/* Footer (Optional) */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 40px;
}
