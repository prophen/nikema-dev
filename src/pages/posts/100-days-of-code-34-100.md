---
title: '100 Days of Code - [34/100]'
date: 2019-09-17T08:13:07.198Z
excerpt: "I fixed the bug!These are the lines that were missing from my `postOneScream` firebase function ```if (req.body.body.trim() === \"\") {    return res.status(400).json({ body: \"Body must not be empty\" })  }```There was an if statement there but it was for a more general error. In hindsight, of course the error was on the backend. It took me a minute to figure it out. \U0001F926\U0001F3FE‍♀️"
template: post
---
I fixed the bug!
These are the lines that were missing from my `postOneScream` firebase function

```
if (req.body.body.trim() === "") {
    return res.status(400).json({ body: "Body must not be empty" })
  }
```
There was an if statement there but it was for a more general error. In hindsight, of course the error was on the backend. It took me a minute to figure it out. 🤦🏾‍♀️

 These are the small victories that are so satisfying. I'm in the last couple of hours of this course and honestly I'm ready to finish and move on to another project. It has been a long journey. I just want to be done. We're getting there. Today I added the feature that allows you expand an individual scream in a dialog. 

<a href="https://github.com/prophen/social-ape-client" target="_blank"><img src="https://d2ddoduugvun08.cloudfront.net/items/0N3P2y031M3S0l3E3Q3f/Screen%20Recording%202019-09-17%20at%2001.11%20AM.gif" alt="walkthrough of posting a scream and getting an error" style="display: block;height: auto;width: 100%;"/></a>
