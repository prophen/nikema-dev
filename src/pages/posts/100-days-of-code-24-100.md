---
title: '100 Days of Code - [24/100]'
date: 2019-09-06T09:58:53.962Z
excerpt: >-
  It's been a frustrating day of coding. I decided to go on HackerRank to
  familiarize myself with the platform. I have a fear of regular expressions. I
  worked on a couple of challenges using them. I solved one of them. Matching a
  string with the same vowel at the beginning and end of the string.
template: post
---
It's been a frustrating day of coding. I decided to go on HackerRank to familiarize myself with the platform. I have a fear of regular expressions. I worked on a couple of challenges using them. I solved one of them. Matching a string with the same vowel at the beginning and end of the string.

```
function regexVar() {
    /*
     * Declare a RegExp object variable named 're'
     * It must match a string that starts and ends with the same vowel (i.e., {a, e, i, o, u})
     */
    let re = /^([aeiou])(.*\1$)/
    
    /*
     * Do not remove the return statement
     */
    return re;
}
```

I'm editing this post to explain what how my RegExp works. 

```
// // These wrap the regular expression, a syntax thing

^ // matches the first character

([aeiou]) // The parenthesis makes a group that I refer to later. The characters in brackets mean match any of them

.* // Any number of characters 

\1$ // Recalling that first group and checking that the same character is matched at the end of the string
```
I probably didn't explain them all with the correct words. I still have a lot to learn about RegExp. I don't want what I did learn to slip away. It feels like adding an explanation solidifies the learning.

The react tutorial is not going smoothly. My results are not the same as what's showing in the video. I'm going to leave it alone for now. It's too late to worry about it. Gotta sleep.
