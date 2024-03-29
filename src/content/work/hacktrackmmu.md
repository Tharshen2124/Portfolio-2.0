---
title: Hacktrack MMU
publishDate: 2019-10-02 00:00:00
img: /assets/hacktrackmmu.png
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
description: |
  A system to keep track of members IdeaTalks and ProgressTalks for each meetup and hackathon.
tags:
  - Svelte
  - Ruby on Rails
  - PostgresSQL
---
<p style="color: orange"><b>NOTE:</b> This is still in development</p>

This website is where we in Hackerspace MMU committee members manage our members details and store their IdeaTalks and ProgressTalks relating to the projects they have worked on for each meetup and hackathon.

The current site is still up and can be accessed <a href="https://hacktrackmmu.herokuapp.com/">here</a>. However it will soon be replaced with the new interface as you have seen from the diagram above.

Im currently working on the new interface that uses the same backend as the previous one but modified the backend to server as an API.

Some of the challenges i faced was:
- navigating through the ruby on rails backend system that is 12 years old.
- trying out sveltekit for the first time
- figuring out how to setup an authentication token for login system from scratch without any libraries
