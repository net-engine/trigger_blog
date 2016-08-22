# Trigger Blog

[blog.triggerapp.com](http://blog.triggerapp.com/)

This project uses [Jekyll](https://jekyllrb.com/).

## How to setup this project?

* Clone the repository
* `bundle install`

## How to run the blog server?

Run `bundle exec jekyll s` and access [lvh.me:4000](http://lvh.me:4000/).

## How to create a new post?

    bundle exec jekyll post "My New Post Name"

## How to deploy?

    ./deploy

---

## Categories

Each category in the sidebar is set by the frontmatter in the articles, this also becomes part of
the finished URL.

```
---
layout: post
title: Pay by cash
category: payment
---
```

This will create a `payment` category in the sidebar and list this post under it, the path to that
post will be `/payment/pay-by-cash`.

### Adding images

To ensure a good quality of the images, please resize the screenshot or any images to
**1200px width**.
