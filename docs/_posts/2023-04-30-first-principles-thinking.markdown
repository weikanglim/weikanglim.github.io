---
layout: post
title:  "First principles thinking: the secret to solving deeply complex problems"
date:   2023-04-30 09:00:45 -0800
categories: software
---

Reflecting upon my own journey in software, a question often pops up:

> Why do I often make different observations, and arrive at different conclusions than my peers? Why do I think differently?

For better or worse, I do have a different thought process than most engineers I have worked with during my career. I used to largely attribute it to my ability to think through logical problems in-depth, with rigor, and sometimes to the lengths of overthinking problems. Recently, I've realized that my thought process can be summed up to **first principles thinking**, and that this may be helpful to others that find it hard to see through the depth of problems.

## Definition

To understand first principles thinking, we first start by examining what "first principles" mean.

In philosophy or science, a first principle is defined strictly as a basic proposition or assumption that cannot be deduced from any other proposition or assumption (Wikipedia definition).

In math terms, a first principle is an axiom.

In physics, first principles are the laws that govern the universe. These are laws that you cannot violate in the real world. If you happen to be a lucky person who can demonstrate a repeatable experiment that shows otherwise, i.e., break the law of physics, congratulations! Scientists are now scrambling to figure out a proposal for a new law that is consistent with your experimental data. This doesn't happen very often, and you should pat yourself on the back since you've helped advance our understanding of our universe.

What exactly is first principles thinking then? While there are many different versions of the definition that exists, here's mine:

First principles thinking is being able to understand the first principles (either confidently believed to be true or formally proven), in each problem space, building up rules from there, and finally creating solutions or conclusions that are consistent with the first principles.

Scientists applies first principles thinking all the time without thinking about it since they live and breathe in their subject matter, and it comes natural to them. When scientists are able to think critically and apply the right amount of creativity to discovery new breakthroughs, I believe first principles thinking plays a large role here.

A more well-known example is how innovators such as Elon Musk applies first principles thinking to decide whether a deeply complex problem that often requires significant amount of time, effort, and money is worth looking into.

In a recent podcast #252 with Lex Fridman, Elon Musk describes first principles thinking as follows:

> First principles analysis can be applied to really any walk of life. It involves just boiling down something to the most fundamental principles, the things we are most confident are true at a foundational level. That sets your axiomatic base, and then you reason up from there. And you cross check your conclusion with your axiomatic truth.

How it applies to a practical problem:

> Let's take an example of manufacturing. You're trying to take a new advanced technology part and bring it to volume manufacturing. This is the hard phase of manufacturing -- the design of the part was the easy phase.

>  Now then, you have to ask yourself, why is this part of the product is expensive? Is it something fundamentally foolish? Or is the volume too low? What if our volume was a million units a year? Would it still be expensive then? If it is, then there is something fundamentally flawed about the design.

In a few sentences, Elon was able to provide a reasonable materials cost analysis with little effort. Most business leaders would have delegated this analysis to the experts, industrial manufacturing engineers after years of college and industry experience.

The power of first principles thinking is illustrated here in this example. Someone with little in-depth experience in the problem domain was able to come up with a reasonable hypothesis by applying deep understanding of science and math involved in a practical fashion. The hypothesis can then be refined upon with help from relevant experts using numerical analysis based on concrete evidence.

In the remainder of this article, we'll look at more specific examples in software and life that showcase how first principles thinking work in practice, and how it ends up being an incredibly valuable way of thinking.

## First principles thinking distills problems into fundamental units, which is powerful

I view first principles thinking as perhaps a more advanced technique than general logical thinking. When thinking logically, you try to make logical connections between statements, and try to identify whether a conclusion follows from initial problem statements and the rules provided.

This gets us very far. Logical thinking governs our daily lives in how we decide on what goals to pursue, how to execute on our goals, and balancing our priorities.

A more advanced technique exists with first principles thinking. When you think using first principles, you understand that all problems in life that are governed by general principles that are most likely to be true, and sometimes provenly true.

If you keep thinking this way, eventually you also learn how to break down problems into their fundamental units. Let's take an example problem, a common thing that all of us deals with at some point in our life: how do I lose weight?

It's simple. Scientific evidence shows that, for the average person (an important note here is that not all bodies work the same), losing weight is about living a healthier lifestyle, specifically, the following principles:

1. Eating and sleeping better, with less caloric intake
2. Exercising more, to increase calories burned

It follows that you need to eat and sleep better, and exercise more. Now you have to follow through with asking questions such as:

1. Why don't I eat and sleep better?
2. Why don't I exercise more?

With some common answers:

1. I have other priorities in life.
2. I do not have time.
3. I do not feel motivated enough.

Depending on which of the options you picked, you need to keep asking yourself questions until you arrive at the fundamental source of the problem. Only then, will you know what problem is it that you need to address. For example, the sources of the problems could look like:

1. I don't correctly prioritize my health over other things in life. This is because I don't view my health as important, even though I want to prolong my lifespan and live a healthy life, rather than one that is plagued by sickness.
2. I don't have time, because I don't plan my schedule accordingly.
3. I don't have time, because I have too many other things going on in my life. I should decide whether other things are worth doing; decide what I should cut.
4. I don't feel motivated. I don't like going to the gym. I should find other ways to keep myself active.

Once you understand that all problems can be broken down and introspected further, you'll be able to arrive at the root of all problems and solve those deeper problems rather than letting the roots continue to grow.

When you start breaking down problems into fundamental units, you'll see that the same types of problems arise in different areas in life but are all generally applicable. Here are some examples of mine:

- Physics teaches you that the laws of the universe governs us. First principles exist, and the type of thinking here transfers to our daily lives.
- Chess teaches you about thoroughly thinking and planning ahead. This is a general useful thing to think about in life.
- Large parts of computer science teaches you about how to solve problems efficiently. Problem solving is a huge chunk of our lives, and a lot of programming techniques are applicable to real life situations.
- Mathematical patterns tends to repeat itself in different parts of the real world. It is only up to the keen observer to realize the significant of this.

There are a lot of parallels that can be made everywhere in life. The most interesting ones are perhaps places where humans have spent a lot of time thinking about and continue advancing in: math, science, music, art, philosophy, and language. A conjecture here is as follows:

Often, the most successful scientists, innovators are ones that can master cross-disciplinary studies and applies the lessons from one area to another.

## First principles thinking leads to breakthrough designs

Have you ever had a time in high-school math class, when someone was able to solve something difficult, even though the teacher hasn't explained the new techniques yet? Or when someone in class discovers a new way to solve the same problem, leaving everyone, including the teacher, confused?

The reason why certain students can perform such a task, is because they see past the problem, and understand the underlying concepts of what the mathematical problem entails. They see the ground truths and are able to build from there. This is the essence of first principles thinking. Students that see beyond the formulas presented (which often is derived formulas for simplicity), to deduce the more fundamental and powerful formulas. These formulas apply more broadly to a general set of situations, and can still be used to derive the specific formulas that was presented.

When a student understands the axiomatic rules that they must not violate, they also understand how they could come up with a different solution that is consistent with the rules laid out and is completely convinced that this is an alternative solution. Other students that only understand the application of the derived formula simply stare in awe, and some of them are not convinced that the alternative solution is any better or is even correct.

Ground truths exist everywhere. In computer science, we often talk about the bounded complexities of algorithms. We often talk about fundamental tradeoffs, such as time (computational time) vs. space (storage memory) tradeoffs in algorithms. When the input of the problem, `n` is sufficiently large, we'll necessarily hit these limits. Most software engineers do not work in complex enough areas to hit these limits, but it does come up occasionally from time-to-time.

In practical software engineering, you may also hit cold, hard walls when trying to make programs run faster given real world constraints. If you ever wanted to exploit every little detail of the computer to make a program run fast, you will need to dive deeper down the layers, which includes: language runtime (if applicable), compiler optimization, memory allocation and deallocation techniques, and finally hardware architecture. Knowing the first principles of each layer, helps you make better technical decisions and tradeoffs that work best for the type of problem you're attempting to solve.

People that practice first principles thinking are able to come up with new, creative ideas that can be realized physically, in a reasonable amount of time.

## First principles thinking helps you stay critical

By the same vein that first principles thinking allows you to come up with new, creative ideas, it also allows you reject ideas that are immediately known to be inconsistent to the model or result in undesirable tradeoffs that are harder to deal with. This allows you to stay critical about solutions that are proposed, either by yourself, or your peers.

Constructive criticism of ideas is an important skill in real life, especially in more creative disciplines such as software. A program can be written differently, in many ways. How do we know which program is written better? There are many different ways to solve a problem. How do we know which way is better? Engineers that care for the trade think deeply about these problems, but often find it hard to guide their thinking. First principles thinking helps here.

In contrast, when writing general-purpose application software, engineers often don't need to think about the hard computer science tradeoffs that arises, because they don't matter in practice. Most engineers can get away with less precise thinking. The users won't notice any difference after all. With that in mind, there is less of a desire for certain engineers to criticize ideas. After all, new ideas come up all the time, and who is to judge whether one is better than the other?

The idea of doing what is absolutely necessary to appease the user is indeed correct in most places. However, formalism and rigor are also needed in sufficiently sophisticated areas, and in areas where the design needs to be stretched to the limit -- which usually means, withstanding the test of time and changing requirements. A common example here would be internal code architecture or design. This is a sophisticated and abstract area. It is important to know what tradeoffs you are trying to optimize for when you design foundational components. Internal code architecture or design is also a place where is often stretched to the limit. After all, any good software will stay around for years, and with all this time and number of changes, the design will be put to test of time.

When ideas are cross-checked with understanding by first building up from first principles for the domain, one can easily deduce whether the idea is sound, or needs modification. The challenge here perhaps, to a highly trained software engineer, is understanding what first principles exist in the problem domain. This is often a mixture of formal science, and informal observations. After all, the first principles of computer science do not translate directly to the first principles in a given real-world problem domain. There are human factors at play here that provides bouding of the problem. Thus, understanding the new problem domain is often required.

If you are able to master a problem domain, and build first principles thinking in that domain, you end up being the expert that everyone naturally consults before making any decisions in the problem space. More often than not, you'll be accurate in your analyses and conclusions.

## Final advice

As a word of caution, first principles thinking isn't for everyone -- our brains work very differently. For thinkers that do not resonate well with deep logical thoughts, a simpler and more practical advice is as follows: keep to your heart facts, principles, ideas, that you hold to be true, and try to think about them when someone discusses a new idea with you. Try to think how the new idea works -- or doesn't work with what you know.

For the logical thinkers, first principles thinking is an extremely powerful tool, but also understand that other tools exist that may be more attractive towards solution formulation. First principles thinking is most useful in solving deeply complex problem domains. Keep this in your tool belt when you need to go deep into areas, and want a lifeline attached.

For software engineers, when designing new application software, always consider whether a design is needed before making code changes. Certain changes do not require them. Consider whether the design will hold the test of time, if it needs to. First principles thinking may help here.

Finally, the real-world examples in this blogpost may not resonate with you. This is not a fault of the reader, but a fault of the author. If you still find some parts of the idea idea interesting, I'd recommend looking for other sources that may resonate better<sup>1</sup>. It also goes without saying that understanding and practicing abstract thought processes are harder said than done. With that in mind, the final advice I'll leave with you is to capture ideas that resonate with you and revisit these ideas or this post when the time is right.

<i>Footnote: I'm always looking for feedback and topics my readers might be interested in. If you'd like to contact me, my Twitter handle is [weikanglim](https://twitter.com/weikanglim).</i>

Notes:

<sup>1</sup> Mayo Oshin's Medium [blog post](https://medium.com/the-mission/elon-musks-3-step-first-principles-thinking-how-to-think-and-solve-difficult-problems-like-a-ba1e73a9f6c0) - *Elon Musks' “3-Step” First Principles Thinking* comes to mind as an article that is excellent for a broader audience.