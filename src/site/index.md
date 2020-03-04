---
title: peterY
subtitle: This site to peg a stake for me in the digital world using <a href="https://www.11ty.dev/" target="_blank">Eleventy</a> / Netlify / PostCSS, somewhat quickly.
layout: layouts/base.njk
---


## All the things I find interest in, yet blocked by not enough time in the day:

Recent projects, Skills, interests, ramblings:

- [Chalk](https://chalk.vuforia.com/): wrote all CSS using Grid, Flexbox
- [Engine.Vuforia.com](https://engine.vuforia.com/engine): wrote all CSS using Flexbox
- **Apps:**  
  * Chalk Desktop (styling in a component environment using LitHTML)  
  * Chalk Admin




## Post pages

The pages found in in the posts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Learning

- Currently working my way through Zell Liew's **[Learn Javascript](https://learnjavascript.today/)** and Wes Bos's **[Beginner JavaScript](https://wesbos.com/beginner-javascript/)**

## Running locally

```bash
# install the dependencies
npm install

# External data sources can be stashed locally
npm run seed

# It will then be available locally for building with
npm run start
```


### Redirects and proxies

Netlify's Redirects API can provide friendlier URLs as proxies to these URLs.

- [/api/hello](/api/hello)
- [/api/fetch-joke](/api/fetch-joke)




