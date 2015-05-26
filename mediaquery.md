[Responsive Web Design](http://alistapart.com/article/responsive-web-design)   
#### Images   
#### px => %   
````css
.main {
  width: 60%; // 600px / 1000px
}
````
#### Media query    
````html
<link rel="stylesheet" media="(max-width: 800px)" href="example.css" />
````
````css
@media (max-width: 600px) {
  .facet_sidebar {
    display: none;
  }
}
@media all and (min-width: 600px) {
  .main {
    width: 80%;
  }
}
````
[media query](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Media_queries)    
[respond.js](https://github.com/scottjehl/Respond)   