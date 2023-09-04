---
layout: essay
type: essay
title: "Question Everything?"
# All dates must be YYYY-MM-DD format!
date: 2023-09-04
published: true
labels:
  - Open Source 
  - Communication
  - Community Involvement
---

<img width="200px" class="rounded float-start pe-4" src="../img/softDev.png">

*"There is no such thing as a dumb question! If you have a question, just ask!" - MANY many teachers*

In a classroom setting, where information is not as easily accessible and perhaps being seen for the first time, there are very limited opportunities for stupid questions. The question that has already been asked is a stupid question and the question that was already answered (perhaps not as a question but in the content) is also a stupid question. Outside of those factors its extremely difficult to ask a stupid question. Regardless, many students fear ridicule or negative feedback and as a result do not ask questions that could have been quite smart. 

But what about online? If you're home and you have a question? Well, in that scenario it is much more likely you have a stupid question. With the resources available to you and modern day technology, you probably have the capability to answer that question yourself. However with a few guidelines, you can avoid an embarassing online blunder and make sure you are contributing positively to your community. How does one ask a smart question? Its not quite as simple as "all questions are smart questions", because that's quite untrue, so lets dive in. 

## Search First, Ask Questions Later

*"It is better to keep your mouth closed and have people think you are a fool than to open it and remove all doubt" - Mark Twain*

Oh no! You've run into a problem! What are you going to do? Solving it seems kind of like a lot of work...i'm sure someone online probably knows the answer right off the top of their head! Bigger oops, you've now just asked a stupid question. 

So what should you have done? Running into problems in every aspect of life is going to happen. However, throwing in the towel before exhausting your possibilities for solving it yourself is not just bad character, but also a waste of time for everyone else. In the context of the open source software community, how do we know when we need to ask a question? Computer work is kinda hard...you've been staring at this screen and you just *cannot* figure it out. 

Luckily, Eric Steven Raymond has given us some [guidelines](http://www.catb.org/esr/faqs/smart-questions.html). Before you ask, it is your responsibility to exhaust all options for getting the answer yourself. This includes looking for the answer online, searching the forum it makes the most sense to post your question to, read the manual, read the FAQ, try some problem solving and mess around with it, ask someone you are friends with if they might know the answer (obviously, this one applies only when they have experience in the field), and read the source code! Basically, if you have a way to get the information without posting the question, do not post the question before you've exhausted all options. 

## How to Pop the Question 

Alright, you've now done everything you can think of to possibly find the answer. You are certain your question is not a stupid one, because you've done everything you can to try and find the answer, and it's still nowhere to be found. Now what? Time to pop the question! 

But wait! Even after all the work you've just done, your question could still be stupid if you don't ask it the right way. So how do you make sure that you're not wasting your time or other peoples' time? It's important to remember, that you are not owed an answer. You're doing this in your free time, and so is anyone who might answer your question. How do you encourage others to *want* to answer your question? Raymond says, theres a a few things we can do. 

Make sure you post your question in the correct forum, i.e. don't ask a question about mammals in a forum about snakes, people will think you are dumb. If you don't know the difference between mammals and snakes, why would I waste my time explaining something about mammals to you, even if I know the answer? Similarly, if the forum is very technical, don't post a question thats *not* technical. Intuitive, right? Find the forum that fits the question, and created a targeted post within that forum, and maybe one or two others, but not too many! You want your question to recieve the appropriate amount of eyes, basically, don't put the question everywhere you can think of, and don't send it directly to one person. I have never met you and you emailed me your question? It's not my job to answer, and you're acting like it is. Now you're ignored, doofus. 

Based on your question, there may be a few special cases that apply to you. For [Stack Overflow](https://stackoverflow.com) questions, you should always search first and then ask. Do not ask a question that has been asked before. For Web/IRC forums, theres often a channel for people who are new to get help. Still, search before asking. If you're not getting anywhere, use mailing lists, not individual email addresses. 

Your subject line is very important. Be descriptive, not using phrases such as "need help" or "assistance needed" or etc. Obviously you need help, otherwise you wouldn't be here. The best practice in subject lines is to use the "object-deviation" format. What are you needing help with, and then what is going on? It both introduces the topic to the reader, allowing them to quickly ascertain whether or not they can even help, and begins explaining the problem. 

## What do You Mean?  

So lets go ahead an analyze some examples, just to see all the above in action. 

1. In this [example](https://stackoverflow.com/questions/71724426/how-to-prevent-useeffect-run-twice-after-running-a-function-in-context-consume), someone was having an issue with a javascript function in react. Overall, the post was well made and the community response was positive.

   Positives of this post inlcude the subject line. The subject, while it is not in the object-deviation format, does accurately summarize the issue the poster was having. Additionally, all of the code included in the post was correctly formatted (no images, could easily be copy-pasted). The post is very descriptive and allows the reader to understand what is going on thoroughly. This question could not be found anywhere else on the site, and as a result there were over 2000 views and 3 detailed responses. 

2. In this [example](https://stackoverflow.com/questions/23040185/insert-table-names-in-jcombobox-in-swing-java), someone was having an issue with table names in JComboBox in swing Java. Overall, the post was not well made and the community response was nonexistent.

   The subject line of this post accurately describes the issue the poster was having. However in the description description, lines such as "Please point out the mistake that i'm doing" and "Sorry if this question is already posted". There were no responses at all to this question. The code is properly formatted and included in the post, however not enough context as to what is going on is provided.

3. In this [example](https://stackoverflow.com/questions/57871677/ios-13-silent-push-notifications-are-no-longer-reliable), someone was having an issue with iOS notifications. Overall, the post was not well made and the community response was nonexistent.

    The subject line of this post is nondescript, and makes a statement that is not conducive to an answer. The entire post in general is not very specific, and ends without ever technically asking a question. Naturally, there were over 8000 views of this post without a single answer. 

## All Around

We are continuously growing and changing. As people, as a community, as a profession, and even as a world. You know, in the third grade I had a teacher who wouldn't let me use a calculator. I ofcourse thought, well we have this magnificent tool, we already learned the basics and *can* do it without, why not use this awesome technology? "When you grow up and are walking around town, you're not going to be carrying a calculator everywhere with you!", boy oh boy I bet she feels pretty silly now. 

Our only limit is our imagination. Even recently, another thing most of us wouldn't have dreamed up, became commonplace! You can now chat with a website, who seems to know way more about your differential equations class than you do! Obviously, there have been some pretty problematic things with A.I. in the past, but there's always a learning curve with these types of things. There is so much left to discover and develop. Learning the tools and methodologies to move ourselves forward as a society (and get an A in ICS 314) is just the first step! I cannot wait to be part of the professional computer science community, contributing to the innovations and society of tomorrow! 
