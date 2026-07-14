---
layout: post
title: "Remote Coding"
---
I created this post from a Microsoft Teams message.

That is the whole point of this entry: the path from an idea to a published website is becoming shorter, more conversational, and more connected. I sent a message in Teams asking Scout to add a blog post to my local website project. Scout found the local GitHub Pages repository on my machine, inspected the Jekyll blog structure, followed the existing post format, and created this Markdown file in the `_posts` folder.

From here, the workflow is familiar but much faster. GitHub Desktop can detect the file change in the local repository. I can review the diff, commit the update, and push it to GitHub. Because the site is hosted through GitHub Pages, that push becomes the trigger for the website to rebuild and publish the new post.

The products and connections that make this possible are working together:

- **Microsoft Teams** provides the conversational interface from wherever I am.
- **Microsoft Scout** acts as the AI agent that understands the request, reads the local project, and edits the right file.
- **Local file system access** allows Scout to work directly with the website source files on my machine.
- **GitHub Desktop** provides the human review, commit, and push experience.
- **GitHub** stores the repository and version history.
- **GitHub Pages** turns the Jekyll site into a published website.
- **OneDrive and the local Windows environment** provide the workspace where these tools can meet.

The result is a new style of remote coding: not just writing code from another location, but coordinating work through a chat interface, using AI to make the file change, using Git to preserve the change, and using cloud publishing to make it visible on the web.

This is a small post, but it represents a larger shift. The distance between intent, implementation, and publication is collapsing.
