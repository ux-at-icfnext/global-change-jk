
<ul class="usa-card-group">
  {% for card in page.cards %}
    <li class="usa-card">
      <div class="usa-card__container">
        <div class="usa-card__header">
          <h3 class="usa-card__heading">{{card.title}}</h3>
        </div>
        {% if card.img %}
            <div class="usa-card__media {{card.media-class}}">
                <div class="usa-card__img">
                <img
                    src="{{card.img}}"
                    alt="{{card.alt}}"
                />
                </div>
            </div>
        {% endif %}
      <div class="usa-card__body">
        <p>
            <small>{{card.date}} | {{card.time}}</small>
        </p>
      </div>
      <div class="usa-card__footer">
        <a href="">{{card.label}}</a>
        <br>
        <a href="">{{card.download}}</a>
      </div>
    </div>
  </li>
  {% endfor %}
</ul>
