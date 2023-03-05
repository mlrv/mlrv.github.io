---
title: How to write good software
---

The most elegant piece of software is of very little value if it doesn't solve the problem it was intended to solve.

As software engineers, our main purpose is to provide solutions to problems. Often, those solutions come in the form of written code, but they don't have to. Code, or software in general, is merely a tool.

Nonetheless, being able to [[Designing Data-Intensive Applications|write good software]] will most likely make us better engineers, so it's reasonable to spend time and effort in trying to understand how we can get better at it, but also what good means in this context.

For any non-trivial project, the main challenge is understanding the domain. That's where intrinsic complexity comes into play. Writing software in the domain of nuclear medicine is likely to come with a lot of complexity that derives from the field itself, not the project. Incidental complexity, on the other hand, does not derive from anything other than our own doing. More than twenty years ago, Dijkstra wrote an [incredible paper on this topic](https://www.cs.utexas.edu/~EWD/transcriptions/EWD13xx/EWD1304.html), this is the passage I like the most about it.

  >  [...] most of our systems are much more complicated than can be considered healthy, and are too messy and chaotic to be used in comfort and confidence. The average customer of the computing industry has been served so poorly that he expects his system to crash all the time, and we witness a massive worldwide distribution of bug-ridden software for which we should be deeply ashamed. 

In the last decades, software engineers and computer scientists have developed a lot of techniques aimed at reducing the incidental complexity of a software project. Paradigms, frameworks, algorithms, all designed to help us humans make sense of the increasingly complex landscape of software engineering.

Of all these techniques, the one that resonated the most with me was that of [[Functional Programming]].