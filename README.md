Smart-Crop-WideImage
====================

Smart Crop is a function helper for WideImage to make easy crop and resize based on the picture size and resolution.

Info
====================

Version: 1.0    
Author: Mark Topper    
Website: www.webman.io

Usage
====================

- Include "WideImage Library"
- Include "function.smartcrop.php"
- You are ready to use the function

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

| Original Picture | WideImage's Crop | SmartCrop |
| ------------- |:-------------:| -----:|
| ![Original Image](http://webman.io/github_sources/Smart-Crop-WideImage/readme.md/images/original.jpg "Original Image") | ![WideImage's Crop](http://webman.io/github_sources/Smart-Crop-WideImage/readme.md/images/wideimage-crop.jpg "WideImage's Crop") | ![SmartCrop](http://webman.io/github_sources/Smart-Crop-WideImage/readme.md/images/smartcrop-crop.jpg "SmartCrop") |
| size: 300px X 450px | Size: 100px X 100px | size: 100px X 100px |


Support
====================

Please report bugs here on github    
You can contact me on mail@webman.io
