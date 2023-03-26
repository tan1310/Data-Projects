<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>{{ Tanmay Jain }} | Data Professional</title>
    <link rel="stylesheet" href="{{ "/assets/css/main.css" | relative_url }}">
  </head>
  <body>
    <header>
      <h1>My Data Portfolio</h1>
      <nav>
        <ul>
          {% for page in site.pages %}
            <li><a href="https://github.com/tan1310/Data-Projects/blob/main/BABS%20502_Final_Tanmay.ipynb">{{ Machine Learning Project}}</a></li>
          {% endfor %}
        </ul>
      </nav>
    </header>
    <main>
      {{ content }}
    </main>
    <footer>
      <p>&copy; 2023 Tanmay Jain</p>
    </footer>
  </body>
</html>



