# Basic blog template in Jekyll

This is a 'starter kit' for running a blog with Jekyll. It uses the base `minima` theme with some (opinionated) so if you are hoping to get started easily, try cloning this repo.

Setup steps:
Go to your new repo's settings on Github, choose "Pages," then choose "deploy from a branch" and choose `gh-pages` as the branch.

In the "Actions->General" settings page, grant "read and write permissions" to workflows. This will allow the "PR preview" action to run.

To blog:
Check out a new branch.
Create a markdown file in `_posts` with a filename of the format `YYYY-MM-DD-title.md`. Add "front matter" at the top of the file:

```markdown
---
layout: post
title:  Your title here
categories: optional space-separated list
---
```

Write your post below the second set of hyphens. When you're ready, commit your changes and open a pull request. The "PR Preview" action will run and show you a preview of your new page. If you like it, merge, and wait for the second GH action to deploy your site.

These are just the very basics of Jekyll. Learn more with the [official docs](https://jekyllrb.com/), and happy blogging!