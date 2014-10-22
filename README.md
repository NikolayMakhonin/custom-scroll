#Customize your scroollbar

Its a simple, fast, lightweight (~2kB) plugin for jQuery 1.7+
Works fine with all browsers using jQuery.

 \+ Supporting touch, wheel, middle button and any kind of scrolling  
 \+ As fast as native  
 \+ Weight incredible small  

 \- No horizontal scroll support, not sure if anyone using it  


Watch the [example](http://standys.github.io/custom-scroll/) page

 
## Usage
`$('#example').customScroll([options])`



## Documentation
All classes added via plugin has a changable prefix   
`prefix: 'custom-scroll_'`  

Min height for scrollbar  
`barMinHeight: 10`  

Top and bottom offset for scrollbar  
`offsetTop: 0`  
`offsetBottom: 0`  

Replace a scrollbar html on your choice  
`barHtml: '<div />'`  



To remove custom scroll use 'destroy'  
`$(container).customScroll('destroy')`  

## License
[MIT](https://github.com/standys/custom-scroll/blob/master/LICENSE)
