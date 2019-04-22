---
layout: post
title: First post.  Thanks Jekyll!
image: /img/jekyll.png
---

Hello and welcome! 👋

This is my first post to this blog.  The primary focus in the future will be around topics involving DevOps and SRE (Site Reliability Engineering), but for this first post I wanted to praise [Jekyll](https://jekyllrb.com/){:target="_blank"} for helping me get a blog running quickly, easily, and on my own terms.

### How Did I Get Here?
When I decided that I was going to start journalling this new career direction into DevOps and SRE, I needed an outlet for said activity.

I quickly remembered that I had a neglected blog over on WordPress where I had been documenting my practice of Brazilian Jiu Jitsu (currently on extended hiatus).  I hit up my old account and started setting up a new blog.  Within moments, I was attempting to install a plug-in for some extra customization to support code highlighting.  I soon found out that something that simple required a paid subscription.  This sent me on the path to find an alternative solution that I had more direct control.  Enter Jekyll.

### Steps For Setting Up This Blog
Jekyll is a tool built using Ruby to build static webpages.  It allows the use of Markdown, so I knew it could be decent for creating simple blog posts quickly.

Having some Python experience, I immediately asked: "How do I install Ruby?  Is there a similar solution to pyenv, virtualenvwrapper, etc. for Ruby?".  

1) I found [rbenv](https://github.com/rbenv/rbenv){:target="_blank"} and installed on my Mac.  While this doesn't set up a virtual environment, it allowed me to target a specific Ruby installation that wasn't the default one for my machine.  This allowed me to have solid control over the version I was using locally to ensure it would always work in production.

Next, I set up Jekyll on my machine.

2) I followed the simple steps to install Jekyll and spin up a quick site provided by the [Jekyll Home Page](https://jekyllrb.com/){:target="_blank"}

Once I had a site running, I practiced writing a post and viewing locally.  I then skipped a lot of steps to figure out how to serve the site via GitHub Pages.

3) I used Mike's instructions found [here](https://www.youtube.com/watch?v=fqFjuX4VZmU){:target="_blank"} to deploy my site to GitHub Pages.  I'm sure there is a lot of great information in the other 18 parts of the tutorial, but Jekyll is so easy to get started that it was unnecessary for me.

After I had completed a test deployment and had an empty blog created, I felt that the blog needed a bit of a prettier face.  I wanted simple, but beautiful.  I tried a number of [themes](https://jekyllrb.com/docs/themes/){:target="_blank"}, but eventually landed on [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll){:target="_blank"}.

4) I forked [beautiful-jekyll](https://github.com/daattali/beautiful-jekyll){:target="_blank"} on GitHub and followed their instructions.  

5) After I tested a deployment, I updated the About Me, wrote this post, and pushed it to GitHub.

Overall, this was a simple process.  I like that if I ever get tired of the site's style, I can easily change or customize the theme.  It was a bit more work compared to creating something via a blog site, but I believe it was worth it for the learning experience and having total control over the site.  Plus, GitHub pages are free!

Thanks Jeykll!  👍
