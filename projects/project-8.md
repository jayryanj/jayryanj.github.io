---
layout: project
type: project
image: images/URLookup_logo.png
title: URLookup
permalink: projects/URLookup
# All dates must be YYYY-MM-DD format!
date: 2020-10-09
labels:
  - Software
  - Web Application
  - JavaScript
  - Security
summary: Web app for checking a URL for threats.
---

<img class="ui image" src="../images/URLookup_landing.png">

URLookup is a small web application focused on the security of the web regarding URLs. Links can be dangerous, and most users don't know that they are until after they've already clicked on it. URLookup allows users to submit suspicious URLs to check for any possible threats and present easy-to-read results.

The point of URLookup is to use popular third-party scanning APIs, compile their often complicated results, and present the user with a concise decision whether the URL is safe. Currently, URLookup uses urlscan.io's API, but more API integration such as Google Safe Browsing, scanii, VirusTotal, annd Hybrid Analysis APIs are currently being planned. I solely created URLookup as a personal project because of my deep interest in cyber security and programming.

Below, you can see the technologies used in the development of URLookup

Front-end:
- HTML, CSS, JavaScript
- React
- Bootstrap

Back-end:
- JavaScript
- Node.js
- Express.js
- MongoDB (still under development)

Other:
- Git/GitHub
- Heroku

For links to the deployed site and the Github repo, see below.

Links:
- [URLookup Github Repo](https://github.com/jayryanj/URLookup)
- [Deployed Site on Heroku (using free dyno)](https://urlookup.herokuapp.com/)