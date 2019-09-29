---
layout: page
title: Members
description: The individuals and organizations that make us, us.
nav-menu: true
image: 
menu-order: 50
show_tile: false
published: true
---

<!-- Main -->
<div id="main" class="alt">

    <!-- One -->
    <section id="one">
        <div class="inner">
            <header class="major">
                <h1>{{ page.title }}</h1>
            </header>

<h2>An (incomplete) list of supporters</h2>
{% for member in site.members %}
  <h3>{{ member.name }}</h3>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}




        </div>
    </section>
</div>