# school
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Welcome - [Your School Name]</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Link to CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <!-- School Logo -->
        <img src="school-logo.png" alt="School Logo" class="logo">

        <h1>Welcome to [Your School Name]</h1>
        <div class="buttons">
            <a href="register.html" class="btn">Register</a>
            <a href="login.html" class="btn">Login</a>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Register - [Your School Name]</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Link to CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <!-- School Logo -->
        <img src="school-logo.png" alt="School Logo" class="logo">

        <h1>User Registration</h1>
        <form id="registrationForm">
            <div class="form-group">
                <label for="fullName">Full Name<span>*</span></label>
                <input type="text" id="fullName" name="fullName" required placeholder="John Doe">
            </div>
            <div class="form-group">
                <label for="email">Email Address<span>*</span></label>
                <input type="email" id="email" name="email" required placeholder="example@mail.com">
            </div>
            <div class="form-group">
                <label for="password">Password<span>*</span></label>
                <input type="password" id="password" name="password" required placeholder="Create a password">
            </div>
            <div class="form-group">
                <label for="confirmPassword">Confirm Password<span>*</span></label>
                <input type="password" id="confirmPassword" name="confirmPassword" required placeholder="Confirm your password">
            </div>
            <div class="form-group">
                <label for="document1">Upload Document 1<span>*</span></label>
                <input type="file" id="document1" name="document1" accept="image/*" required>
            </div>
            <div class="form-group">
                <label for="document2">Upload Document 2<span>*</span></label>
                <input type="file" id="document2" name="document2" accept="image/*" required>
            </div>
            <div class="form-group">
                <label for="document3">Upload Document 3<span>*</span></label>
                <input type="file" id="document3" name="document3" accept="image/*" required>
            </div>
            <button type="submit">Register</button>
            <p>Already have an account? <a href="login.html">Log in here</a>.</p>
        </form>
    </div>
    <!-- Link to JavaScript -->
    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login - [Your School Name]</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Link to CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <!-- School Logo -->
        <img src="school-logo.png" alt="School Logo" class="logo">

        <h1>User Login</h1>
        <form id="loginForm">
            <div class="form-group">
                <label for="emailLogin">Email Address<span>*</span></label>
                <input type="email" id="emailLogin" name="emailLogin" required placeholder="example@mail.com">
            </div>
            <div class="form-group">
                <label for="passwordLogin">Password<span>*</span></label>
                <input type="password" id="passwordLogin" name="passwordLogin" required placeholder="Your password">
            </div>
            <button type="submit">Login</button>
            <p>Don't have an account? <a href="register.html">Register here</a>.</p>
        </form>
    </div>
    <!-- Link to JavaScript -->
    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Dashboard - [Your School Name]</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Link to CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <!-- School Logo -->
        <img src="school-logo.png" alt="School Logo" class="logo">

        <h1>Welcome, <span id="userFullName"></span>!</h1>
        <p>This is your dashboard where you can view your information.</p>
        <div class="user-info">
            <h2>Your Details</h2>
            <p><strong>Full Name:</strong> <span id="displayFullName"></span></p>
            <p><strong>Email:</strong> <span id="displayEmail"></span></p>
            <!-- You can add more details or options here -->
        </div>
        <button id="logoutButton">Logout</button>
    </div>
    <!-- Link to JavaScript -->
    <script src="script.js"></script>
</body>
</html>
/* Reset Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f2f4f8;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 400px;
    margin: 50px auto;
    background-color: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: center;
}

/* Logo */
.logo {
    max-width: 150px;
    margin-bottom: 20px;
}

/* Headings */
h1 {
    font-size: 24px;
    margin-bottom: 20px;
    color: #2c3e50;
}

h2 {
    font-size: 20px;
    margin-bottom: 15px;
    color: #2c3e50;
}

/* Form Groups */
.form-group {
    text-align: left;
    margin-bottom: 15px;
}

.form-group label {
    display: block;
    margin-bottom: 5px;
    color: #555;
}

.form-group label span {
    color: red;
}

.form-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccd1d9;
    border-radius: 4px;
    font-size: 14px;
}

/* Buttons */
button[type="submit"], #logoutButton {
    width: 100%;
    padding: 12px;
    background-color: #2980b9;
    color: #fff;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    cursor: pointer;
    margin-top: 10px;
    transition: background-color 0.3s;
}

button[type="submit"]:hover, #logoutButton:hover {
    background-color: #2573a6;
}

/* Links */
p {
    margin-top: 15px;
    font-size: 14px;
}

p a {
    color: #2980b9;
    text-decoration: none;
}

p a:hover {
    text-decoration: underline;
}

/* User Info */
.user-info {
    text-align: left;
    margin-top: 20px;
}

.user-info p {
    margin-bottom: 10px;
    font-size: 16px;
}

/* Buttons Container */
.buttons {
    display: flex;
    justify-content: space-between;
}

.buttons .btn {
    flex: 1;
    margin: 5px;
    background-color: #2980b9;
    color: #fff;
    padding: 12px 0;
    text-decoration: none;
    border-radius: 4px;
    font-size: 16px;
    transition: background-color 0.3s;
}

.buttons .btn:hover {
    background-color: #2573a6;
}

/* Responsive Design */
@media (max-width: 480px) {
    .container {
        margin: 20px auto;
        padding: 20px;
    }
}
// Utility functions
function getUsers() {
    let users = localStorage.getItem('users');
    return users ? JSON.parse(users) : [];
}

function saveUser(user) {
    let users = getUsers();
    users.push(user);
    localStorage.setItem('users', JSON.stringify(users));
}

function findUser(email) {
    let users = getUsers();
    return users.find(user => user.email === email);
}

function setCurrentUser(email) {
    localStorage.setItem('currentUser', email);
}

function getCurrentUser() {
    return localStorage.getItem('currentUser');
}

function clearCurrentUser() {
    localStorage.removeItem('currentUser');
}

// Registration Form Handling
if (document.getElementById('registrationForm')) {
    document.getElementById('registrationForm').addEventListener('submit', function(e) {
        e.preventDefault();

        let fullName = document.getElementById('fullName').value.trim();
        let email = document.getElementById('email').value.trim();
        let password = document.getElementById('password').value;
        let confirmPassword = document.getElementById('confirmPassword').value;
        let document1 = document.getElementById('document1').files[0];
        let document2 = document.getElementById('document2').files[0];
        let document3 = document.getElementById('document3').files[0];

        // Basic validation
        if (!fullName || !email || !password || !confirmPassword || !document1 || !document2 || !document3) {
            alert('Please fill out all required fields and upload all documents.');
            return;
        }

        if (password !== confirmPassword) {
            alert('Passwords do not match.');
            return;
        }

        if (findUser(email)) {
            alert('An account with this email already exists.');
            return;
        }

        // Convert documents to data URLs (for demonstration)
        let reader1 = new FileReader();
        let reader2 = new FileReader();
        let reader3 = new FileReader();

        reader1.onload = function() {
            let doc1Data = reader1.result;

            reader2.onload = function() {
                let doc2Data = reader2.result;

                reader3.onload = function() {
                    let doc3Data = reader3.result;

                    // Save user data
                    let user = {
                        fullName: fullName,
                        email: email,
                        password: password,
                        documents: [doc1Data, doc2Data, doc3Data]
                    };

                    saveUser(user);
                    setCurrentUser(email);
                    alert('Registration Successful!');
                    window.location.href = 'dashboard.html';
                };

                reader3.readAsDataURL(document3);
            };

            reader2.readAsDataURL(document2);
        };

        reader1.readAsDataURL(document1);
    });
}

// Login Form Handling
if (document.getElementById('loginForm')) {
    document.getElementById('loginForm').addEventListener('submit', function(e) {
        e.preventDefault();

        let email = document.getElementById('emailLogin').value.trim();
        let password = document.getElementById('passwordLogin').value;

        let user = findUser(email);

        if (user && user.password === password) {
            setCurrentUser(email);
            alert('Login Successful!');
            window.location.href = 'dashboard.html';
        } else {
            alert('Invalid email or password.');
        }
    });
}

// Dashboard Page Handling
if (window.location.pathname.endsWith('dashboard.html')) {
    let currentUserEmail = getCurrentUser();

    if (!currentUserEmail) {
        alert('Please log in to access the dashboard.');
        window.location.href = 'login.html';
    } else {
        let user = findUser(currentUserEmail);
        document.getElementById('userFullName').textContent = user.fullName;
        document.getElementById('displayFullName').textContent = user.fullName;
        document.getElementById('displayEmail').textContent = user.email;

        // Handle Logout
        document.getElementById('logoutButton').addEventListener('click', function() {
            clearCurrentUser();
            window.location.href = 'login.html';
        });
    }
}
