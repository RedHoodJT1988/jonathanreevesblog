---
path: '/first-blog'
date: '2018-11-09'
title: 'My Time with GraphQL'
---

Hello,

My name is Jonathan Reeves. And, as the title of this blog suggests, I will be talking about my experience with GraphQL on the project my team and I are working on.

I helped solidfy the team by explaining GraphQL's Mutation and Query functionality to allow one of my teammates, who specializes is frontend, to develop the mutation for deleting a user. My team is awesome. We immediately meshed together. We see and try to implement everyone's expertise as a whole. There is no I in TEAM and we definitely reflect that. I might have caused some friction with my MacBook acting up at the beginning of the week. But have since fixed that issue and am good to go. GraphQL so far has been amazing and has cut the amount of development time that normally takes place creating logins, signups, and signouts into mere hours vs days.

Project links:
Frontend Link: https://clever-ramanujan-6abad4.netlify.com/
Backend Link/User Account Tool: https://adventure-tracker-backend-ewlkjhhafm.now.sh/

Pull Request and Trello Card Links:
PR 1: https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/4
PR 2: https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/14
PR 3: https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/18
PR 4: https://github.com/Lambda-School-Labs/Labs8-AdventureTracker/pull/19

Trello Card: https://trello.com/c/jKderASz/1-create-user-accounts

I was tasked with creating User Accounts. Since we decided on GraphQL and I knew very little about it. I knew that I had a lot of research ahead of me. I thought for sure I was going to be reading through documentation for at least a day just getting used to the syntax and testing small things out to get a feel for how the process would work. Let me tell you right now that was not the case. GraphQL made it very simple to create that first sginup mutation almost instantly. Now I know what you are thinking. What in the world is a mutation? Well in GraphQL, for those new to it, you have two ways of accessing and creating data. You have a mutation (which would be creating data) and you have a query (which would be how you get the data). You have a few files that you need to configure before it all works. Below are the generaized steps one would take to create a signup mutation:

1. You create a schema.graphql file and input your code for the mutation here is a small example
   `type mutation { signup(name: String!, email: String!, password: String!):User!}
2. You then move to your Mutation.js file and configure the logic for said mutation.
3. Then you push your schema changes up to your database that GraphQL supports, we chose to use Prisma so our command was `npm run deploy

4. Then we opened up GraphQL Playground, a really awesome and vital tool for testing your Mutations and Queries to make sure all is working ok.

5. Once everything is working and you have tested it, you're done

So in conclusion I have found GraphQL to be a great tool for backend logic. One that I will continue to use going forward. Especially since it plays so nicely with just about everyt language you can use on the web.
