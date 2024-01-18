 CSS List Properties

    ul.a {
      list-style-type: circle;
    }
    
    ul.b {
      list-style-type: square;
    }
    
    ol.c {
      list-style-type: upper-roman;
    }
    
    ol.d {
      list-style-type: lower-alpha;
    }

CSS Tables

    table, th, td {
       border: 1px solid;
    }

Default Display Value

    li {
    display: inline;
    }

    
position Property

    div.relative {
    position: relative;
    left: 30px;
    border: 3px solid #73AD21;
  }

The z-index Property

    img {
      position: absolute;
      left: 0px;
      top: 0px;
      z-index: -1;
    }
    
CSS Overflow

visible - Default. The overflow is not clipped. The content renders outside the element's box
hidden - The overflow is clipped, and the rest of the content will be invisible
scroll - The overflow is clipped, and a scrollbar is added to see the rest of the content
auto - Similar to scroll, but it adds scrollbars only when necessary

        overflow: visible;
        overflow: hidden;
        overflow: scroll;
        overflow: auto

float and clear

property specifies how an element should float

      float: right;
      float: left;
      float: none;
      
clear

When we use the float property, and we want the next 
element below (not on right or left), we will have to use the clear property.

      clear: left;

      

        
        
        
    



