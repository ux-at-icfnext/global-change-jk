
{% for tab in page.tabs %}
    {% if tab.type == "big" %}
        <span class="usa-tag usa-tag--big">{{tab.text}}</span>
    {% else %}
        <span class="usa-tag">{{tab.text}}</span>
    {% endif %}
{% endfor %}
