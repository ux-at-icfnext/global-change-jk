<div class="highlight-wrapper">
{%for item in page.highlights %}
  <div class="highlight">
    <div class="highlight-header">
        <h4>{{item.title}}</h4>
    </div>
    <div class="highlight-container"> 
      <img src="https://via.placeholder.com/220">
      <div class="announcement-content">
          <p><a href="{{item.link}}">{{item.title}}</a></p>
          <p>{{item.content}}</p>
          <a href="" class="announcement-link">Read More</a>
          <p><em>By Sondra Ainsworth and Constance Lu</em></p>
          <time>September 20, 1968</time>
      </div>
      <!-- end announcment-content -->
  </div>
<!-- end announcement container -->
</div>
<div class="highlight-tags">
  <ul class="usa-collection__meta" aria-label="Topics" style="margin-left: 0rem;">
      <li class="usa-collection__meta-item usa-tag usa-tag--new">{{item.tags}}</li>
      <li class="usa-collection__meta-item usa-tag">Highlight Tag</li>
      <li class="usa-collection__meta-item usa-tag">Highlight Tag</li>
  </ul>
</div>
<!-- end highlight tags -->
{%endfor%}
</div>
<!-- end announcement-wrapper -->