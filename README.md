# V School - The Coding Bootcamp Primer Course 

## Assignment 5 - CSS Flags

https://coursework.vschool.io/css-flags/

### Instructions

Build the following flags in pure HTML and CSS, no images allowed. No need to make them responsive. The "aspect ratios" listed below refer to the height:width aspects. E.g. France 🇫🇷 is 2:3, so if you make it 200px in height, it should be 300px in width. With Germany 🇩🇪 (3:5), 200px height would be 333px in width (200px × 5 ÷ 3 = 333.3333px).


#### Required

  1.  France - Blue: #002495, White: #FFFFFF, Red: #ED2938, Aspect Ratio: 2:3

  2.  Germany - Black: #000000, Red: #DE0002, Yellow: #FFCE00, Aspect Ratio: 3:5 

  3.  Madagascar - White: #FFFFFF, Red: #FC3E32, Green: #007E39, Aspect Ratio: 2:3

  4.  Switzerland - White: #FFFFFF, Red: #FF0002, Aspect Ratio: 1:1 

  5.  Sweden - Blue: #0269A6, Yellow: #FECC00, Aspect Ratio: 5:8 

  6.  Gambia - Red: #CE1127, White: #FFFFFF, Blue: #0D1D8B, Green: #3B7827, Aspect Ratio: 2:3 

  7.  Japan - White: #FFFFFF, Red: #BC022C, Aspect Ratio: 2:3 

  8.  Niger - Orange: #E15307, White: #FFFFFF, Green: #10AF2A, Aspect Ratio: 6:7 

  9.  Belize (just kidding)



#### Extra challenge

Only do these if you felt like the required ones were pretty easy. If you struggled with the required ones, don't let these ones hold you back from moving forward in the curriculum.

  10.  Tonga - Red: #C20002, White: #FFFFFF, Aspect Ratio: 1:2 

  11.  Greece - White: #FFFFFF, Blue: #0E5FAE, Aspect Ratio: 2:3

  12.  Maldives - Red: #D31133, Green: #007E39, White: #FFFFFF, Aspect Ratio: 2:3



### Problem Solving

Each flag is easiest organized in code as a container with children. Nesting divs is a common HTML practice.

<div class="container">
    <div class="color-one"></div>
    <div class="color-two"></div>
</div>

Use the <strong>position</strong> css property as a last resort. Width, height, and nesting your elements thoughtfully will get you a long way.

<strong>display: inline-block</strong> will be important to give to elements you are trying to control the width of.

