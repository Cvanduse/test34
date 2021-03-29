+++
author = "Hugo Authors"
title = "Guide to Thumbnails in Hugo 2"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo 2"
tags = [
    "",
]
thumbnail= "images/landscape.jpg"
+++
Thumbnails can be enabled easily by setting the `thumbnail` parameter in the frontmatter to an image such as `"images/landscape.jpg"`. 

[![N|Solid](https://image.shutterstock.com/image-photo/closeup-nature-view-green-leaf-600w-387062149.jpg)](https://nodesource.com/products/nsolid)

[(images/landscape.jpg)](https://nodesource.com/products/nsolid)

<a href="http://google.com.au/" rel="some text">![Foo](http://www.google.com.au/images/nav_logo7.png)</a>

[![homepage][1]][2]

[1]:  http://commonmark.org/help/images/favicon.png
[2]:  http://commonmark.org "Redirect to homepage"

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.8.0/css/bulma.min.css">
<section class="section">
<div class="container">
<div class="columns is-centered">
<div class="column is-half">
<a class="box" href="https://bio.fwd2cv.com" aria-label="Pizza Dough">
<div class="is-flex">
<div>
<div>Title</div>
<small class="has-text-grey">Sub Title</small>
</div>
</div>
<div style="margin-top:.1em">



Make sure to copy the image the `static/images/` directory.

If put together, it will look like this (that's in fact this post's frontmatter):

```md
+++
author = "Hugo Authors"
title = "Guide to Thumbnails in Hugo"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo"
tags = [
    "thumbnail",
]
thumbnail= "images/landscape.jpg"
+++
```


