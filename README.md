<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samuel's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background: url('https://source.unsplash.com/1600x400/?programming') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 1em;
        }

        nav {
            text-align: center;
            background-color: #333;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        main {
            background: url('https://source.unsplash.com/1600x900/?coding') center/cover no-repeat;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        section {
            margin-bottom: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 8px;
            width: 100%;
            max-width: 800px;
        }

        footer {
            background: url('https://source.unsplash.com/1600x300/?developer') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        a {
            color: #007bff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        form {
            max-width: 400px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
        }

        form label {
            display: block;
            margin-bottom: 8px;
        }

        form input {
            width: 100%;
            padding: 8px;
            margin-bottom: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        form button {
            background-color: #007bff;
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        /* Align the login form to the right */
        section.login-form {
            align-self: flex-end;
        }

        /* Align the contact form to the bottom */
        section.contact-form {
            align-self: flex-end;
            margin-top: auto;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Samuel's Portfolio</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
        <a href="#">Login</a>
        <a href="#">Sign Up</a>
    </nav>

    <main>
        <section>
            <h2>About Samuel</h2>
            <p>Hello, I'm Samuel, a skilled programmer and the creative mind behind this website. With a passion for coding and innovation, I specialize in crafting websites that not only look great but also function seamlessly. This platform serves as a showcase of my work and skills.</p>
            <p>If you're in need of a website for your business or personal projects, I'm here to help! I offer my services to individuals, small businesses, or anyone in need of a web presence. Whether you have a specific vision in mind or need assistance in shaping your ideas, I'm ready to collaborate with you.</p>
            <p>Feel free to explore my portfolio, and don't hesitate to get in touch if you'd like to discuss your project. I'm open to collaborations and excited about the possibility of turning your ideas into a reality. Let's build something amazing together!</p>
        </section>

        <section class="login-form">
            <h2>Login</h2>
            <form>
                <label for="username">Username:</label>
                <input type="text" id="username" name="username" required>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" required>

                <button type="submit">Login</button>
            </form>
        </section>

        <section class="contact-form">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Samuel's Portfolio</p>
    </footer>

</body>
</html>
