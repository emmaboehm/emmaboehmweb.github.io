---
layout: default
---

<nav>
        <ul class="nav-links">
            <li><a href="/" {% if page.title == "Home" %}class="active-page"{% endif %}>Home</a></li>
            <li><a href="/about" {% if page.title == "About" %}class="active-page"{% endif %}>About</a></li>
        </ul>
    </nav>
    <main class="page-content">
        {{ content }}
          
  
