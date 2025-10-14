---
# Leave the homepage title empty to use the site title
title:
date: 2025-02-07
type: landing

sections:
  - block: markdown
    content:
      title: |
        Welcome to the Boreal-Arctic Biogeochemistry Lab!
      text: |
        <center> The BAB Lab is located in the University of British Columbia’s Geography Department, which we respectfully acknowledge exists on the traditional, ancestral, and unceded territories of the hən̓q̓əmin̓əm̓-speaking xʷməθkʷəy̓əm (Musqueam) people, the Halq'eméylem speaking Coast Salish people, including the Sto:lo and the Seabird Island First Nations.</center>
        <br>
        <center> We are broadly interested in better understanding the impacts of climate warming and human disturbances on carbon and nutrient cycling in boreal-Arctic terrestrial and aquatic ecosystems. Our research group draws on principles and approaches from physical geography including environmental chemistry, earth sciences, geographical sciences, hydrology, limnology, microbiology, and ecology. </center>
        <center> {{< figure src="icon-whitelet.png" >}} </center> 
        <center> *Our beautiful logo made by our lab designer extraordinaire, Lyreshka! </center> 
    design:
      background:
        text_color_light: true
        image:
          filename: wildflower-lake.jpg
          filters: 
            brightness: 0.5
          size: cover
          position: center
          parallax: true
  - block: markdown
    content:
      title: Photos from the Field! 
      text: |
        <div class="photo-gallery">
          <img src="/images/field/IMG_1370.jpeg" alt="Field photo 1" />
          <img src="/images/field/IMG_1473.jpeg" alt="Field photo 2" />
          <img src="/images/field/IMG_1501.jpeg" alt="Field photo 3" />
          <img src="/images/field/IMG_1691.jpeg" alt="Field photo 4" />
          <img src="/images/field/IMG_6255.jpeg" alt="Field photo 5" />
        </div>
    spacing:
        padding: ["0", "0", "0", "0"]   
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
    spacing:
        padding: ["0", "0", "0", "0"]
---
