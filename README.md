<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog</title>
    <style>
        /* Basic Reset */
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }

        /* Page Styling */
        body { background-color: #f9f9f9; color: #333; }
        header { background-color: #3c8dbc; padding: 20px; text-align: center; color: #fff; }
        header h1 { font-size: 2.5em; }
        nav ul { display: flex; justify-content: center; padding: 10px 0; }
        nav ul li { list-style: none; margin: 0 15px; }
        nav ul li a { color: #fff; text-decoration: none; font-weight: bold; }

        /* Main Content */
        .container { max-width: 800px; margin: 30px auto; padding: 0 20px; }
        .section { margin-bottom: 40px; }
        .section h2 { font-size: 1.8em; margin-bottom: 10px; color: #3c8dbc; }
        .section p { line-height: 1.6; margin-top: 10px; }

        /* Footer Styling */
        footer { background-color: #333; padding: 20px; text-align: center; color: #fff; margin-top: 30px; }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Blog</h1>
        <nav>
            <ul>
                <li><a href="#important-topics">Important Topics</a></li>
                <li><a href="#world-journey">World Journey</a></li>
                <li><a href="#fiction-stories">Fiction Stories</a></li>
                <li><a href="#economic-knowledge">Economic Knowledge</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <div class="container">
        <!-- Important Topics Section -->
        <section id="important-topics" class="section">
            <h2>Important Topics</h2>
            <p>Explore a variety of essential topics covering current events, insightful thoughts, and much more.</p>
        </section>

        <!-- World Journey Section -->
        <section id="world-journey" class="section">
            <h2>World Journey</h2>
            <p>Join me as I explore the wonders of the world, one destination at a time.</p>
        </section>

        <!-- Fiction Stories Section -->
        <section id="fiction-stories" class="section">
            <h2>Fiction Stories</h2>
            <p>Dive into captivating tales and fictional worlds crafted for your enjoyment.</p>
        </section>

        <!-- Economic Knowledge Section -->
        <section id="economic-knowledge" class="section">
            <h2>Economic Knowledge</h2>
            <p>Gain insights into the world of economics, with simplified explanations and real-world examples.</p>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 My Blog | Designed with care and curiosity</p>
    </footer>

</body>
</html>