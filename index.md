---
title: Home
layout: main
---
# Hi there! 👋 
heya! I am **Clyron**! just a gateway for me to the internet, hope you enjoy! :3

*This is a temporary website, a permanent iteration is being worked on. Site will also migrate soon to different address.*

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
* **Discord** - `clyron.tar.gz`
* **Discord Server** - [LynxPlaza][1] (server for the Lynxmic YT channel)
* **Fediverse** - <a rel="me" href="https://wetdry.world/@sunn">@sunn@wetdry.world</a>
* **YouTube** - [Clyron][2]
* **GitHub** - [theclyron][3]

---

[1]: https://discord.gg/wDxDKJU2sj
[2]: https://youtube.com/@Clyron
[3]: https://github.com/theclyron
