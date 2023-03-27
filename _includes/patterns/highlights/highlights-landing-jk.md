<div class="announcement-wrapper">
{%for item in page.highlights %}
    <div class="announcement">
        <img src="{{item.img}}"/>
        <div class="announcement-content">
            <div class="announcement-header">
                <h4>{{item.title}}</h4>
                <span>{{item.date}}</span>
            </div>
            <p>{{item.content}}</p>
            <a href="{{item.url}}" class="announcement-link">{{item.link}}</a>
            <p class="highlight-tags">
                <ul class="usa-collection__meta" aria-label="Topics" style="margin-left: 0rem;">
                    <li class="usa-collection__meta-item usa-tag usa-tag--new">{{item.tags}}</li>
                    <li class="usa-collection__meta-item usa-tag">{{item.tags}}</li>
                    <li class="usa-collection__meta-item usa-tag">{{item.tags}}</li>
                </ul>
            </p>
        </div>
    </div>
{%endfor%}
</div>