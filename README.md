<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Helvetica Neue', sans-serif;
            background: radial-gradient(circle at top left, #ff6f61, #ffcc00);
            color: #fff;
            text-align: center;
            padding: 0;
            margin: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        h1 {
            font-size: 4rem;
            margin: 0;
            animation: popIn 1.5s ease-in-out forwards;
            background: linear-gradient(45deg, #fff, #ffcc00);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        p {
            font-size: 1.2rem;
            max-width: 600px;
            animation: fadeUp 2s ease-in-out forwards;
            opacity: 0;
            color: #f0f0f0;
            margin: 20px 0;
        }

        .button {
            display: inline-block;
            margin: 20px;
            padding: 15px 40px;
            font-size: 1.2rem;
            border-radius: 30px;
            background-color: #fff;
            color: #333;
            text-decoration: none;
            transition: all 0.4s ease-in-out;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        .button:hover {
            background-color: #333;
            color: #fff;
            transform: scale(1.1);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
        }

        /* Floating circles */
        .circle {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            animation: float 10s infinite ease-in-out;
        }

        .circle1 {
            width: 300px;
            height: 300px;
            top: 10%;
            left: 15%;
        }

        .circle2 {
            width: 200px;
            height: 200px;
            bottom: 15%;
            right: 20%;
        }

        @keyframes popIn {
            0% { transform: scale(0.5); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        @keyframes fadeUp {
            0% { opacity: 0; transform: translateY(50px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0); }
        }

    </style>
</head>
<body>

    <div class="circle circle1"></div>
    <div class="circle circle2"></div>

    <h1>Hey there! I'm Ondřej Mišák</h1>
    <p>I create sleek, functional designs that turn ideas into impactful digital experiences. Let’s collaborate to craft something bold and beautiful.</p>

    <a href="mailto:misak.ondrej@email.cz" class="button">Contact Me</a>
    <a href="https://www.figma.com/design/0YlSm7hb7xT16KIkEb62Of/Portfolio?node-id=0-1" class="button" target="_blank">View Portfolio</a>

</body>
</html>
