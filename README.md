# ziyad-taha
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taha ue abo el zeik</title>
    <style>
        /* ... (styles unchanged) ... */
    </style>
</head>
<body>
    <header>
        <h1>taha& ziyad</h1>
        <p>Welcome to the website</p>
    </header>

    <nav>
        <a href="#" onclick="navigate('home')">Home</a> |
        <a href="#" onclick="navigate('about')">About</a> |
        <a href="#" onclick="navigate('services')">Services</a> |
        <a href="#" onclick="navigate('contact')">Contact</a>
    </nav>

    <section id="home">
        <h2>Home</h2>
        <p>This is a brief description of your company or personal brand.</p>
    </section>

    <section id="about" style="display: none;">
        <h2>About Us</h2>
        <p>This is more detailed information about your company or personal brand.</p>
    </section>

    <section id="services" style="display: none;">
        <h2>Services</h2>
        <p>Here are the services we offer:</p>
        <ul>
            <li>Service 1</li>
            <li>Service 2</li>
            <li>Service 3</li>
        </ul>
    </section>

    <section id="contact" style="display: none;">
        <h2>Contact Us</h2>
        <p>Include your contact information, a contact form, or any other relevant details here.</p>
    </section>

    <!-- ... (other sections unchanged) ... -->

    <footer>
        &copy; 2023 Your Website. All rights reserved.
    </footer>

    <script>
        function navigate(sectionId) {
            // Hide all sections
            document.querySelectorAll('section').forEach(function(section) {
                section.style.display = 'none';
            });

            // Show the selected section
            document.getElementById(sectionId).style.display = 'block';
        }
    </script>
</body>
</html>
