# Contributing content

### Blog posts

The website uses the same Markdown syntax that the forum uses. You can write your text in a new forum topic and we will help you along. Here’s the procedure:

1) Create a new topic in the [Awareness program category](https://community.humanetech.com/c/focus/awareness-program).

1) Use as title “Blog post: [Your proposed blog title]”.

1) Write a short summary of the subject and other things you want to address in the blog post. Then submit your post.

1) Optionally some discussion ensues on the topic with tips and feedback to refine the article

1) When ready, write the full blog post!
    - Feel free to use any of the formatting and Markdown syntax available on the forum. Use this [Markdown tutorial](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to see other markdown syntax you can use for formatting.
    - Include as many images as you like (but note licensing issues, and where you got them from)

1) When you're finished, we will help you to transfer the text to the website!
    - If you want to be attributed we need to add your contact details to [authors.yml](https://github.com/humanetech-community/community-hub/blob/master/_data/authors.yml), including your photo 290x310 pixel or similar aspect ratio.

All your work is attributed to you and has your name to it (unless you want to stay anonymous, of course). You are the copyright owner (the license is [CC-BY](https://creativecommons.org/licenses/by/4.0/)).


### Other content

If you're looking for content to contribute, check out the [issues tab](https://github.com/humanetech-community/community-hub/issues?q=is%3Aissue+is%3Aopen+label%3A%22needs-content%22) for tickets with the ![](https://img.shields.io/badge/-content%20needed-blue.svg) tag!

When you encounter pages on the Community Hub that you would like to contribute to, you can also create an issue yourself, and add this label to it.

Once you find content you'd like to contribute, create a new topic in the most relevant category on the [forum](https://community.humanetech.com/) to share it, and we will help transfer it to the site. If you're unsure which category it belongs in, create it in [feedback](https://community.humanetech.com/c/central/feedback).

To the forum topic you should add the `community-hub' tag for findability, and provide a link to the related Github issue.

### Enabling comments

A blog post (and any other page) can have an optional Comments thread attached to it. The comments appear directly below the content on the same page.

- Indicate in the forum topic where you discuss your contribution that you would like to have a Comments section.

  - Enabling comments is done by adding `comments: true` to the frontmatter metadata of the page.
  - Optionally an existing forum thread can be shown as the Comments thread, by also adding `discourse_topic_id: [topicId]` to the frontmatter.

After the page is published a Discourse forum topic will automatically be created on the HTC [discussion forum](https://community.humanetech.com), in the _'Uncategorized'_ category. You can ask a moderator to move it to another, more suitable, category (this does not break the link to the page).

> **Note 1**: Comments on a blog post are always allowed, but for other pages a member of the Community Team should review and approve.

> **Note 2**: There is a bug in the Discourse integration code. When using `discourse_topic_id` the first post in the topic is not shown on the website. See [this comment](https://github.com/humanetech-community/community-hub/issues/46#issuecomment-487286701) for info.