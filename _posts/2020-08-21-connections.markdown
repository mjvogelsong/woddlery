---
layout: post
title:  "Connections"
date:   2020-08-21 10:00:00 -0700
categories: starter
---

*By: Michael Vogelsong*

Looking around at the software and machine learning space, I try to find the underlying goals. Moreover, I want to know which of these goals overlap -- they're usually a good source for ideas.

Anything-as-a-service, low-code and no-code platforms, machine learning (ML) / artificial intelligence (AI), APIs (Application Programming Interfaces), generative models -- they seem to all be working towards a similar goal, although they each emphasize different aspects. They try to achieve an interface to solutions that is as conveniently aligned with how we intuitively frame a problem, rather than how the technical details work. In other words, letting users specify / ask questions in a way that makes sense for the problem, rather than bogging them down with implementation details.

WHat's the approach?

- Anything as a Service: Software, infrastructure, etc. is provided to a user in a way where many of the implementation details, hardware setup, and manual processes are hidden away or amortized behind more conveient abstractions.

- Low-code / no-code: Modern programming still requires a lot of boilerplate and unintuitive knowledge to accomplish simple tasks. Low-code and no-code platforms try to provide logical building blocks in a more visual or intuitive way, so you can accomplish the tasks with lower barrier to entry.

- Machine learning / artificial intelligence: While many people think of training when they think of machine learning, it's really just a means to an end. As far as I'm aware, I don't know of any uses of ML training directly -- we find uses in model inference. Training is definitely important, but only in the context of improving the expected inference performance. The real goal of ML is to enable convenient interfaces at a more general scale.

- Generative models: A specific subfield of machine learning, generative models complete the picture and fill in the blanks. This is very imporatant to making better interfaces, as it lowers the burden of specifying input (since some of it can be inferred).

- APIs: APIs give convenient interfaces so that software systems can talk to each other, on behalf of a user or users.

