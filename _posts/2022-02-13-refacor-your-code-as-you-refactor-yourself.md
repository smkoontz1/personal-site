---
layout: post
author: Steven Koontz
title: Refactor Your Code as You Refactor Yourself
type: Blog
excerpt_separator: <!--more-->
---

I have found that when I go to compose a text message, an IM, an email, even this first sentence, I often follow some common patterns in the way I go about constructing the message. I always start with an intention, a reason that I am writing at all.

I recall in school how teachers would always recommend starting a paper by just spilling your brain into a draft. You have something you want to say, and it's in your head, but you have to convert your thoughts into written language. It is not often easy to find the words to express what you need to, so you write a mess, but at least you wrote it all down. Only you know what you mean, so the challenge becomes ensuring that others will understand your words the way you do by making it as easy as possible for them to read what you write.

How do you do this? Simplify. Remove all the fluff that doesn't need to be there.<!--more--> Let's say you're telling someone you'll be available later, but you need to go to the grocery store first.

You could say:

"I need to run to the grocery store so I can pick up some more cheese, because I had some, but I didn't use it fast enough, and then it got mold spots, and I was supposed to make burgers tonight, so I need more."

Or you could say:

"I need to run to the grocery store."

These both accomplish the same goal, informing your friend of the reason you won't be available. For someone that doesn't live with you and has no stake in your dinner plans (steak pun not intended), do they really need to know about your moldy cheese? Probably not. You might think it a supplementary addition, but it doesn't affect them, so they likely don't care. It could be argued that they don't even need to know where you are going, just that you are busy now, and will be available later.

The question then becomes, what do you do if you find yourself starting with the long sentence? That was the "brain draft," because you were concerned about your moldy cheese and felt a desire to express it. You realize the message is too long and unnecessary for your audience, so you reword it, removing some words altogether. You realize there are countless ways to say what you need to, but some are simpler and easier to understand than others. Finally, you land on your final message and send it.

Then, you read it again, because you have to make sure you actually agree with what you just sent. You notice another problem in it, and if you're lucky enough to be using a communication platform with an edit button, you edit your message. If not, you send a small correction. This is how we attempt to be properly understood when utilizing the written language through technology.

Writing code for software is the same way. You start with an intention, a clearly defined problem you need to solve. I have often heard the recommendation not to worry about what the code looks like, how fast it is, or how easy it is to read. Just write something that works to solve the problem. Once you have done this, you can begin to look at modifying the code to clean it up and make it easier to understand for the next person that has to maintain it. You may also begin to recognize some slow areas in your code that you can now focus your attention on, rather than getting bogged down by needing to figure out the optimal way to write everything all at once before you even test it. For the nontechnical people here, this modification process is called refactoring.

I wrote a text message recently, and I found myself writing it once, deleting it, writing it another way, deleting part of it, and writing it again, until I finally sent it. I realized I had followed this exact process earlier that week with some code that I was writing. Code is just that, a machine-friendly encoding of your explanation of how to solve the problem. I knew what the code needed to do, and I wrote it one way that would have worked, but it was so confusing to look at that I tried a different way, using some different utilities in the programming language. That wasn't quite right either, so I modified it just a little more until I got something I was pretty sure would be easy enough to understand in the future that was as concise as I could make it given what it needed to do.

Coding is like golf. Solve the problem in the least amount of steps possible while ensuring you can grow your program to solve subsequent problems as needed in the future. That way, when someone comes back to try and understand what your code does, they don't have to sift through your moldy cheese to understand that you only needed to go to the grocery store.