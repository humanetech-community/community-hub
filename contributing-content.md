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

- Prepare a new forum topic for the Comments thread with an excerpt or the full text of the page.

- When this topic is created, use the topic ID (the number part in the URL) and add it as `discourse_topic_id: [topicId]` in the frontmatter.

> **Note 1**: Comments on a Blog post are always allowed, but for other pages a member of the Community Team should review and approve.

> **Note 2**: By using `discourse_topic_id` the first post in the topic is not shown on the website. This is by design (See [this comment on meta.discourse.org](https://meta.discourse.org/t/embedding-discourse-comments-via-javascript/31963/299) for info). By using an existing topic and `discourse_topic_id` there is full control over the topic title and category.
>
> But it is also possible to forego the manual topic preparation and setting `discourse_topic_id`, but in this case the topic is auto-created in the _Uncategorized_ category with a default title of _"[Page title] - Humane Tech Community"_ and must be moved and renamed after the fact. So using `discourse_topic_id` is preferred.

### Previous / Next navigation

The website uses a pagination scheme (see [post_pagination.html](https://github.com/humanetech-community/community-hub/blob/master/_includes/post_pagination.html)) that drives the 'Previous' and 'Next' buttons at the bottom of the page.

When adding new pages to the Community Hub this pagination needs to be tested to see if there is still a logical ordering of the page. If this is not the case, then the automatic pagination must be overridden by adding `custom_pagination` to the frontmatter metadata and specify either the `prev` or `next` page (or both) manually.

Example:

```yaml
permalink: /about/
title: "About"
excerpt: "About the Humane Tech Community"
author_profile: false
last_modified_at: 2019-04-20T12+02:00
sidebar:
  nav: "about"
custom_pagination:
  prev: /resources/
---
```

(See [Issue #28](https://github.com/humanetech-community/community-hub/issues/28) and [Pull Request #62](https://github.com/humanetech-community/community-hub/pull/62) for background information.)