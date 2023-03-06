<div class="grid-row grid-gap">
  <div class="tablet:grid-col-6">
    <h3 class="site-preview-heading tablet:margin-top-0">Announcement Collection</h3>
    <ul class="usa-collection annnouncement">
    {%for item in page.announcements%}
      <li class="usa-collection__item announcement-wrapper">
        <img
        class="usa-collection__img"
        src="/assets/images/announcement_collection.png"
        alt="Iowa_wind"
        />
        <div class="usa-collection__body">
            <div class="announcement-header">
                <h3 class="usa-collection__heading">
                    <a
                    class="usa-link"
                    href="https://trumpadministration.archives.performance.gov/presidents-winners-press-release/">
                    Gears of Government President’s Award winners
                    </a>
                </h3>
                <span>March 2, 2023</span>
            </div>
          <p class="author">Author Sondra Ainsworth and Constance Lu</p>
          <p class="usa-collection__description">
            Today, the Administration announces the winners of the Gears of
            Government President’s Award. This program recognizes the contributions
            of individuals and teams across the federal workforce who make a
            profound difference in the lives of the American people.
          </p>
          <a href="" class="announcement-link">Continue Reading</a><i class="fa-solid fa-arrow-right"></i>
        </div>
      </li>
    {%endfor%}
    </ul>
  </div>
</div>