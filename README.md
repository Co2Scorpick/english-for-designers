WELCOME!
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ondřej Mišák - Designer</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #f06, #ffcc00);
            color: #fff;
            text-align: center;
            padding: 50px;
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
            animation: fadeIn 2s ease-in-out forwards;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.5rem;
            max-width: 600px;
            animation: slideUp 2s ease-in-out forwards;
            opacity: 0;
        }

        .contact-btn {
            display: inline-block;
            margin-top: 30px;
            padding: 15px 30px;
            background-color: #fff;
            color: #333;
            font-size: 1rem;
            border-radius: 50px;
            text-decoration: none;
            transition: all 0.4s ease-in-out;
            animation: fadeInButton 3s ease-in-out forwards;
            opacity: 0;
        }

        .contact-btn:hover {
            background-color: #333;
            color: #fff;
            transform: translateY(-10px);
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-50px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideUp {
            0% { opacity: 0; transform: translateY(50px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInButton {
            0% { opacity: 0; transform: scale(0.8); }
            100% { opacity: 1; transform: scale(1); }
        }

        /* Floating animation for background circles */
        .circle {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.2);
            animation: float 10s infinite ease-in-out;
        }

        .circle1 {
            width: 200px;
            height: 200px;
            bottom: 10%;
            left: 20%;
            animation-duration: 12s;
        }

        .circle2 {
            width: 300px;
            height: 300px;
            top: 20%;
            right: 15%;
            animation-duration: 8s;
        }

        .circle3 {
            width: 150px;
            height: 150px;
            bottom: 30%;
            right: 35%;
            animation-duration: 10s;
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
    <div class="circle circle3"></div>

    <h1>My name is Ondřej Mišák</h1>
    <p>As a designer, I’m passionate about crafting experiences that seamlessly blend beauty with function. Whether it's sleek interfaces or intuitive user flows, I thrive on turning ideas into designs that make an impact.</p>
    <a href="mailto:misak.ondrej@email.cz" class="contact-btn">Get in touch</a>

</body>
</html>
