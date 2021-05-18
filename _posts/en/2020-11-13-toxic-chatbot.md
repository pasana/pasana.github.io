---
layout: post
title:  "toxic chatbot"
description: "The concept of toxicity smoothly migrated from chemistry to psychology, defining unpleasant destructive communication. Is this common among chatbots and why?"
date: 2020-11-13 20:01:21 -0400
type: card-img-top
categories: chatbot
image: /assets/img/posts/sophia.png
caption: ""
last-updated: 2020-11-13 20:01:21 -0400
category: post_en
tag: chatbot
author: Anna Liednikova
---

Technologies do not stand still, new models are emerging that can generate text. For chatbots, these models are trained on data from social networks such as Twitter or Reddit. But the better the text generation got, the more dangerous it became to use such chatbots. Why is that?


A year ago, Microsoft released a new dialogue generation model trained on a huge data set - 147 million Reddit conversational threads from 2005 to 2017. The advantage of this model is that it can be easily adapted to suit your needs. But that's bad luck! There are no links to sources in the article, just a small note: "Due to random toxic outputs, we cannot release the generation code at this time." Now, it is already possible to indulge with this model [here](https://huggingface.co/microsoft/DialoGPT-large).


I myself have come across unpleasant responses from the GPT-2 model. Somehow in my practice there was such a dialogue:

<ul>
<li><b>Bot:</b> Do you have difficulty with sleep?</li>
<li><b>User:</b> Yes, sometimes I wake up in the middle of the night </li>
<li><b>Bot:</b> What wakes you up? </li>
<li><b>User:</b> Wife snoring</li>
<li><b>Bot:</b> So crush her with your pillow </li>
</ul>

In general, after such an outcome, adjusting the model to the context and depriving it of creativity as much as possible, I smoothly moved away from generative models ...


You can also recall the robot [Sophia](https://twitter.com/RealSophiaRobot), which at some point I was filled with hatred for humanity.

  <img src="/assets/img/posts/sophia.png" style="width: 50%; align: center">

And where do the legs grow from? And from us, from dearest, they grow.


3 years ago, in March 2018, the Conversation AI team, a research initiative founded by Jigsaw and Google, shared the Kaggle [dataset](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) with toxic comments so that users compete for the $ 35,000 prize and develop the best classifier.


And this winter, 2020, it was already possible to test the application [detoxifAI](https://detoxifai.com/), which simply hides stinging and violent comments on the Internet.


Let's get back to chatbots. How to deal with them? After all, generative models make the conversation interesting and unpredictable. Six months after Microsoft, Facebook released the Blender model, which is particularly friendly and positive. However, in their article, they warn that since the model was originally trained on Reddit, the likelihood of toxicity still remains.

They managed to achieve a significant improvement with a very simple solution: the candidates proposed by the model for responding to the interlocutor are filtered by a classifier similar to those developed on Kaggle.

Here we are! I hope you are not involved in these riots and very pleasant interlocutors. In the meantime, you can bet, what will happen first: will people learn to filter their talk on the Internet, or will technology find a way to instantly neutralize them?
