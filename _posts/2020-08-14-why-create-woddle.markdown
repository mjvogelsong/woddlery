---
layout: post
title:  "Why create Woddle.io?"
date:   2020-08-14 11:00:00 -0700
categories: starter
---

*By: Michael Vogelsong*

# Background

The goal of woddle.io is pretty simple: allow people to ask for services that address their problems. This is enabled by an API marketplace, with one important distinction. Marketplaces usually are provider-driven, where the goods or services are designed by the providers. E.g., Company A designs and sells product A, and some subset of customers buy it if it fits into what they're looking for. However, for APIs and online services, we could imagine a better experience. With APIs, the user's goal is to accomplish some task(s) while not having to know all the nitty gritty technical details of how the tasks are implemented. In other words, the user will often have an idea on what they want an interface to look like, even if a real service to accomplish it doesn't exist yet. So, we should make the marketplace user-driven, where users are specifying the interfaces they want to see, and providers take those desired interfaces and create implementations that fulfill those requests.

With the user-driven API marketplace, we move toward shortening the gap between having a goal and having a system to accomplish the goal. Plus, exploring the marketplace can even have the added effect of inspiring new ideas and goals.

# What do developers want?

Well, I don't know exactly what all developers value -- that's why Woddle exists: to understand what they want! However, I think there are some key themes that will be true in many cases:

## From a user perspective

1. I want to work with the simplest interface possible that completely addresses my goals, but no simpler. There should be sensible, best-practice defaults whenever possible, with optional escape hatches when customization is needed.

2. I want to specify the most fundamental pieces of information, and then let the system infer the rest.

3. I want to feel confident improving a system, and have a low barrier to making those improvements. I should feel comfortable experimenting and trying new things, knowing that if I make a mistake or introduce an error, the remedy is straightforward.

4. I want to feel confident using a system -- I want to know that the system I'm using will perform reliably, efficiently, and accurately. I like when it "just works."

5. Statefulness can be hard and confusing, so I'd like as little statefulness as possible. But when it is a necissity, I should know where I'm at in a workflow, what to expect in proceeding, and how to return to an earlier or cleaner state.

6. I want pricing options that accurately reflect the value I'm receiving.

7. I want to know the services I'm using are trustworthy and employ good business ethics.

## From a builder perspective

1. I want as little overhead as possible between having functionality (e.g., code) and deploying that functionality for community usage (i.e., as an API).

2. I want to earn money on my service proportional to the value I'm providing.

3. I want to feel comfortable upgrading my service, with confidence that the right changes will be available to users.

4. I want to get my services in front of the releavnt audience of users.

5. I want to have the best information on what developers want, what frustrations they have, and what major needs are not currently being met.

6. I want to make sure my services are not being abused or used in a way that harms others.

As more users and builders join Woddle, I hope to update this summary with feedback! We will use these core needs to prioritize how we build and improve Woddle.io.