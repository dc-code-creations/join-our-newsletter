<!-- Please update value in the {}  -->

<h1 align="center">{Join Our Newsletter} | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/join-our-newsletter" target="_blank">Join Our Newsletter</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://join-our-newsletter-murex.vercel.app/">
      Demo
    </a>
    <span> | </span>
    <a href="https://github.com/dc-code-creations/join-our-newsletter">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/join-our-newsletter">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- OVERVIEW -->

## Overview

![screenshot](images/final-project-screenshot.png)

<!--
Introduce your projects by taking a screenshot or a gif. Try to tell visitors a story about your project by answering:

- What have you learned/improved?
- Your wisdom? :)
-->

### What I learned

<!-- Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge. -->

This project wasn't too difficult overall, so I took this opportunity to determine when it was best to use relative vs absolute units of measure when creating as webpage and well as which ones work best when. Here is a quick(ish) summary of what I gathered:

  - relative units: change relative to some other element on the page (viewport, another element, text/character size, etc.)
  - absolute units: don't change change relative to some other element on the page

  - most frequently used units: rem, em, vh, vw, %, px (so majority relative units, absolute almost exclusively px)

  - em/rem (generally rem is preferred): padding, margings, fonts, height
  - vh/vw: height/width respectively (useful when something needs to take up a certain percentage of the viewable screen)
  - %: width (recommended, for items that don't have to take up a certain portion of the screen), height
  - px: should be used sparingly for responsive design; anything that needs to stay the same size no matter what 
      - specifying the fixed size of an element (border size, image size, etc.)
      - border radius (acts differently than percentages do, seem more stable and look better to me)
  - ch: can be used for fonts or width sometimes supposedly, but I don't know how often this is the case

### Useful resources

<!--
- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.
-->

[CSS Units & When To Use Each](https://www.freecodecamp.org/news/css-units-when-to-use-each-one/#:~:text=For%20width%2C%20percentages%20are%20often,depending%20on%20your%20specific%20requirements) - this is the article I read that helped me determine which units to use when

### Built with

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Acknowledgements

<!-- This section should list any articles or add-ons/plugins that helps you to complete the project. This is optional but it will help you in the future. For exmpale -->

## Author

- Website [daracline.gitlab.io](daracline.gitlab.io)
- GitHub [@dc-code-creations](https://github.com/dc-code-creations)
