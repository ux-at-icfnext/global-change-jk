
<ul class="usa-card-group">
  {% for card in page.cards %}
    <li class="usa-card {{page.card-class | default: 'tablet:grid-col-4'}}">
      <div class="usa-card__container">
        <div class="usa-card__header">
          <h2 class="usa-card__heading">{{card.title}}</h2>
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
          {{card.content}}
        </p>
      </div>
      {% if card.button %}
      <div class="usa-card__footer">
        <button class="usa-button">{{card.button}}</button>
      </div>
      {% endif %}
    </div>
  </li>
  {% endfor %}
</ul>
