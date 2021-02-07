# EasySlides.js

## Getting Started
 * Clone the repo
 ```
 git clone csc309-fall-2020/js-library-xutian14
 ```
 * Imporint JS
First, import the main javascript (in pub/lib/) by using <script> tag
 ```
  <script src="easyslides.js"></script>
  <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
 ```
 * Importing CSS
 Second, link the style sheet (in pub/lib/) with \<link\> element
 ```
  <link rel="stylesheet" ref="easyslides.css"></link>
 ```
 
 * Writing HTML
 
 ```
 <div class="easyslides"> 
   <div class="easyslides-cell"> ... </div>
   <div class="easyslides-cell"> ... </div>
   <div class="easyslides-cell"> ... </div>
 </div>
 ```
 * Applying EasySlides
 ```
  const options = {} // define your slider options here
  const slides = document.querySelector('.easyslides');
  const easySlides = new EasySlides(slides, options);
 ```

## APIs
https://protected-shore-59731.herokuapp.com/html/api.html


## Landing Page
 https://protected-shore-59731.herokuapp.com/
