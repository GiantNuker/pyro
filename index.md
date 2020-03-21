---
description: The addon client focused on quality before quantity<span style="font-size:0.3rem">(guess why we only have 1 hack lmao)</span>
---

### Modules
<ul>
{% for module in site.data.modules.active %}
<li>
    <h4>{{ module.name }}</h4>
    <ul>
    {% for feature in module.features %}
        <li>
            <p>{{ feature }}</p>
        </li>
    {% endfor %}
    <a href="modules/{{ module.id }}.html"><h4>Details</h4></a>
    </ul>
</li>
{%endfor%}
</ul>

### Status
Pyro is currently undergoing a closed beta test, and will continue to be closed until a lisencing system is implemented and obfuscation is added.