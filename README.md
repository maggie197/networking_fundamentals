# Networking Fundamentals

## This is a presentation describing Networking Fundamentals using the Reveal.js framework (HTML-based slideshow). 

1. Create a GitHub repository

2. Add Reveal.js

Clone the repo:

```
git clone https://github.com/hakimel/reveal.js.git

```

3. Create your presentation HTML

In your repo root, create an index.html:

```
    <!doctype html>
    <html>
    <head>
        <meta charset="utf-8">
        <title>My Reveal.js Presentation</title>
        <link rel="stylesheet" href="https://unpkg.com/reveal.js/dist/reveal.css">
        <link rel="stylesheet" href="https://unpkg.com/reveal.js/dist/theme/black.css">
    </head>
    <body>
        <div class="reveal">
        <div class="slides">
            <section>Welcome to my presentation</section>
            <section>Second Slide</section>
            <section>Thank you!</section>
        </div>
        </div>
        <script src="https://unpkg.com/reveal.js/dist/reveal.js"></script>
        <script>
        Reveal.initialize();
        </script>
    </body>
    </html>

```