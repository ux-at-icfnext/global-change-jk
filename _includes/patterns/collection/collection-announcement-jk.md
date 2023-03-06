<div class="grid-row grid-gap">
  <div class="tablet:grid-col-6">
    <h3 class="site-preview-heading tablet:margin-top-0">Announcement Collection</h3>
    <ul class="usa-collection annnouncement">
    {%for item in page.announcements%}
      <li class="usa-collection__item announcement-wrapper">
      {%if item.img %}
        <img
        class="usa-collection__img"
        src="{{item.img}}"
        alt="{{item.alt}}"
        />
        {%else%}
        <img class="usa-collection__img">
        {%endif%}
        <div class="usa-collection__body">
            <div class="announcement-header">
                <h3 class="usa-collection__heading">
                    <a
                    class="usa-link"
                    href="{{item.href}}">
                    {{item.title}}
                    </a>
                </h3>
                <span>{{item.date}}</span>
            </div>
          <p class="author">Author {{item.author}}</p>
          <p class="usa-collection__description">
            {{item.content}}
          </p>
          <a href="" class="announcement-link">Continue Reading</a><i class="fa-solid fa-arrow-right"></i>
        </div>
      </li>
    {%endfor%}
    </ul>
  </div>
</div>