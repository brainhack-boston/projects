---
layout: post
title: Submitting a project
date: 2017-02-10 17:05
comments: true
external-url:
categories: Hackathons openscience 0
---

For this Boston brainhack event, we are using [GitHub](https://github.com). Since GitHub is a common web service used in many software projects, it is useful to learn how to use it. Think of this as your intro to hacking.

If you are new to GitHub, here are several [guides](https://guides.github.com/). Perhaps [hello world](https://guides.github.com/activities/hello-world/) is a good place to start.

We have a GitHub organization: [brainhack-boston](https://github.com/brainhack-boston)

We have a [blog](https://brainhack-boston.github.io/projects) to collect projects. To submit a project we ask that you create a new post using a template and send a
pull request (GitHub jargon for asking us to review your proposal, and merge it online).

# Steps to submit a project

1. Go to the project posts directory

   Open [the post directory](https://github.com/brainhack-boston/projects/tree/master/_posts) in your browser.

2. Click on `Create a new file`

3. Name the file using a specific syntax

   `YYYY-MM-DD-short-title.markdown`

   You should replace **short-title** with your own. This should fork the project into your own GitHub repository. (Fork is GitHub jargon for making a copy of the project while preserving links to the main project and all the history).

4. Use a specified template to create a file.

   You can use [this first post](https://raw.githubusercontent.com/brainhack-boston/projects/master/_posts/2017-02-10-intro-to-brainhacks.markdown) as an example. Here is a template:

   ```
    ---
    layout: post
    title: ENTER A TITLE FOR YOUR POST
    date: YYYY-MM-DD HH:MM
    comments: true
    external-url:
    categories: Keyword1 Keyword2 ...
    ---

    WRITE POST HERE using markdown.
   ```

   The template has a header that you need to fill. You need to enter a title, date, and keywords for categories. Leave a blank line after the last '`---`', and then write your project description using [Markdown](https://guides.github.com/features/mastering-markdown/).

5. Send a pull request.

   Click on the `Propose new file` button. To truly understand how forks and pull requests work you will need to go through the GitHub guides.
