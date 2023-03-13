<div class="usa-accordion">
    {% for item in site.data.contentful.spaces.assessment-report-page.chapters_list.chaptersList[0].chapters %}
        <h4 class="usa-accordion__heading">
            <button
            class="usa-accordion__button"
            aria-expanded="false"
            aria-controls="c-a{{forloop.index}}"
            >
                {{ item.chapter }}
            </button>
        </h4>
        <div id="c-a{{forloop.index}}" class="usa-accordion__content usa-prose">
            <p>
                {{ item.content | markdownify }}
            </p>
        </div>
    {% endfor %}
</div>