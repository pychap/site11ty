---
title: Second post
date: 2020-03-03
---

There's not much here in the sample post page. Better get to work.

<img width="400" src="../../images/eberhard-grossgasteiger-aC25VCORbog-unsplash.jpg" alt="Mountains">

The common front-matter data for all of the files in the posts section are abstracted into a `posts.json` file so that we don't need to repeat that on every file. Handy.

It looks like this:

```js
{
  "layout" : "layouts/post.md",
  "tags" : "post",
  "templateEngineOverride": "njk,md"
}
```


