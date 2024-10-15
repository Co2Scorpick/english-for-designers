<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(120deg, #3498db, #8e44ad);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            justify-content: flex-start;
            min-height: 100vh;
            overflow: auto;
            color: #fff;
            padding-left: 50px;
            padding-top: 20px;
        }

        h1 {
            font-size: 4rem;
            font-weight: 700;
            margin-bottom: 20px;
            opacity: 0.9;
            text-align: left;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        h1:hover {
            color: #f39c12;
            transform: scale(1.05);
        }

        p {
            font-size: 1.25rem;
            margin: 20px 0;
            max-width: 700px;
            text-align: left;
            opacity: 0.9;
        }

        ul {
            margin: 20px 0;
            padding-left: 20px;
        }

        table {
            margin: 20px 0;
            border-collapse: collapse;
            width: 100%;
            max-width: 700px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
        }

        th, td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
            color: #333; /* Černý text */
        }

        th {
            background-color: rgba(255, 255, 255, 0.3);
        }

        tr:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }

        .button-container {
            display: flex;
            gap: 20px;
            margin: 40px 0;
            opacity: 0.9;
        }

        .button {
            padding: 15px 30px;
            border-radius: 30px;
            background-color: #fff;
            color: #333;
            font-size: 1rem;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .button:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.3);
            background-color: #333;
            color: #fff;
        }

        /* Floating circles */
        .background-bubble {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            animation: move 20s infinite ease-in-out;
        }

        .bubble1 {
            width: 200px;
            height: 200px;
            bottom: 10%;
            left: 5%;
        }

        .bubble2 {
            width: 150px;
            height: 150px;
            top: 15%;
            right: 10%;
        }

        /* Additional bubbles */
        .bubble3 {
            width: 250px;
            height: 250px;
            bottom: 30%;
            right: 5%;
        }

        .bubble4 {
            width: 100px;
            height: 100px;
            top: 5%;
            left: 20%;
        }

        @keyframes move {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
    </style>
</head>
<body>

    <div class="background-bubble bubble1"></div>
    <div class="background-bubble bubble2"></div>
    <div class="background-bubble bubble3"></div>
    <div class="background-bubble bubble4"></div>

    <h1>I'm Ondřej Mišák</h1>
    <p>As a designer, I’m passionate about creating beautiful, modern, and functional digital experiences. Let's connect and build something amazing together.</p>

    <div class="button-container">
        <a href="mailto:misak.ondrej@email.cz" class="button">Contact Me</a>
        <a href="https://www.figma.com/design/0YlSm7hb7xT16KIkEb62Of/Portfolio?node-id=0-1" class="button" target="_blank">View Portfolio</a>
    </div>

    <p>Here’s some additional information about my interests:</p>
    <ul>
        <li>Web Design</li>
        <li>User Experience</li>
        <li>Graphic Design</li>
        <li>Photography</li>
    </ul>

    <p>Check out the following table for my skills:</p>
    <table>
        <thead>
            <tr>
                <th>Skills</th>
                <th>Tools</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Branding + Product Design</td>
                <td>Adobe Photoshop</td>
            </tr>
            <tr>
                <td>Digital Media Design</td>
                <td>Adobe Illustrator</td>
            </tr>
            <tr>
                <td>Wireframing</td>
                <td>Adobe Premiere Pro</td>
            </tr>
            <tr>
                <td>Graphic Design</td>
                <td>Adobe InDesign</td>
            </tr>
            <tr>
                <td>Digital Art and Illustration</td>
                <td>Adobe After Effects</td>
            </tr>
            <tr>
                <td>Social Media Management</td>
                <td>Microsoft 365</td>
            </tr>
            <tr>
                <td>Creativity</td>
                <td>Figma</td>
            </tr>
            <tr>
                <td></td>
                <td>Clip Studio</td>
            </tr>
            <tr>
                <td></td>
                <td>Blender</td>
            </tr>
            <tr>
                <td></td>
                <td>Sketch</td>
            </tr>
        </tbody>
    </table>

    <p>Enjoy this funny GIF!</p>
    <img src="frogwalk.gif" alt="Frog Walking" style="max-width: 100%; height: auto;">

</body>
</html>
