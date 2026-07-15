---
layout: default
title: Website changelog
permalink: /changelog/
---

<section class="hero panel">
  <p class="eyebrow">Private working notes, public page</p>
  <h1>Website changelog.</h1>
  <p class="tagline">
    A running history of requests, implementation notes, and publishing decisions for this site. This page is intentionally not linked from the main navigation, but remains available directly at <code>/changelog/</code>.
  </p>
</section>

<section class="section panel post-content">
  <p class="eyebrow">How to read this</p>
  <p>
    Entries track the source of the request, the exact prompt or request where available, the change made, and any related commit. Older setup entries came from prior Scout desktop sessions. Later entries came through Microsoft Teams relay messages.
  </p>
</section>

<section class="section panel post-content">
  <p class="eyebrow">Changelog</p>

  <h2>2026-07-15</h2>

  <h3>Created this hidden changelog page</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Excellent, please do so, and I need you to also create the entries in this change log that cover all the requests made starting with asking you how to do it and installing GitHub desktop and also track where the request or change was initiated from. If this was via teams or Scout desktop and include the exact prompt or request that was sent
  </blockquote>
  <p><strong>Change:</strong> Added a public-but-unlinked changelog page at <code>/changelog/</code> with request history, source channel, exact prompts, and commit references.</p>

  <h3>Recommended hidden changelog approach</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    I want to make a change log for the website so that I can make notes and track changes I make to it from start to finish. I would also like to be able to access this change log from the web but I don’t want it to add it to the navigation. So this could be in a subdirectory as long as i can access it online. What do you recommend?
  </blockquote>
  <p><strong>Change:</strong> Recommended a hidden public page at <code>/changelog/</code>, accessible by direct URL but not added to site navigation.</p>

  <h3>Removed white line overlay from profile image</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    can you remove the part of the web template that creates the white lines over my profile pic
  </blockquote>
  <p><strong>Change:</strong> Removed the <code>.headshot::before</code> CSS pseudo-element that drew angled white/border lines over the homepage profile image.</p>
  <p><strong>Commit:</strong> <code>1652da1 Remove profile image overlay</code></p>

  <h3>Created OneDrive asset intake folder for mobile uploads</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    I see, I am working remotely with Teams on my phone, but I am going to try and save the images to my OneDrive using my OneDrive app on my IPhone. To make sure that I place them in a directory that you can access would you create a folder in my OneDrive called jeromeshort.com_Assets
  </blockquote>
  <p><strong>Change:</strong> Created the local OneDrive-synced folder <code>C:\Users\jeshort\OneDrive - Microsoft\Documents\jeromeshort.com_Assets</code> for images that need to be used in website posts.</p>

  <h2>2026-07-14</h2>

  <h3>Removed screenshots and postscript from Remote Coding post</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Remove the images and the post script and the post script from that last post
  </blockquote>
  <p><strong>Change:</strong> Removed all image embeds, deleted the temporary redacted screenshot assets, and removed both postscript paragraphs from the Remote Coding post.</p>
  <p><strong>Commit:</strong> <code>207cfd6 Remove screenshots and postscript from remote coding post</code></p>

  <h3>Added redacted screenshots and post-postscript, then pushed</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    First, add this image to the post and add a post post script with a note about how happy I am that you took the extra step to ask me before push pushing the post and then go ahead and push it
  </blockquote>
  <p><strong>Change:</strong> Added the post-postscript and pushed the previously prepared redacted screenshots. The image attached through Teams was not exposed as an accessible file, so it could not be added.</p>
  <p><strong>Commit:</strong> <code>52a11f4 Add redacted screenshots to remote coding post</code></p>

  <h3>Prepared screenshots and privacy checkpoint for Remote Coding post</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Can you add these screenshots to the post but also redact the file path and url path from the images. Also ad a post script to the post to marvel at the fact that I’m able to stand up my own social media with a laptop and a cell phone
  </blockquote>
  <p><strong>Change:</strong> Created redacted local screenshot copies and updated the post locally, but paused before pushing because the screenshots came from work/Teams context and needed confirmation before public publication.</p>

  <h3>Added Remote Coding blog post</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Can you add a blog post and call it Remote Coding and write a post that gives a brief explanation I was able to create this post via a teams message and explain the whole path from this post to it being pushed to the site and then explain what products and connections made this possible
  </blockquote>
  <p><strong>Change:</strong> Added <code>_posts/2026-07-14-remote-coding.md</code>, explaining the Teams-to-Scout-to-GitHub-Desktop-to-GitHub-Pages workflow.</p>
  <p><strong>Commit:</strong> <code>bbdd63a Add remote coding blog post</code></p>

  <h3>Asked whether remote website edits were possible through GitHub Desktop</h3>
  <p><strong>Source:</strong> Microsoft Teams relay</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Are you connected to GitHub desktop and able to make changes to my website that is open
  </blockquote>
  <p><strong>Change:</strong> Clarified that Scout cannot directly control the GitHub Desktop UI, but can edit local files and use Git/GitHub Desktop’s bundled Git once the repository path is known.</p>

  <h3>Installed GitHub Copilot CLI</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    install github copilot
  </blockquote>
  <p><strong>Change:</strong> Installed GitHub CLI through a portable path and verified <code>gh copilot</code> downloaded Copilot CLI successfully.</p>

  <h2>2026-07-13</h2>

  <h3>Implemented Reader Mode and Short Mode</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    ok, I want to implement but call them Reader Mode and Short Mode
  </blockquote>
  <p><strong>Change:</strong> Replaced the old B/W toggle with a real presentation switch across the homepage and blog layouts. Reader Mode simplifies the page for reading; Short Mode restores the branded visual design.</p>
  <p><strong>Commit:</strong> <code>d40873c Replace B/W toggle with reader mode</code></p>

  <h3>Renamed blog navigation link</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Change the navigation link to the blog to 'Short Blogs'
  </blockquote>
  <p><strong>Change:</strong> Updated homepage and blog-layout navigation labels to <strong>Short Blogs</strong>.</p>
  <p><strong>Commit:</strong> <code>222024d Rename blog navigation link</code></p>

  <h3>Renamed blog title</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    Change the blog title from Jerome's blog to 'Short posts'
  </blockquote>
  <p><strong>Change:</strong> Renamed the blog title across config, blog index, and post layout.</p>
  <p><strong>Commit:</strong> <code>9c2ce96 Rename blog to Short posts</code></p>

  <h3>Updated video placeholder copy</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    update the text in the video placeholder to say 'coming soon: A 'Short' discussion on why AI transformation matters, how you advise executive teams, and what makes your Microsoft AI/cloud perspective valuable. And change the Placeholder to 'A Short executive introduction video.'
  </blockquote>
  <p><strong>Change:</strong> Updated the homepage interview/video placeholder text.</p>
  <p><strong>Commit:</strong> <code>24a1985 Update video placeholder copy</code></p>

  <h3>Changed blog title links to orange</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    can you make it so that those blog title links are orange instead of blue
  </blockquote>
  <p><strong>Change:</strong> Added styling so blog card title links use the orange theme accent.</p>
  <p><strong>Commit:</strong> <code>ecc480a Use orange blog title links</code></p>

  <h3>Added first two blog posts</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    I want to create two posts. I'd like your assistance writing these. The first one I would like a short one paragraph that kicks off the blog and describes my interests in AI and my excitement about using these tools, describe them, to create the entire site. The second post I would like to be about the Legal Agent in Word and how it could have impact on how lawyers utilize Microsoft tech and why this is a consideration for law firms to adopt Copilot wall to wall. mention that I have seen this first hand. And that the expectation is that innovations for legal and other regulated industries will continue to be released and how this could cover many of the use cases for a large percentage of the firm that may not need a full third party AI license for things like Harvey.
  </blockquote>
  <p><strong>Change:</strong> Added <strong>Launching this site with AI</strong> and <strong>Why legal agents in Word matter</strong> as initial Jekyll posts.</p>
  <p><strong>Commit:</strong> <code>fa740c3 Add initial blog posts</code></p>

  <h3>Installed local Jekyll tooling</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    yes please install
  </blockquote>
  <p><strong>Context:</strong> This followed the question <q>should I install Jekyll locally</q>.</p>
  <p><strong>Change:</strong> Installed Ruby, Jekyll, and Bundler locally and verified the site built successfully.</p>

  <h3>Added Jekyll blog structure</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact requests:</strong></p>
  <blockquote>
    I want a jekel blog to this site and add it to the navigation, match the existing theme, ask me if any details I left out
  </blockquote>
  <blockquote>
    /blog details Jerome's Blog
  </blockquote>
  <p><strong>Change:</strong> Added Jekyll-ready <code>/blog/</code>, <code>_layouts/post.html</code>, and <code>_posts</code> scaffolding; added the blog to site navigation.</p>
  <p><strong>Commit:</strong> <code>18cfcc0 Add Jekyll blog</code></p>

  <h2>2026-07-10</h2>

  <h3>Darkened geometric site background</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    I want to make the background on this theme darker and use a different geometric pattern in the background
  </blockquote>
  <p><strong>Change:</strong> Updated the homepage background to a darker geometric visual treatment.</p>
  <p><strong>Commit:</strong> <code>ceee143 Darken geometric site background</code></p>

  <h3>Adjusted profile image framing</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact requests:</strong></p>
  <blockquote>
    now it's clipping my chin can you shrink it down so my whole head is in the picture and adjust the width of the frame if need be
  </blockquote>
  <blockquote>
    yes, please fix and push
  </blockquote>
  <p><strong>Change:</strong> Adjusted the headshot layout so the full head remained visible.</p>
  <p><strong>Commits:</strong> <code>13b4849 Adjust headshot crop</code>, <code>de65f2f Show full headshot portrait</code></p>

  <h3>Added grayscale headshot</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    I want to update he placeholder headshot with this picture "C:\Users\jeshort\OneDrive - Microsoft\Delete Review\Medium\Pics from phone\jeshort2.JPG" but I want to have it rendered in greyscale and have it cropped accordingly
  </blockquote>
  <p><strong>Change:</strong> Created and added a grayscale headshot asset for the homepage.</p>
  <p><strong>Commit:</strong> <code>a0a2f70 Add grayscale headshot</code></p>

  <h3>Public-safety content review and copy softening</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact requests:</strong></p>
  <blockquote>
    can you check the content of this site for anything that would be data or content about Microsoft or my microsoft customers that I may want to remove as sensitive or confidential. I have no reason to believe that there is but I want you to validate and then itemize anything
  </blockquote>
  <blockquote>
    please do that
  </blockquote>
  <p><strong>Change:</strong> Reviewed public content and softened references that could overstate Microsoft/customer specifics.</p>
  <p><strong>Commit:</strong> <code>eb8b7d4 Soften public site Microsoft references</code></p>

  <h3>Published CTO personal site to GitHub Pages repository</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    I have done steps 1, 2, and 3 above. The repository is cloned to the path C:\Users\jeshort\OneDrive - Microsoft\Documents\GitHub\Chef-Jeromeo.github.io Can you copy the CTO HTML into the repo as index.html and then commit and push from GitHub Desktop
  </blockquote>
  <p><strong>Change:</strong> Copied the CTO HTML into the repository as <code>index.html</code>, committed, and pushed to GitHub Pages.</p>
  <p><strong>Commit:</strong> <code>d5b9931 Publish CTO personal site</code></p>

  <h3>Created GitHub Pages CNAME</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact context:</strong> Part of the GitHub Pages publishing setup for the personal website.</p>
  <p><strong>Change:</strong> Added <code>CNAME</code> to support the custom domain configuration.</p>
  <p><strong>Commit:</strong> <code>5684551 Create CNAME</code></p>

  <h3>Chose personal GitHub publishing path</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact requests:</strong></p>
  <blockquote>
    I want to upload this to my github pages site
  </blockquote>
  <blockquote>
    I want to publish to this repository https://github.com/Chef-Jeromeo/Chef-Jeromeo.github.io.git what do I need to provide to enable this
  </blockquote>
  <p><strong>Change:</strong> Determined the repo target and what was needed to publish the generated CTO site to GitHub Pages.</p>

  <h3>Installed GitHub Desktop for publishing workflow</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    install GitHub Desktop
  </blockquote>
  <p><strong>Change:</strong> Installed GitHub Desktop to support committing and pushing the site through a visual Git workflow.</p>

  <h3>Initial share/path discussion for CTO website</h3>
  <p><strong>Source:</strong> Scout desktop session</p>
  <p><strong>Exact request:</strong></p>
  <blockquote>
    what is the url for the CTO website I asked you to make and how can I share this to other users inside Microsoft
  </blockquote>
  <p><strong>Change:</strong> Identified the locally generated CTO website artifact and discussed internal sharing/publishing options before moving to GitHub Pages.</p>
</section>
