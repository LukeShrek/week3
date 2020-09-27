<!DOCTYPE html>
<html>
  <head>
    <title>Web development</title>
    <link rel="stylesheet" href={{ "/style.css" | relative_url}}>
  </head>

  <body>
    {% include navbar.md %} 
    {% include sidebar.md side=page.side nav=page.nav %}
    {{ content }}
  </body>
</html>
