+++
author = "Hugo Authors"
title = "Guide to Thumbnails in Hugo"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo"
tags = [
    "thumbnail",
]
[![N|Solid](https://image.shutterstock.com/image-photo/closeup-nature-view-green-leaf-600w-387062149.jpg)](https://nodesource.com/products/nsolid)
+++
Thumbnails can be enabled easily by setting the `thumbnail` parameter in the frontmatter to an image such as `"images/landscape.jpg"`. 

[![N|Solid](https://image.shutterstock.com/image-photo/closeup-nature-view-green-leaf-600w-387062149.jpg)](https://nodesource.com/products/nsolid)

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


