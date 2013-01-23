Front-End Standard
==================

Contributors
============

EragonJ

Mitch Chen

photoframe
-

photoframe is a jquery widget can makes image into photo frame by wrapping a `DIV` element 

Using
-
photoframe only accepted ` image ` is a object.

@sample
```javascript
    var $img = $("<img>");
```    
    
@param      

  - **{ object }** : optations
  - **{ number }** options.frameWidth Width of photo frame
  - **{ number }** options.frameHeight Height of photo frame
  - **{ string }** options.wrapperClass Class name for photo frame
  - **{ string | number }** options.scale `number` `lettetBox` `zoomEven` `zoomStretch` `none`  

`number` : Both width and height of photo will scale with the value.
     
`letter` : uniformly scales up content as much as possible, while still showing all content on the screen.

`zoomEven` : uniformly scales up content to fill the screen, while preserving aspect ratio. Some content may appear offscreen.

`zoomStretch` : non-uniformly scales up content to fill the screen. All content will remain onscren, but it may be stretched vertically or horizontally.

`none` : No scalling.

@example

```javascript
    $('.Selector').photoFrame({
        frameWidth: 140,  // width of photo frame
		frameHeight: 140, //Height of photo frame
		scale: "zoomEven" //scale
    });
```

Tech
-----------

photoframe uses these open source projects to work properly:

* [jQuery] 


  [jQuery]: http://jquery.com  
  
Version
-

1.0

