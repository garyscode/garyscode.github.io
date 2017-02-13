---
title:  "Social Blogging (like a hacker): Git WebHooks, WebAPI, and Twitter"
date:   2017-02-13
categories: [Github, WebAPI, Twitter, Azure]
tags: [garybryant.me, crlf, eolm, default end of line sequence, visual studio code]
published: true
---

**Issue blogging with Jekyll and Visual Studio Code**

I ran into an issue with my new blog.  It's supposed to use the first paragraph as the teaser, but only show the full blog once the title is clicked.  Instead, it was showing the entire post on the teaser page.

It turns out the default line endings in Visual Studio code are CR LF, which is expected.  However Jekyll apparently is looking for LF, not CR LF.  This turned out to be the issue.  I did find that I could change that per document by using the built in command to "Change End Of Line Sequence".  But then I'd have to remember to do it every time I wrote a blog.  

Thankfully, the latest version of [Visual Studio Code](https://blogs.msdn.microsoft.com/user_ed/2016/04/02/visual-studio-code-new-features-editor-improvements/) allows you to set the "Default End of Line Sequence".  Voila, the default is now LF.  Perfect for me for now as I'm only using VS Code to blog.  Time will tell if the change causes any other issues for me in the future, but for now I'm up and running in a convenient fashion.  :-)

G  

