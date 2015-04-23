# Documentation How to make facebook share

<h3> Share a web url with simple script: </h3>
``` <a href="https://www.facebook.com/sharer/sharer.php?u=http://example.com">share</a> ```

<h3> Some point that we need to give attention: </h3>
1. Please make sure the url that we share is online
2. Give meta tag so when we share on our facebook page show image/description about the content. When we share our page, facebook will read that meta tag. Documentation about the meta can be found in http://ogp.me/

<h3>OpenGraph tags</h3>
Facebook’s OpenGraph allows you to specify metadata to optimize how your content appears in a user’s timeline. The added benefit of using this data is that by creating an “Edge” in Facebook you can obtain some fantastic data about the users checking out your content via Facebook Insights. If you don’t use Open Graph tags Facebook will default to standard metadata.



<h5>og:title</h5>
This is the title of the piece of content. You should use this as a headline that will appeal to the Facebook audience. It is completely ok to use a different title than the one on the actual site as long as the message is ultimately the same. You have 95 characters to work with.Format:<br/>
```<meta property=”og:title” content=”iAcquire’s awesome blog”/>```

<h5>og:type</h5>
This is the type of object your piece of content is. For your purposes it will usually be blog, website or article, but if you want to get fancy Facebook provides a complete list.Format:<br/>
```<meta property=”og:type” content=”article”/>```

<h5>og:image</h5>
This is the image that Facebook will show in the screenshot of the content. Be sure to specify a square image to ensure the best visibility in a user’s timeline. If you don’t specify an image at all you are left to the mercy of the user to pick which image represents your content based on what Facebook can scrape. That is typically not the way to ensure the best first impression.Format:<br/>
```<meta property=”og:image” content=”http://www.example.com/some-thumbnail.jpg”/>```

<h5>og:url</h5>
This is simply the URL of the page (or edge). You should specify this especially if you have duplicate content issues to make sure the value of the edge in Facebook is consolidated into one URL.Format:
```<meta property=”og:url” content=”http://example.com/article-we-share”/>```

<h5>og:description</h5>
This is the description Facebook will show in the screenshot of the piece of content. Just like the standard meta description it should be catchy and contain a call to action, but in this case you have nearly twice the number of characters to work with. Make sure this too speaks to the Facebook audience. You have to 297 characters to make it happen.Format:<br/>
```<meta property=”og:description” content=”Stop hitting refresh on your ex-girlfriend’s Facebook page? You should check out the iAcquire blog and learn something instead”/>```


<h3> Debug tools</h3>
When our page have been shared at least once, facebook will catch our page and save the cache so when we reshare our page we will see the page as same as the first time shared even we has make change in our page. To reload the view we can use debuging tools provided by facebook in ``` https://developers.facebook.com/tools/debug/ ```

<h3>Image Sizes</h3>

Use images that are at least 1200 x 630 pixels for the best display on high resolution devices. At the minimum, you should use images that are 600 x 315 pixels to display link page posts with larger images.

<h5>Small Images</h5>

If your image is smaller than 600 x 315 px, it will still display in the link page post, but the size will be much smaller.


We've also redesigned link page posts so that the aspect ratio for images is the same across desktop and mobile News Feed. Try to keep your images as close to 1.91:1 aspect ratio as possible to display the full image in News Feed without any cropping.

<h5>Minimum Image Size<h5>

The minimum image size is 200 x 200 pixels. If you try to use an image smaller than this you will see an error in the URL Debugger.
