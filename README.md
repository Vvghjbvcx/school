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
