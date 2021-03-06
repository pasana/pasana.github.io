---
layout: post
title:  "chatbot and role models"
description: "A role is a set of functions for performing a specific range of tasks. There are social roles, there are interpersonal roles, and what are they for chatbots?"
date: 2020-11-17 20:01:21 -0400
type: card-img-top
categories: chatbot
image: /assets/img/posts/roles.png
caption: ""
last-updated: 2020-11-17 20:01:21 -0400
category: post_en
tag: chatbot
author: Anna Liednikova
---

Our interactions are driven by the social context. In most cases, being in society, we perform some kind of social role, and sometimes several. Since the context of using a particular chatbot, as a rule, remains unchanged, it can be assumed that it also has one role model. But is it?

<img src="/assets/img/posts/roles.png">

This has been true for a long time. In general, chatbots can be divided into two main camps: goal-oriented (there is a task, it needs to be solved: order tickets, a hotel, make a diagnosis) and chit-chat (talk about everything and nothing, as long as there is enough resource).


And only in 2017, Zhou Yu, Alan Black and Alexander Rudnitsky presented the first hybrid ([Learning conversational systems that interleave task and non-task content](https://www.ijcai.org/Proceedings/2017/0589.pdf)). Through their research, they have shown that a system that alternates between social content (chit chat) and task content (goal-oriented) is more successful at accomplishing a task and more attractive than a purely task-oriented (performer).

The main task of the chatbot they presented was to recommend films, but in order for it to cope with the task more efficiently, several communication strategies (from the role of a chit-chat) were added to the main set of functions (the role of the goal-oriented bot):

  <ul>
<li> <b> Active listening strategies </b> engage users by actively participating in the conversation, such as asking additional questions about the current topic </li>
<li> <b> Rationale strategies </b> using knowledge from the knowledge base, linking and proposing facts for the current topic </li>
<li> <b> Personalized strategies </b> - adaptation to the user using automatically extracted information from a conversation with him. For example, offer to talk more about a specific topic, knowing that the user has previously been involved in that topic. </li>
  </ul>

But in general, the development of performers and talkers individually developed faster than together. Nevertheless, the tendency to combine various roles behind the interface of a single system remained.


For example, at the end of the same year, the Heriot-Watt University team put forward the social dialogue system [Alana] (https://arxiv.org/abs/1712.07558) (chatterbox) as part of the [Alexa Prize](https://developer.amazon .com / alexaprize). This system combined several roles at once, which are highlighted in gray in the next fragment of the dialogue.

<img src="/assets/img/posts/alana.png">

And in October 2020, the first [article] was published (https://dl.acm.org/doi/10.1145/3383652.3423889), which showed that mixing roles did not give positive results. It turns out that the public space and work environment create a completely different context than when you are at home talking face to face with your virtual assistant like Alexa.

<img src="/assets/img/posts/busy.png">

And Facebook released a chatbot [Blender](https://ai.facebook.com/blog/state-of-the-art-open-source-chatbot/), which combines the following communication functions:

<ul>
<li> Engaging use of personality (<a href="https://arxiv.org/abs/1801.07243">PersonaChat</a>) </li>
<li> Engaging use of knowledge (<a href="https://arxiv.org/abs/1811.01241">Wizard of Wikipedia</a>) </li>
<li> Display of empathy (<a href="https://arxiv.org/abs/1811.00207">Empathetic Dialogues</a>) </li>
</ul>

Although ... Hmm ... Wait, doesn't this remind you of all those chatbot's communication strategies for recommending movies? Yeah, everything is the same, only now the methods are more effective. If earlier it was a limited set of templates, now each strategy is a previously developed chatbot that generates text, being trained on a huge amount of data.

<img src="/assets/img/posts/blender.png">

As you can see, the idea of combining various roles and communication strategies is far from new, but it is still very relevant from three sides: 1) development of each role separately, 2) determination of the optimal set of roles for the task, 3) determination of the optimal criterion for selecting a candidate for output to the user.

And you, dear friends, how many roles do you have in your arsenal and how often do you use them? Do you feel that sometimes it's time to pump up a joker, empath, or arrogant person? How many roles do you allow yourself to mix up in your workplace? And in general, did everyone think about it before?
