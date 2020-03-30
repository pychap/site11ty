---
title: peterYchapman
subtitle: Front-end UI Developer
layout: layouts/base.njk
---

My personal website (just launched) using <a href="https://www.11ty.dev/" target="_blank">Eleventy</a> / Netlify / PostCSS / and for Typography, <a href="https://utopia.fyi" target="_blank">Utopia</a>.  

## Professional interests:  

<ul>
<li><a class="link__base" href="#"><span class="link__effect" data-content="Content here" aria-hidden="true"></span>Content here</a> I had a nice day to day.</li>
<li><a class="link__base" href="#"><span class="link__effect" data-content="Content here two" aria-hidden="true"></span>Content here two</a> then I went to the store and bought food.</li>
</ul>

Recent projects:


<!-- - <span class="link__effect" data-content="Link Hover" aria-hidden="true"></span>[Chalk](https://chalk.vuforia.com/): wrote all CSS using Grid, Flexbox -->
- <a class="link__base" href="https://chalk.vuforia.com/"><span class="link__effect" data-content="Chalk" aria-hidden="true"></span>Chalk</a>: wrote all CSS using Grid, Flexbox
- [Engine.Vuforia.com](https://engine.vuforia.com/engine): wrote all CSS using Flexbox
- **Apps currently working on:**  
  * Vuforia Chalk Desktop - styling in a component environment using LitHTML  
  * Vuforia Chalk Admin - tool for Chalk Admins with user accounts, data analytic views




## Post pages

These are placeholders for now, posts by me soon to come. Please check back.

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Learning

- Currently working my way through Zell Liew's <a class="link__base" href="https://learnjavascript.today/"><span class="link__effect" data-content="Learn JavaScript" aria-hidden="true"></span>Learn JavaScript</a> and Wes Bos's **[Beginner JavaScript](https://wesbos.com/beginner-javascript/)**  
- Build CSS challenges when I stumble on good ones

## Running locally

```bash
# install the dependencies
npm install

# External data sources can be stashed locally
npm run seed

# It will then be available locally for building with
npm run start
```

Fetch a joke!

<!-- - [/api/hello](/api/hello) -->
- [/api/fetch-joke](/api/fetch-joke)


<div class="nakedLink">

Latest deploy status: [![Netlify Status](https://api.netlify.com/api/v1/badges/056b4a67-70e6-4af4-9be5-dee151b8e906/deploy-status)](https://app.netlify.com/sites/eleventyone/deploys)

</div>