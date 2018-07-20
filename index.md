---
layout: default
title: Home
featured-image: images/illustrated_skyline.jpg
---

<header>
<h1>This city is a web of lives, tangled</h1>
    {% if page.featured-image %}
    <span class="image main">
      <img src="{{ page.featured-image }}" alt="Illustration of a city skyline at night">
    </span> {% endif %}
<p>Etiam quis viverra lorem, in semper lorem. Sed nisl arcu euismod sit amet nisi euismod sed cursus arcu elementum ipsum arcu vivamus quis venenatis orci lorem ipsum et magna feugiat veroeros aliquam. Lorem ipsum dolor sit amet nullam dolore.</p>
</header>

{% include tiles.html %}
