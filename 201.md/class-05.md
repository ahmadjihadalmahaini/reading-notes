# read05
# HTML 
# 1- Images :
## Q: X How to add images to pages
## We have seen how to create hypertext link using text and we also learnt how to use images in our webpages. Now, we will learn how to use images to create hyperlinks.

## Example
## It's simple to use an image as hyperlink. We just need to use an image inside hyperlink at the place of text as shown below −
### <!DOCTYPE html>
### <html>

   ### <head>
  ### <title>Image Hyperlink Example</title>
   ### </head>
	
   ### <body>
### <p>Click following link</p>
###   <a href = "https://www.tutorialspoint.com" target = "_self"> 
###      <img src = "/images/logo.png" alt = "Tutorials Point" border = "0"/> 
###  </a>
  ### </body>
	
### </html>
## This will produce the following result, where you can click on the images to reach to the home page of Tutorials Point.
## This was the simplest way of creating hyperlinks using images. Next we will see how we can create Mouse-Sensitive Image Links.
## Mouse-Sensitive Images
## he HTML and XHTML standards provides a feature that lets you embed many different links inside a single image. You can create different links on the single image based on different coordinates available on the image. Once different links are attached to different coordinates, we can click different parts of the image to open target documents. Such mouse-sensitive images are known as image maps.

## There are two ways to create image maps −
# ![](https://www.wikihow.com/images/thumb/d/dc/Insert-Images-with-HTML-Step-5-Version-5.jpg/v4-460px-Insert-Images-with-HTML-Step-5-Version-5.jpg.webp)
## Server-side image maps − This is enabled by the ismap attribute of the <img> tag and requires access to a server and related image-map processing applications.

## Client-side image maps − This is created with the usemap attribute of the <img> tag, along with corresponding <map> and <area> tags.

## Server-Side Image Maps
## Here you simply put your image inside a hyper link and use ismap attribute which makes it special image and when the user clicks some place within the image, the browser passes the coordinates of the mouse pointer along with the URL specified in the <a> tag to the web server. The server uses the mouse-pointer coordinates to determine which document to deliver back to the browser.

## When ismap is used, the href attribute of the containing <a> tag must contain the URL of a server application like a cgi or PHP script etc. to process the incoming request based on the passed coordinates.

## The coordinates of the mouse position are screen pixels counted from the upper-left corner of the image, beginning with (0,0). The coordinates, preceded by a question mark, are added to the end of the URL.
## 
## Choosing the right format :
## The very first question you should ask yourself is whether an image is, in fact, required to achieve the effect you are after. Good design is simple and will also always yield the best performance. If you can eliminate an image resource, which often requires a large number of bytes relative to HTML, CSS, JavaScript and other assets on the page, then that is always the best optimization strategy. That said, a well-placed image can also communicate more information than a thousand words, so it is up to you to find that balance.
## If you are sure an image is the correct option, you should carefully select the right kind of image for the job.
## Each format has its own set of pros and cons. Vector formats are ideally suited for images that consist of simple geometric shapes such as logos, text, or icons. They deliver sharp results at every resolution and zoom setting, which makes them an ideal format for high-resolution screens and assets that need to be displayed at varying sizes.
## However, vector formats fall short when the scene is complicated (for example, a photo): the amount of SVG markup to describe all the shapes can be prohibitively high and the output may still not look "photorealistic". When that's the case, that's when you should be using a raster image format such as PNG, JPEG, or WebP.
## Raster images do not have the same nice properties of being resolution or zoom independent —when you scale up a raster image you'll see jagged and blurry graphics. As a result, you may need to save multiple versions of a raster image at various resolutions to deliver the optimal experience to your users
##  Optimizing images for the web :
# ![](https://kinsta.com/wp-content/uploads/2015/11/how-to-optimize-images-for-web-1.png)
## The primary goal of formatting your images is to find the balance between the lowest file size and an acceptable quality. There is more than one way to perform almost all of these optimizations. One of the most popular ways is to simply compress them before uploading to WordPress. Usually, this can be done in a tool like Adobe Photoshop or Affinity Photo. Some of these tasks can also be performed using plugins, which we will go into more below.

## The two primary things to consider are the file format and type of compression you use. By choosing the right combination of file format and compression type you can reduce your image size by as much as 5 times. You’ll have to experiment with each image or file format to see what works best.

## Choose the Right File Format
## Before you start modifying your images, make sure you’ve chosen the best file type. There are several types of files you can use:

## PNG – produces higher quality images, but also has a larger file size. Was created as a lossless image format, although it can also be lossy.
## JPEG – uses lossy and lossless optimization. You can adjust the quality level for a good balance of quality and file size.
## GIF – only uses 256 colors. It’s the best choice for animated images. It only uses lossless compression.
## There are several others, such as JPEG XR and WebP, but they’re not universally supported by all browsers. Ideally, you should use JPEG or JPG for images with lots of color and PNG for simple images.
## (Suggested reading: JPG vs JPEG: Understanding the Most Common Image File Format)
## 
# Color :
##  How to specify colors

## How to Change Text Color in Html
## In HTML, we can change the color of any text using the following different ways:

## Using HTML tag
## Using an Inline style attribute
## Using internal CSS
## Using HTML tag
## Note: HTML 5 does not support the color attribute of font, so we have to use the inline style attribute and internal CSS options for changing the color of a text.
## If we want to change the color of a text using Html tag which is to be displayed on a web page, we have to follow the steps which are given below. Using these steps, we can easily change the color of any text:


## Step 1: Firstly, we have to type the Html code in any text editor or open the existing Html file in the text editor in which we want to use the Html tag.
## Step 2: Now, move the cursor at the starting of that text whose color we want to change. And then, type the empty Html <font> tag at that position.
## Html <font> tag at that position.
## <font> Single Line text and statements  
## Step 3: Then, we have to close the font tag at the end of the text whose color we want to change.
## <font> Single Line text and statements </font>  

## Step 4: Now, we have to add the attribute of the font tag whose name is "color". So, type the color attribute within the starting <font> tag. And, then we have to give the color which we want to use on the text. So, type the name of color in the color attribute as described in the following block.


## Step 5: And, at last, we have to save the Html code in the text editor and run the code. After execution, we will see the output in the browser. The following screenshot shows the output of the above Html Code:



## Background Color
## The CSS background-color property defines the background color for an HTML element.
## Text Color
## The CSS color property defines the text color for an HTML element:
## <h1 style="color:blue;">This is a heading</h1>
## <p style="color:red;">This is a paragraph.</p>
## Fonts
## The CSS font-family property defines the font to be used for an HTML element:
## <h1 style="font-family:verdana;">This is a heading</h1>
## <p style="font-family:courier;">This is a paragraph.</p>
## Text Size
## The CSS font-size property defines the text size for an HTML element:
## Text Alignment
## The CSS text-align property defines the horizontal text alignment for an HTML element:
## <h1 style="text-align:center;">Centered Heading</h1>
## <p style="text-align:center;">Centered paragraph.</p>

# JPEG vs PNG vs GIF — which image format to use and when? :
## TL;DR
## Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.
## JPEG is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. Because JPEG compression works by averaging out colours of nearby pixels (read Discrete Cosine Transform), JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good results.
## PNG is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.
## GIF is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.
##