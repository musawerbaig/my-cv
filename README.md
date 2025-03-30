<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
            transition: background 0.3s, color 0.3s;
        }

        header {
            background: #333;
            color: white;
            padding: 20px;
            border-radius: 10px;
        }

        header img {
            width: 100px;
            border-radius: 50%;
        }

        h2 {
            color: #555;
        }

        section {
            background: white;
            padding: 15px;
            margin: 15px auto;
            width: 80%;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }

        button {
            background: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 10px;
        }

        button:hover {
            background: #555;
        }

        .dark-theme {
            background-color: #333;
            color: white;
        }

        .dark-theme section {
            background-color: #444;
            color: white;
        }
    </style>
</head>
<body>

    <header>
        <img src="mypic.jpg" alt="Profile Picture">
        <h1>Muhammad Musawer</h1>
        <p>Student</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>I am a passionate web developer with experience in front-end and back-end technologies.</p>
    </section>

    <section class="experience">
        <h2>Experience</h2>
        <ul>
            <li><strong>Web Developer</strong> - XYZ Company (2022-Present)</li>
            <li><strong>Intern</strong> - ABC Tech (2021-2022)</li>
        </ul>
    </section>

    <section class="education">
        <h2>Education</h2>
        <p>Bachelor's Degree in Computer Science - Comsats University Isalmabad</p>
    </section>

    <section class="contact">
        <h2>Contact</h2>
        <p>Email: musawerbaig.com</p>
        <p>Phone: +923478969175</p>
    </section>

    <button onclick="changeTheme()">Toggle Theme</button>

    <script>
        function changeTheme() {
            document.body.classList.toggle("dark-theme");
        }
    </script>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
    <title>My CV</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 50px; }
        h1 { color: #2c3e50; }
        p { font-size: 18px; }
    </style>
</head>
<body>
    <h1>Umer Iqbal</h1>
    <p>Software Engineer | AWS Cloud Enthusiast | Students Lover | LMKR</p>
    <p>Email: umer.iqbal@iiui.edu.pk</p>
</body>
</html>
