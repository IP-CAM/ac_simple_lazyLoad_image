# AC LazyLoadImage.js

Hello, this is my plugin to lazy load image on div and image. I use it to load image for diferent screen resolution.

# how it use

### JS
inlude acLazyLoadImage.js file after jquery

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="acLazyLoadImage.js"></script>

after this execute script

    $( ".img_lazy" ).ImgLazyLoad();

### html tag's

**for one image**

    <div class="img_lazy" data-src="ImageUrlHere"></div>

data-src attributes is required

**few resources**

    <div class="img_lazy" data-src="ImageUrlHere" data-src-small="ImageSmallUrlHere" data-src-big="ImageBigUrlHere"></div>

**img tag**

you can use on image element

    <img class="img_lazy" data-src="ImageUrlHere">

or 

    <img class="img_lazy" data-src="ImageUrlHere" data-src-small="ImageSmallUrlHere" data-src-big="ImageBigUrlHere">

### Options

    $( ".img_lazy" ).ImgLazyLoad({
        mobile: "640", 
        qhd:"1680", 
        offset:"-150", 
        time:"250"
      });

 - mobile: is maximum width which small image is loaded
 - qhd: is minimum width which big image is loaded 
 - offset: pixels in front of element before plugin load image 
 - time: interval time which function check visible elements



## Licence

**MIT** and I will be happy if it will be useful :)

[My homepage](http://tox.ovh)

