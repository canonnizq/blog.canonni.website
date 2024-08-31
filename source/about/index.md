---
title: about
layout: about
---

## About me

Sup! I haven't wrote this part yet, so I guess you can call me mysterious?

## About this blog

The technical details of this blog can be loosely organized into three areas: writing, styling, and networking.

For readers like you, the most relevant area is writing, as its ones and zeros directly translate to human-readable text, which form the core of every article, which are written in the [Markdown](https://daringfireball.net/projects/markdown/) language. Despite being the easiest to deploy and scale, .md files are dumpster files waiting to be disposed by sane humans in modern civilization. For that reason, in the near future, this blog and its articles may be migrated to another, cleaner, text-markup language.

Style-wise, this blog uses the [Hexo framework](https://hexo.io/) and its community-made [Fluid theme](https://hexo.fluid-dev.com/), both of which are free and open source. Although these libraries are far from perfect, as demonstrated through the hours of tweaking needed to implement a quote generator, they are the best solutions avalible that utilize raw HTML, making the blog easier to maintain and manage.

Finally, the most important area of any website is its networking. This blog is hosted on a [S3 Bucket](https://aws.amazon.com/s3/) connected to a [Route 53](https://aws.amazon.com/route53/) domain, running on [AWS](https://aws.amazon.com/), the largest and most stable cloud service provider worldwide. The actual code is synced via a Git repo stored on [GitHub](https://github.com/canonnizq/blog.canonni.website). When new code is pushed, an [automated script](https://github.com/canonnizq/blog.canonni.website/blob/main/.github/workflows/deploy.yml) is run, which uploads the updates to AWS' servers in Nevada.

If all of that sounded unnecessary and verbose, you're right. However, keep in mind this is one of the easiest ways to operate a small-scale blog with minimal funding and that the explaination above is already grossly simplified.
