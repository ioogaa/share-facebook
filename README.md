# Documentation How to make facebook share

<h3> Share a web url with simple script: </h3>
``` <a href="https://www.facebook.com/sharer/sharer.php?u=http://example.com">share</a> ```

<h3> Some point that we need to give attention: </h3>
1. Please make sure the url that we share is online
2. Give meta tag so when we share on our facebook page show image/description about the content. When we share our page, facebook will read that meta tag. Documentation about the meta can be found in http://ogp.me/

<h3> Good Examples of og meta tag: </h3>

<h4> Title </h4>
A clear title without branding or mentioning the domain itself.

``` <meta property="og:title" content="Workday Sets Price Range for I.P.O." /> ```
<h4>Site name</h4>
Provide a site name, e.g. "My Favorite News"
``` <meta property="og:site_name" content="My Favorite News"/> ```
<h4>URL</h4>
A URL with no session id or extraneous parameters. All shares on Facebook will use this as the identifying URL for this article.
``` <meta property="og:url" content="http://www.example.com/article" /> ```
<h4>Description</h4>
A clear description, at least two sentences long.
``` <meta property="og:description" content="This is a description that we share to other. This is long long description about something." /> ```

<h4>Facebook App ID</h4>
A Facebook App ID that identifies your website to Facebook. Not mandatory if we dont have it.
``` <meta property="fb:app_id" content="[FB_APP_ID]" />```

<h4>Object Type</h4>
The type of object:

``` <meta property="og:type" content="article" /> ```
more complete documentation can be found here ```https://developers.facebook.com/docs/reference/opengraph/```

<h4>Author and Publisher</h4>
This article has an author and a publisher:
``` <meta property="article:author" content="https://www.facebook.com/fareedzakaria" />
<meta property="article:publisher" content="https://www.facebook.com/cnn" /> ```


<h3> Debug tools</h3>
When our page have been shared at least once, facebook will catch our page and save the cache so when we reshare our page we will see the page as same as the first time shared even we has make change in our page. To reload the view we can use debuging tools provided by facebook in ``` https://developers.facebook.com/tools/debug/ ```

<h3>Image Sizes</h3>

Use images that are at least 1200 x 630 pixels for the best display on high resolution devices. At the minimum, you should use images that are 600 x 315 pixels to display link page posts with larger images.

<h4>Small Images</h4>

If your image is smaller than 600 x 315 px, it will still display in the link page post, but the size will be much smaller.


We've also redesigned link page posts so that the aspect ratio for images is the same across desktop and mobile News Feed. Try to keep your images as close to 1.91:1 aspect ratio as possible to display the full image in News Feed without any cropping.

<h4>Minimum Image Size</h4>

The minimum image size is 200 x 200 pixels. If you try to use an image smaller than this you will see an error in the URL Debugger.
