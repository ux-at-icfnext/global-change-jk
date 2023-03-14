<div class="highlight-wrapper library">
{%for item in page.highlights %}
  <div class="highlight">
    <div class="highlight-header">
        <h4>{{item.title}}</h4>
    </div>
    <div class="highlight-container"> 
      <img src="https://via.placeholder.com/220">
      <div class="announcement-content">
          <p><a href="{{item.url}}">{{item.title}}</a></p>
          <p>{{item.content}}</p>
          <a href="" class="announcement-link">Read More</a>
      </div>
      <!-- end announcment-content -->
  </div>
<!-- end announcement container -->
</div>
<!-- end highlight tags -->
{%endfor%}
</div>
<!-- end announcement-wrapper -->