WebSite Challenges
You will make multiple website layouts that follow certain rules. The content is not important. I am looking to see if you can arrange the HTML and CSS correctly.

Challenge 1
This is a plain website, think about the 5 paragraph essay: A header, a footer, and 3 supporting paragraphs.

--|body
  |----header
  |----section
  |----section
  |----section
  |----footer
The header and the footer should each be 500px wide and 300 pixels tall. Keep is simple, make the color for the header gray and the color of the footer black.
Each section should have the same width but a height of 100 pixels. Choose 3 different background colors. Keep it simple, choose the rainbow.
Challenge 2
This website is a "tiled" website. The goal is to use the floats and percents properly.

--|body
  |----header width:100% height:100px background-color:gray

  |----section
      |----div height: 200px width:50% background-color: red
      |----div height: 200px width 50% background-color: blue

  |----section
      |----div height: 200px width 25% background-color: red
      |----div height: 200px width 75% background-color: blue

  |----section
      |----div height: 200px width 66.66% background-color: red
      |----div height: 200px width 33.33% background-color: blue

  |----footer width:100% height:100px background-color:black
Challenge 3
This website is designed to represent a typical "news feed" like article. This will include a title a picture and a description. You should create 3 of your own articles. Here are some of the css properties that you should use to make it look good.

padding: #px; //this makes sure your words do not touch the edge of your box.
margin: #px; //this makes sure your boxes do not touch each other
border: #px solid black; //has 3 inputs, creates a border around your box.
border-radius: #px; //rounds the corner of your boxes.
--|body
  |
  |----|article  width:400px; padding:8px; border:8px; border-radius:4px;
       |----|h3   margin:0;
       |----|img  width:400px;
       |----|p

  |----|article  same as above
       |----|h3   
       |----|img  
       |----|p

  |----|article  same as above
       |----|h3   
       |----|img  
       |----|p
Challenge 4
The goal here is to copy and paste your c3 content and make it look for like ESPN.

Your layout should be three giant boxes floated to the left
aside 15% width
main 70% width
aside 15% width
All of your code from c3 should be copied into the main box.
Make the body's background-color gray
Fill each aside with tiny divs of the same width ie 100% but give them a margin-bottom property of 32px. Also give each div a background color of your choice but keep them all the same color.
--|body
--|----|section
--|----|----|aside
--|----|----|----|div  //ad
--|----|----|----|div  //ads
--|----|----|----|div  //ads
--|----|----|----|div  //ads

--|----|----|main  //copy from c3

--|----|----|aside
--|----|----|----|div  //ad
--|----|----|----|div  //ads
--|----|----|----|div  //ads
--|----|----|----|div  //ads