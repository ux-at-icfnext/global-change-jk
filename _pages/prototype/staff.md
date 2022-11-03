---
layout: left-rail
categories: [prototype]
title: Staff
type: [sub-nav-item, prototype]
permalink: /prototype/staff/
description: Shows the staff the structure of the organization

cards:
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member  
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member  
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member  
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member  
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member  
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 
 - title: Staff Member Name
   content: staff member title   
   img: /assets/customImages/placeimg_320_200_grayscale_nature.jpg
   alt: an image of a staff member 

---



<ul class="usa-card-group">
  {% for card in page.cards %}
    <li class="usa-card tablet:grid-col-3">
      <div class="usa-card__container">
        <div class="usa-card__header">
          <a href=""><h2 class="usa-card__heading">{{card.title}}</h2></a>
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
    </div>
  </li>
  {% endfor %}
</ul>



