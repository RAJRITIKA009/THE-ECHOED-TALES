# THE-ECHOED-TALES
THE WORLD WHERE THE SOUL FINDS PEACE
<html lang="en">
<head>
        <meta name="google-site-verification" content="5l0t4vOhXmelyOYoGXwJVA-H7F2y0SS2dJTMA0D_c4k" />
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, black, baby pink, yellow);
            color: white;
            line-height: 1.6;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: black;
            color: white;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #222;
            padding: 10px 0;
        }
        nav a {
            color: yellow;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: pink;
        }
        .search-bar {
            text-align: center;
            margin: 20px auto;
        }
        .search-bar input[type="text"] {
            padding: 10px;
            width: 80%;
            max-width: 400px;
            border: 2px solid pink;
            border-radius: 5px;
            background-color: #fff;
            color: black;
            transition: transform 0.3s ease, border-color 0.3s ease;
        }
        .search-bar input[type="text"]:focus {
            border-color: yellow;
            transform: scale(1.05);
        }
        .section {
            margin: 40px 20px;
            padding: 20px;
            border-radius: 10px;
            background-color: rgba(255, 255, 255, 0.1);
            color: black;
            text-align: center;
        }
        .sub-section {
            margin-top: 20px;
            padding: 20px;
            background-color: pink;
            color: black;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .sub-section:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: black;
            color: white;
        }
        a {
            color: white;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: pink;
        }
    </style>
</head>
<body>
    <header>
        <h1>The Echoed Tales</h1>
        <p>Where words weave worlds of wonder</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#poems">Poems</a>
        <a href="#stories">Stories</a>
    </nav>
    <div class="search-bar">
        <input type="text" placeholder="Search...">
    </div>
    <section id="home" class="section">
        <h2>Home</h2>
        <p>Welcome to a haven of peace and imagination. Explore our poems and stories crafted to soothe your soul.</p>
    </section>
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>We are dedicated to transforming your thoughts and scenarios into poems and stories that bring tranquility and joy.<br>
           In today's world, as we stay busy dealing with reality, there is a part of us that keeps seeking peace.<br>
           Join us in helping your soul find a place to feel happy and content once again!</p>
    </section>
    <section id="poems" class="section">
        <h2>Poems</h2>
        <div class="sub-section">
            <h3>The Whispering Winds</h3>
            <p>Through valleys deep, the winds do speak,<br>
               A timeless song, a tale unique.<br>
               They whisper secrets, old and true,<br>
               Of worlds unseen, and skies so blue.</p>
        </div>
        <div class="sub-section">
            <h3>Starlit Dreams</h3>
            <p>Beneath the night’s vast, velvet dome,<br>
               The stars invite, they call us home.<br>
               A journey through celestial streams,<br>
               To worlds alive in starlit dreams.</p>
        </div>
    </section>
    <section id="stories" class="section">
        <h2>Stories</h2>
        <div class="sub-section">
            <h3>The Enchanted Forest</h3>
            <p>Once upon a time, in a land cloaked in mist,<br>
               There lay a forest, by sunlight kissed.<br>
               Its trees held magic, its roots ran deep,<br>
               A place where secrets were known to keep.</p>
        </div>
        <div class="sub-section">
            <h3>The Clockmaker's Secret</h3>
            <p>In the quiet town of Eldenwood, there was a clockmaker,<br>
               His clocks were flawless, no room for error.<br>
               But hidden within, a secret so grand,<br>
               A tale of time, and a master’s hand.</p>
        </div>
    </section>
    <footer>
        <p>© 2025 The Echoed Tales</p>
    </footer>  
     <script>
    document.querySelector("input[type='text']").addEventListener("keyup", function (event) {
        if (event.key === "Enter") {
            let query = this.value.toLowerCase();
            // Navigate to sections
            if (query.includes("home")) {
                location.href = "#home";
            } else if (query.includes("about")) {
                location.href = "#about";
            } else if (query.includes("poems")) {
                location.href = "#poems";
            } else if (query.includes("stories")) {
                location.href = "#stories";
            }
            // Navigate to specific poems
            else if (query.includes("whispering") || query.includes("winds")) {
                alert("Navigating to 'The Whispering Winds'... Scroll down to Poems section!");
                location.href = "#poems";
            } else if (query.includes("starlit") || query.includes("dreams")) {
                alert("Navigating to 'Starlit Dreams'... Scroll down to Poems section!");
                location.href = "#poems";
            }
            // Navigate to specific stories
            else if (query.includes("enchanted") || query.includes("forest")) {
                alert("Navigating to 'The Enchanted Forest'... Scroll down to Stories section!");
                location.href = "#stories";
            } else if (query.includes("clockmaker") || query.includes("secret")) {
                alert("Navigating to 'The Clockmaker's Secret'... Scroll down to Stories section!");
                location.href = "#stories";
            } 
            // Handle unknown queries
            else {
                alert("Sorry, I couldn't find what you're looking for. Try searching for 'Home', 'About', 'Poems', 'Stories', or specific titles like 'The Whispering Winds'.");
            }
        }
    });
</script>
  
    </body>
</html>
