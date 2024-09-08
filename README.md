# immersion-v2
Assignment 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML</title>

    <title>Basic HTML Template</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="UTF-8">
    <style>
        
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background: #e32020;color: rgb(31, 28, 139);
        }
        header {
            background-color: #453f3f;
            padding: 10px 0;
            text-align: center;
            margin-bottom: 20px;
        }
        form {
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
            border-collapse: collapse;
            padding: 8px;
            text-align: left;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Basic HTML Page</h1>
    </header>

    <h2>Basic Registration Form</h2>
    <p>Please fill out the form below to register.</p>

    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br><br>
        
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>
        
        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone"><br><br>
        
        <input type="submit" value="Register">
    </form>

    <h2>Registered Users</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Phone Number</th>
        </tr>
        <tr>
            <td>Alexander Luthor</td>
            <td>luthor711@example.com</td>
            <td>+2348089034760</td>
        </tr>
        <tr>
            <td>Sperable John</td>
            <td>sperableeduorg990@example.com</td>
            <td>+2348075363212</td>
        </tr>
    </table>

    <h2>Sample Image</h2>
    <img src="portfolio image.png" alt="Sample Image" width="200px" height="200px">

    <p>Visit <a href="https://google.com" target="_blank">Google</a> for more information.</p>
</body>

</html>
