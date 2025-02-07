/* style.css */
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* Subtle background */
    color: #333; /* Dark text for contrast */
    line-height: 1.6;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 1rem;
}

section {
    padding: 2rem;
}

.project {
    margin-bottom: 2rem;
    border: 1px solid #ddd; /* Light border */
    padding: 1rem;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.1); /* Subtle shadow */
}

.project img {
    max-width: 100%;
    height: auto;
}


/* Basic responsiveness (expand as needed) */
@media (max-width: 768px) {
    nav {
        text-align: center; /* Center nav on smaller screens */
    }
    nav a {
        display: block; /* Stack links vertically */
        margin: 0.5rem 0;
    }
    .project {
        text-align: center; /* Center project content */
    }
    .project img {
        max-width: 90%;
    }
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
}
