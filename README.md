Smart Crop for WideImage
====================

Smart Crop is a function helper for WideImage to make easy crop and resize based on the picture size and resolution.

Info
====================

Version: 1.0    
Author: Mark Topper [[Facebook]](https://www.facebook.com/marktopper) [[Github]](https://github.com/marktopper) [[Twitter]](https://www.twitter.com/webmanio/)    
Website: [www.webman.io](https://www.webman.io/smartcrop)   
Email: [mark@webman.io](mailto:mark@webman.io)


Usage (with Composer)
====================

Simple add `"borter/smartcrop": "1.*"` to the `require`-section in your `composer.json`-file and run `composer update`.


Usage (without Composer)
====================

1. Include ["WideImage Library"](http://wideimage.sourceforge.net/)
2. Include ["function.smartcrop.php"](https://github.com/marktopper/Smart-Crop-WideImage/blob/master/function.smartcrop.php)
3. You are ready to [use the function](#function-usage)


Function Usage
====================

##### Simple Usage
`smart_crop('path/to/file.jpg');`    
This will simple take the file `'path/to/file.jpg'` and smart crop it to 100px X 100px and save it as the same.


##### Save As
`smart_crop('path/to/file.jpg','new/path/to/file.jpg');`    
This will simple take the file `'path/to/file.jpg'` and smart crop it to 100px X 100px and save it as `'new/path/to/file.jpg'`.


##### Custom Size
`smart_crop('path/to/file.jpg','new/path/to/file.jpg',200,150);`    
This will simple take the file `'path/to/file.jpg'` and smart crop it to `200`px (width) X `150`px (height) and save it as `'new/path/to/file.jpg'`.


Why using SmartCrop?
====================

Instead of using only WideImage to crop and resize your images, which even resize it and losses the resolution, or crop out to much of the picture. Then SmartCrop resize and crops the image to get most out of it in a single line of code.

##### Examples

| Original Picture | WideImage's Crop | Smart Crop |
| :-------------: | :-------------: | :-------------: |
| ![Original Image](https://webman.io/static-content/original-image.jpg "Original Image") | ![WideImage's Crop](https://webman.io/static-content/wideimage-crop.jpg "WideImage's Crop") | ![Smart Crop](https://webman.io/static-content/smartcrop-crop.jpg "Smart Crop") |
| size: 300px X 450px | Size: 100px X 100px | size: 100px X 100px |


Support
====================

Please report bugs here on github    
You can contact me on [mail@webman.io](mailto:mail@webman.io)



Thanks to
====================
- [Matteo](https://github.com/matteomartinelli) - Important bug fix
