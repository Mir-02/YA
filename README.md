<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Youth Advocates</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #FF9900; /* Orange */
            color: #333; /* Dark Gray */
        }

        header {
            background: #99DFCE; /* Light Blue-Green */
            color: #333; /* Dark Gray */
            text-align: center;
            padding: 2em;
        }

        header img {
            max-width: 100%;
            height: auto;
            border-radius: 50%;
            margin-bottom: 1em;
        }

        nav {
            background: #99DFCE; /* Light Blue-Green */
            padding: 0.5em;
            text-align: center;
        }

        nav a {
            color: #333; /* Dark Gray */
            text-decoration: none;
            padding: 0.5em;
            margin: 0 1em;
            font-weight: bold;
            font-size: 1.2em;
        }

        .tabs {
            display: flex;
            justify-content: space-around;
            margin: 1em 0;
            background-color: #99DFCE; /* Light Blue-Green */
            padding: 0.5em;
        }

        .tab {
            cursor: pointer;
            border-radius: 5px;
            padding: 0.5em 1em;
            transition: background-color 0.3s;
        }

        .tab:hover {
            background-color: #66b9a8; /* Darker Blue-Green on hover */
        }

        section {
            padding: 2em;
            background-color: #fff; /* White */
            margin: 1em 0;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            display: none;
        }

        section h2 {
            color: #FF9900; /* Orange */
        }

        section img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 1em;
        }

        ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        ul li::before {
            content: "▶ ";
            color: #FF9900; /* Orange */
            font-weight: bold;
        }

        .contact-info {
            margin-top: 1em;
        }

        .highlight {
            color: #FF9900; /* Orange */
            font-weight: bold;
        }

        .volunteer-info {
            margin-top: 1em;
        }

        .quote {
            font-style: italic;
            color: #555; /* Gray */
            margin-top: 1em;
        }

        .founder-info {
            margin-top: 2em;
        }

        .founder-info img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 1em;
        }
    </style>
</head>
<body>
    <header>
        <img src="ya_logo_placeholder.png" alt="Youth Advocates Logo">
        <h1>Youth Advocates</h1>
        <p>Empowering young minds for a brighter future.</p>
    </header>

    <nav>
        <a href="#youth-advocates" class="tab">Youth Advocates</a>
        <a href="#dolphin-academy" class="tab">Dolphin Academy</a>
        <a href="#contact" class="tab">Contact</a>
    </nav>

    <div class="tabs">
        <div class="tab" id="youth-advocates-tab">Youth Advocates Programs</div>
        <div class="tab" id="dolphin-academy-tab">Dolphin Academy Programs</div>
    </div>

    <section id="youth-advocates">
        <h2>Youth Advocates Programs</h2>
        <p>At Youth Advocates, our journey began with a simple yet profound vision – to create a community where every young mind is empowered to thrive, regardless of their background or circumstances. It all started in the heart of Louisville, where a group of passionate individuals recognized the need for uplifting the youth.</p>
        <p>The founders, inspired by their own experiences, envisioned a place where after-school hours weren't just idle time but an opportunity for growth. They believed in the potential of every child and saw education as a key to unlock a brighter future.</p>
        <p>With this vision in mind, Youth Advocates formed partnerships with local schools to extend their impact. The programs started modestly, providing academic support and engaging activities. As the community responded with enthusiasm, the organization expanded its offerings, including mentoring initiatives and specialized childcare programs for families in need.</p>
        <p>The heart of Youth Advocates lies in the belief that nurturing young minds goes beyond