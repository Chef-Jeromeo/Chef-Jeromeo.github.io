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

Here are a few redacted screenshots from the workflow. The file paths, URL path, QR code, participant names, and message details have been removed before publishing.

![A redacted Teams message showing the request flow from mobile Teams into Scout](/assets/remote-coding/teams-message-redacted.png)

![A redacted Teams meeting participant pane showing the Teams collaboration surface](/assets/remote-coding/teams-participants-redacted.png)

![A redacted GitHub Copilot canvas reference showing the behind-the-scenes development workflow](/assets/remote-coding/github-canvas-redacted.png)

This is a small post, but it represents a larger shift. The distance between intent, implementation, and publication is collapsing.

P.S. It is worth pausing for a second to marvel at the fact that I can stand up my own small social-media-like publishing channel with a laptop and a cell phone. A thought starts as a Teams message from a phone, turns into a file change on a laptop, becomes a Git commit, and then lands on a public website. That is not just remote work; it is personal publishing infrastructure that used to require a whole stack of specialized skills, hosting, tooling, and time.

P.P.S. I am also genuinely happy that Scout took the extra step to ask before pushing screenshots to a public site. That human checkpoint matters. The magic is not just that AI can make the change; it is that the workflow can still pause for judgment, privacy, and intent before something becomes public.
