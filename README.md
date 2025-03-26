<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia & Form Page</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
        }
        table {
            width: 50%;
            margin: 20px auto;
        }
        form {
            width: 300px;
            margin: 20px auto;
        }

        form label{
          display: block;
          margin-top: 10px;
        }
        form input, form select{
          width: 100%;
          padding: 8px;
          box-sizing: border-box;
        }
    </style>
</head>
<body>

    <header>
        <h1>Multimedia and Registration</h1>
    </header>

    <main>
        <section>
            <h2>Multimedia</h2>
            <img src="https://via.placeholder.com/300" alt="Placeholder Image">

            <audio controls>
                <source src="audio.ogg" type="audio/ogg">
                <source src="audio.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>

            <video width="320" height="240" controls>
                <source src="video.mp4" type="video/mp4">
                <source src="video.ogg" type="video/ogg">
                Your browser does not support the video element.
            </video>
        </section>

        <section>
            <h2>Registration Form</h2>
            <form action="/register" method="post">
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required minlength="3">

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required minlength="8">

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="country">Country:</label>
                <select id="country" name="country">
                    <option value="usa">Republic of South Aftrica</option>
                    <option value="canada">Kenya</option>
                    <option value="uk">Zimbabwe</option>
                    <option value="other">Other</option>
                </select>

                <input type="submit" value="Register">
            </form>
        </section>

        <section>
            <h2>Data Table</h2>
            <table>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Age</th>
                        <th>City</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Alice</td>
                        <td>30</td>
                        <td>Johannesburg</td>
                    </tr>
                    <tr>
                        <td>Bob</td>
                        <td>25</td>
                        <td>Nairobi</td>
                    </tr>
                    <tr>
                        <td>Charlie</td>
                        <td>35</td>
                        <td>Harare</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2>Countries of origin:</h2>
            <h3>Unordered List</h3>
            <ul>
                <li>Republic of South Africa</li>
                <li>Kenya</li>
                <li>Zimbabwe</li>
            </ul>

            <h2>Age in order</h2>
            <h3>Ordered List</h3>
            <ol>
                <li>25</li>
                <li>30</li>
                <li>35</li>
            </ol>
        </section>
    </main>

    <footer>
        <p>Contact: mifivelile@gmail.com</p>
    </footer>

</body>
</html>
# Webdev_week2_assignment
