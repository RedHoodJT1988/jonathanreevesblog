---
path: '/second-blog'
date: '2018-11-15'
title: 'Implementing Google Maps API with React and GraphQL'
---

YouTube Whiteboard Interview:
https://www.youtube.com/watch?v=Xj0QLsfw9wA

---

Trello Ticket Board

1. https://trello.com/c/Hh2cP5dd/14-google-maps-api-integration

2. https://trello.com/c/UAMvcOMX/41-add-o-auth-to-login-and-sign-up-pages

---

Pull Requests on GitHub:

1. https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/27

2. https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/43

3. https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/44

4. https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/46

---

Project GitHub Graph: https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pulse

Hello and welcome to my second blog entry on our journey to creating an app with React, GraphQL, Apollo, and Prisma. What a ride it has been so far. If you read my last blog then you have a basic idea of what has been built so far, if you haven't then I highly recommend checking it out then coming back here. You can find my first blog here: https://jonathanreevesblog.netlify.com/first-blog.

To begin today's blog I will tell you about the steps that I took to implement Google Maps API with our project. First we tried to work with Esri ArcGIS JavaScript Map API. It was pretty straight forward and really well documented. The problem I was having with it was getting the environment set up and ready for deployment. For some reason or another Netlify couldn't find the dojo/dojoDOMReady! files and dependencies necessary to function. I spent several hours trying to locate a solution and even reached out to a fellow Lambda Grad that works with the ArcGIS software on a daily basis. I was told that they use WebPack in production and that dojo wasn't something they setup.

Being a bit discouraged and slightly irritated I decided to step away from the computer for a bit. Which is something that I highly recommend doing if you find yourself caught between a rock and a hard place. You need to regain focus. Think about something else for a little while, most often than not a potential solution will come to you and you can try implementing that to see if it works.

Well that is exactly what happened. I was playing with my kids and a thought crossed my mind. Maybe ArcGIS wasn't the best API for this project. Sure it's great and really simple to use but perhaps it doesn't mesh well with the tech stack we chose. I decided at that point I would be using Google Maps Api to accomplish the same thing. I read the documentation. Did a few tutorials to get myself acquainted with the API and it's usage. Then I set out to add a Google Map to our website. What I found out was that Google and ArcGIS both have really well written documentation. It was an easy transition and I was able to create a Map component have it start at a random location and then zero in on the browsers location with a marker showing you your location based on what the browser shows.

All in all it was a frustrating week of work but my team and I were able to get things working and have continued to knock it out of the park with innovative ideas and solutions to issues that get in the way.
