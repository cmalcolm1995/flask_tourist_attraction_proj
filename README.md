# flask_tourist_attraction_proj
Code Academy Flask - Tourist Attraction project
COmpleted on the 16th May 2021

Project focuses on how to use Jinja2 Forms and Templates

-Variable Filters-
<!-- Capitalize the string -->
<h1>{{ heading_var | upper  }}</h1>
 
<!-- Default string when 
no_var not declared -->
<h1>{{ no_var | default("My Website") }}</h1>

-If Statements-
<html>
  <body>
    <h1>
      {% if template_feel == 'happy' %}
        This Page Is Happy
      {% elif template_feel == 'sad' %}
        This Page Is Sad
      {% else %}
        This Page Is Not Sure How It Feels
      {% endif %}
    </h1>
  </body>
</html>

-For Loops-
<ul>
  {% for content_item in content_list %}
    <li>content_item</li>
  {% endfor %}
</ul>
