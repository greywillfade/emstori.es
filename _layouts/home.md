---
title: Home
---

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ title }}</title>
  </head>
  <body>
    <header>
        <a href="/">EM stories</a>
        <nav aria-label="Primary navigaton">
            <ul>
                <li><a href="/">Stories</a></li>
                <li><a href="/about/">About</a></li>
                <li><a href="/contact/">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        {{ content }}
    </main>
    <footer>Stories by Sally</footer>
  </body>
</html>