# Project Scorecard

[![Netlify Status](https://api.netlify.com/api/v1/badges/fba40d60-3c7a-4c03-a9d2-67cd33a98834/deploy-status)](https://app.netlify.com/sites/justin-tsugranes-scorecard/deploys)

A basketball scorecard using JavaScript

Here is the [live demo](https://justin-tsugranes-scorecard.netlify.app/).

## Challenges

The hardest part of this project was formatting the multiple levels of flexboxes. It's easy to get lost in exactly what the flex flow of each individual component is.

I used a main container to hold all of the items, then created a container to hold both of the teams individual scores and all their corresponding buttons. Then, each team has their own container with a heading, scorefield, and then a container with each of the buttons.container

Handling flexbox is easier when you start from the top of a design and then hone in on the layouts of specific, more atomic components.

## Mistakes / Failures

I don't think the box model is being implemented in a unified way. I could sketch out the padding, borders, and margin so everything follows a simple design system.

## Enjoyed

I'm getting a much stronger grasp on controlling CSS. It's enjoyable to purposefully make things look specific way.

## What I'd Do Differently

I think I could refactor the javascript for updating the scores in the DOM. There is a redudancy in typing `homeScore.textContent = homeCount` three times for each team. I could probably hold that in a separate function and call that function.

I also added some unused classes on the increment score buttons that I wasn't sure if I was going to use or not. I could probably erase those.
