<div class="usa-accordion">
    {% for item in site.data.contentful.spaces.assessment-report.assessmentReport[0].fa_qs[0].list %}
        <h4 class="usa-accordion__heading">
            <button
            class="usa-accordion__button"
            aria-expanded="false"
            aria-controls="a{{forloop.index}}"
            >
                {{ item.label }}
            </button>
        </h4>
        <div id="a{{forloop.index}}" class="usa-accordion__content usa-prose">
            <p>
                {{ item.content | markdownify }}
            </p>
        </div>
    {% endfor %}
</div>