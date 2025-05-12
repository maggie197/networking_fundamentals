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
    <title>CDN Reveal.js Presentation</title>
    <!-- Stylesheets loaded from CDN -->
    <link rel="stylesheet" href="https://unpkg.com/reveal.js/dist/reveal.css">
    <link rel="stylesheet" href="https://unpkg.com/reveal.js/dist/theme/black.css">
  </head>
  <body>
    <div class="reveal">
      <div class="slides">
        <section>Welcome to my presentation</section>
        <section>Next slide</section>
        <section>Thank you!</section>
      </div>
    </div>

    <!-- Scripts loaded from CDN -->
    <script src="https://unpkg.com/reveal.js/dist/reveal.js"></script>
    <script>
      Reveal.initialize();
    </script>
  </body>
</html>

```

4. Push to GitHub

5. Enable GitHub Pages:
    1. Open "Settings" → "Pages"
    2. Configure GitHub Pages
    Under "Build and deployment":
        * Source: Choose Deploy from a branch
        * Branch: Select main
        * Folder: Choose / (root) (or /docs if that's where your files are)
        * Save

6. Get the URL
Once it's deployed, a green banner will appear saying:

Your site is live at: https://yourusername.github.io/presentation-demo/