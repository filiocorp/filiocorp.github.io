---
layout: post
title: "How to write an article"
date: 2019-08-13 -4:00
categories: jekyll update
description: "A sample description for my article"
author: "Arvin Poddar"
---

Hey reader, welcome to this file.

The first thing you'll want to do to make a new article is to copy this entire page, and paste it in the same folder we're in right now (`_posts`). All articles are stored in the (`/your-blog-folder/_posts`) folder. This is the only folder you need to work with.

Then, take a look at the information at the top of this file (between the dashed lines). Go ahead and edit all of that so that it pertains to your new article.

**Here's some important steps you need to know:**

- `your-blog-folder` is what I'll call the folder where all your blog stuff is stored. It is not actually going to be called `your-blog-folder`.
- When you make a new article, it has to be a Markdown file (ends in `.md` or `.markdown`)
- When you paste the article, change the name of the document to look like this:
  - `2019-08-15-article-title.md`
- All posts go in the `/your-blog-folder/_posts` folder
- All images go in the `/your-blog-folder/images` folder
- When you're done making your changes, save everything and use `git push`

Here's how to add an image to your article:
![Lamborghini](https://www.lamborghini.com/sites/it-en/files/DAM/lamborghini/model/huracan/Evo/car-configurator.jpg)
Note that an image will be the full width of the post, so make sure you pick some good quality images.

If you need an image that you have saved, paste the image into the **images** folder (`/your-blog-folder/assets/images`). Then, use the notation below to insert the image:
![Lamborghini](/assets/images/404.png).

**These blogs are written in Markdown, a simple computer language. Here's a few syntax guides you may need:**

`*italics*` = _italics_

`**bold**` = **bold**

# Header

`code`

```
Inline code
```

A table:

| A1  | B1  | C1  | D1  | E1  |
| --- | --- | --- | --- | --- |
| A2  | B2  | C2  | D2  | E2  |
| A3  | B3  | C3  | D3  | E3  |
| A4  | B4  | C4  | D4  | E4  |

- Bulleted list
- Another bullet

1. Ordered list
2. Another bullet

[//]: # "You can write invisible comments for your own reference like this"
