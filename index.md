---
title: Home
layout: main
---
# Hi there! 👋 
heya! I am **Sunnville**, also sometimes known as **Sunn** or **sunn.ia32**! just a gateway for me to the internet, hope you enjoy! :3

# Projects
    {% for project in site.data.projects %}
<div class="card">
    <div class="card-image">
        <img src="./img/projects/{{ project.logo }}.svg">
    </div>
    <div class="card-content">
        <h2 style="margin-bottom: 0;">{{ project.name }}</h2>
        <span style="text-transform: capitalize;">{{ project.type }}</span>
        <p>{{ project.desc }}</p>
        <a class="button" href="{{ project.btn_link }}">{{ project.btn_name }}</a>
    </div>
</div>
    {% endfor %}

# Find me on...
* **Discord** - `sunnville`
* **Discord Server** - [Lynxmic][1]
* **Fediverse** - <a rel="me" href="https://wetdry.world/@sunn">@sunn@wetdry.world</a>
* **YouTube** - [Sunnville][2]
* **GitHub** - [sunn-ia32][3]

---

[1]: https://discord.gg/wDxDKJU2sj
[2]: https://youtube.com/@sunn.ia32
[3]: https://github.com/sunn-ia32
