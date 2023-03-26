<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>{{ page.title }} | My GitHub Pages Site</title>
    <link rel="stylesheet" href="{{ "/assets/css/main.css" | relative_url }}">
  </head>
  <body>
    <header>
      <h1>My GitHub Pages Site</h1>
      <nav>
        <ul>
          {% for page in site.pages %}
            <li><a href="{{ page.url }}">{{ page.title }}</a></li>
          {% endfor %}
        </ul>
      </nav>
    </header>
    <main>
      {{ content }}
    </main>
    <footer>
      <p>&copy; 2023 John Doe</p>
    </footer>
  </body>
</html>



