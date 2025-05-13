---
# Leave the homepage title empty to use the site title
title:
date: 2025-02-07
type: landing

sections:
  - block: markdown
    content:
      title: |
        Welcome to the Boreal-Arctic Biogeography Lab!
      text: |
        <center> The BAB Lab is located in the University of British Columbia’s Geography Department. </center>
        <br>
        <center> We are broadly interested in better understanding the impacts of climate warming and human disturbances on carbon and nutrient cycling in boreal-Arctic terrestrial and aquatic ecosystems. Our research group draws on principles and approaches from physical geography including environmental chemistry, earth sciences, geographical sciences, hydrology, limnology, microbiology, and ecology. </center>
        <center> {{< figure src="icon-whitelet.png" >}} </center> 
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
        
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
