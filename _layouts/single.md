---
layout: default
---

<nav>
        <ul class="nav-links">
            <li><a href="/" {% if page.title == "Home" %}class="active-page"{% endif %}>Home</a></li>
                <li><a href="/research" {% if page.title == "Research" %}class="active-page"{% endif %}>Research</a></li>
            <li><a href="/about" {% if page.title == "About" %}class="active-page"{% endif %}>About</a></li>
                <li><a href="/CV" {% if page.title == "CV" %}class="active-page"{% endif %}>CV</a></li>
        </ul>
    </nav>
    <main class="page-content">
        {{ content }}
          
  
