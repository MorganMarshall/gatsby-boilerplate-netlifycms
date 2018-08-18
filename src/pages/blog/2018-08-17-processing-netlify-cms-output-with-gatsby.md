---
templateKey: blog-post
title: Processing Netlify CMS Output with Gatsby
date: '2018-08-17T21:10:25-04:00'
description: >-
  Gatsby can be configured to process Markdown by following the Adding Markdown
  Pages guide in the docs.
tags:
  - tags
  - gatsby
  - moretags
---
![](/img/jay-gatsby.jpeg)

Our config.yml file for Netlify CMS is set up to use the same fields used in the guide, so you can follow the instructions to the letter and should work fine. Note: When configuring the gatsby-source-filesystem plugin in the Adding Markdown Pages Guide, the path to your markdown files should be ${__dirname}/blog.

Once this is complete, get your changes committed and pushed up to your GitHub repo and check your site! The new blog post will be at whatever you entered in the path field when creating your blog entry in Netlify CMS. If you followed the example in Gatsby’s Adding Markdown Pages guide and used “/blog/my-first-blog”, then your blog post would be at “your-site-name.netlify.com/blog/my-first-blog”.

This was a very basic example meant to help you understand how Netlify CMS works with Gatsby. As mentioned in the beginning of this guide, if you got stuck, you can compare your code to the example repo, which is a working example created by following this guide. You can also reach out to the Netlify CMS community on Gitter. Lastly, if you’d like to move into a more complete boilerplate to get going with Gatsby and Netlify CMS, you can clone and deploy the official Gatsby Netlify CMS starter to Netlify with one click.
