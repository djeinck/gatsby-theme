# `@dschau/gatsby-theme-blog`

**Now lives at [DSchau/gatsby-themes](https://github.com/dschau/gatsby-themes)**

## Install

```sh
npm install --save @dschau/gatsby-theme-blog gatsby@^2.0.75
```

## Usage

In `gatsby-config.js`:

```js
module.exports = {
  __experimentalThemes: [
    {
      resolve: '@dschau/gatsby-theme-blog',
      options: {
        root: __dirname,
      },
    },
  ],
}
```

Additionally, you'll need to create a `content` folder with Markdown files powering the blog.

```shell
mkdir -p content/blog/2018-12-28-hello-world
touch content/blog/2018-12-28-hello-world/index.md
```

A sample post is below:

```md
---
date: '2018-12-28'
title: 'Hello World'
excerpt: 'This is an excerpt optimized for SEO'
featured: ./images/create-an-image-here.jpg
tags:
  - gatsby
  - is
  - wonderful
---

Hello World! This is my first post! I'll have great features enabled by default, including:

- Syntax highlighting with triple backticks
- Responsive images
- Responsive iframe embeds
- and more!
```
