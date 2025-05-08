---
title: about
layout: about
---

## About me

Sup! I haven't wrote this part yet, so I guess you can call me mysterious?

## About this blog

The technical details of this blog can be loosely organized into three areas: writing, styling, and networking.

For readers like you, the most relevant area is writing, as its ones and zeros directly translate to human-readable text, which form the core of every article, written in the [Markdown](https://daringfireball.net/projects/markdown/) language.

Style-wise, this blog uses the [Hexo framework](https://hexo.io/) and its community-made [Fluid theme](https://hexo.fluid-dev.com/), both of which are free and open source. Although these libraries are far from perfect, as demonstrated through the hours of tweaking needed to implement a quote generator, they are still comparably more lightweight than other options, making the blog easy maintain and manage.

Finally, the most important area of any website is its networking. This blog was hosted on a [S3 Bucket](https://aws.amazon.com/s3/) connected to a [Route 53](https://aws.amazon.com/route53/) domain, running on [AWS](https://aws.amazon.com/), but has since migrated to [GitHub Pages](https://pages.github.com/) for lower costs and ease-of-use. The actual code is tracked by a Git repo stored on [GitHub](https://github.com/canonnizq/blog.canonni.website). When new code is pushed, an [automated script](https://github.com/canonnizq/blog.canonni.website/blob/main/.github/workflows/deploy.yml) is run, which tests, builds, and deploys the website to GitHub servers.

If all of that sounded unnecessary and verbose, you're right. Welcome to the internet, where nothing works, and where countless tools are created (and fail) to remedy the status quo.
