---
layout: post
title:  "common sense and chatbot"
description: "Common sense is a set of views on the surrounding reality, a sober, practical understanding of things, prudence, the ability of a person to think logically. But is there a thinking chatbot?"
date: 2020-11-13 20:01:21 -0400
type: card-img-top
categories: chatbot
image: /assets/img/posts/t6-slide1.jpg
caption: 
last-updated: 2020-11-13 20:01:21 -0400
category: post_en
tag: chatbot
author: Anna Liednikova
---

It is pleasant to maintain a conversation with a person with common sense: he is able to think logically, has a basic set of facts about the world around him, and can connect them in a sequence. As a rule, we are not aware of all this and draw conclusions intuitively. But in order to teach a virtual friend common sense, you need to decompose the process into components. What are they in general terms?


Most of today's chatbots are semantic. I am not counting those who are built on deterministic rules. The "train of thought" of the semantic chatbot can be correlated with our intuitive thinking, built on associations.


The ability to reason is a more energy-intensive skill and includes building not so much associative connections as causal ones.

As an example, I will give a slide from [Commonsense Tutorial (T6), Commonsense resources](https://homes.cs.washington.edu/~msap/acl2020-commonsense/slides/03%20-%20Commonsense%20Resources.pdf).

  <img src="/assets/img/posts/t6-slide1.jpg" style="width: 50%">

To be able to build these causal relationships requires some basic set of facts, axioms of sorts, about the environment.

And here we smoothly come to the concept of a knowledge base and reflections. But it is only recently that they have begun to be correlated with common sense among chatbots.

When Geoffrey Nunberg [spoke about] in 1987 (https://www.aclweb.org/anthology/T87-1027/) in Position Paper on Common-sense and Formal Semantics, the concept of common sense began to be perceived at the level of esotericism and was avoided in every possible way. And now this common sense can even be touched and pampered with.

Today I would like to share with you two types of knowledge that form the common sense of a chatbot.

The first type of knowledge is semantic, it is built on the relationship "A is B". The most popular resource is [ConceptNet](http://conceptnet.io/), which began to form as early as 1999. As an illustration, a slide from [Commonsense Tutorial (T6), Commonsense resources](https://homes.cs.washington.edu/~msap/acl2020-commonsense/slides/03%20-%20Commonsense%20Resources.pdf).

  <img src="/assets/img/posts/conceptnet.jpg" style="width: 50%">

Another type of knowledge is inferential knowledge, i.e. when we get new knowledge from the knowledge acquired earlier. The most popular resource is ATOMIC, which contains a set of facts about how X affects Y. I suggest playing with this model [here](https://mosaickg.apps.allenai.org/comet_atomic).

  <img src="/assets/img/posts/atomic.png" alt="Фрагмент карты взаимосвязей"> 

Thanks to the introduction of these models into chatbots, they are able to generate or select an answer that not only matches the topic of the conversation, but also fits into the set of facts voiced by the interlocutors. And below is an excellent example of such reasoning from the article by Svetlana Vakulenko[Measuring Semantic Coherence of a Conversation](https://arxiv.org/abs/1806.06411). If you are not familiar with the Ubuntu operating system, the conversation may look like an incoherent set of phrases, but in fact the conversation is very consistent.

  <img src="/assets/img/posts/ubuntu.png">

Both knowledge bases continue to grow, and the methods of their introduction into the dialogue with the chatbot are growing in quantity and quality. Who knows, maybe soon thinking sensibly about life with a chatbot will not be such a curiosity? Have you met people who are not entirely sane? What prompted you to give them such a title? Isn't the general knowledge base the same?
