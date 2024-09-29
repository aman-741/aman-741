- 👋 Hi, I’m @aman-741
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
aman-741/aman-741 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f8f9fa;
    color: #333;
}

/* Navigation Bar */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
}

.navbar .logo {
    font-size: 1.5em;
}

.navbar .nav-links {
    list-style: none;
    display: flex;
    gap: 15px;
}

.navbar .nav-links li a {
    color: white;
    text-decoration: none;
    font-size: 1em;
}

.navbar .profile {
    background-color: #28a745;
    padding: 5px 15px;
    border-radius: 20px;
    cursor: pointer;
}

/* Main Container */
.container {
    display: flex;
    margin: 20px;
}

/* Sidebar */
.sidebar {
    background-color: #343a40;
    color: white;
    width: 200px;
    padding: 20px;
}

.sidebar ul {
    list-style: none;
}

.sidebar ul li {
    margin: 15px 0;
    cursor: pointer;
}

/* Content Area */
.content {
    flex-grow: 1;
    padding: 20px;
}

/* Stock Ticker */
.ticker {
    background-color: #ff9800;
    color: white;
    padding: 10px;
    margin-bottom: 20px;
    font-weight: bold;
}

/* Dashboard */
.dashboard {
    margin-bottom: 20px;
}

.dashboard .cards {
    display: flex;
    justify-content: space-between;
    gap: 10px;
}

.dashboard .card {
    background-color: #007bff;
    color: white;
    padding: 20px;
    flex-basis: 30%;
    border-radius: 5px;
    text-align: center;
}

/* Chart Area */
.chart {
    background-color: white;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

/* Footer */
footer {
    text-align: center;
    padding: 10px;
    background-color: #007bff;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}

