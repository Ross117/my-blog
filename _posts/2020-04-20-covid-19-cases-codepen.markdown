---
layout: post
title: "Covid-19 Cases Project"
date: 2020-04-20 17:00:00 +0100
categories: programming
---

<a href="https://github.com/Ross117/covid-19-cases-by-english-county">Github repo</a>

This project acted for me as a refresher in:
 - Vanilla JS
 - HTML
 - CSS
 - APIs
 - Code Pen

The purpose of this mini-project was just to use my web development skills to create something for the first time in a long time. It is very basic, and in fact it’s now broken as the API no longer exists; it was only in a working state for around 10 days. It was interesting to find the API and work out how to get the data from it; I remembered how helpful Postman can be. Coding-wise, I focused principally on the Javascript side. I remember feeling frustrated at times as I struggled to do something quite simple (make a HTTP Request and append the results in the HTML DOM). Quite a bit of it was a case of refreshing myself on syntax, and also struggling with asynchronous code. My main problem was caused by not tying together the function which appended the data to the DOM and the async function which made the HTTP request, with the result that the former was called before the latter has finished executing. I did get it working eventually though. I spent a bit of time refactoring the Javascript code, which involved trying to make it more concise and modular. There’s minimal HTML and I stole the CSS from one of my other Code Pens.
