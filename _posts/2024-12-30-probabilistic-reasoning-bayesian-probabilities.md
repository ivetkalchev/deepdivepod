---
layout: post
title: "My Ongoing Journey with Bayesian Probabilities"
date: 2024-12-30
excerpt: "This post discusses probabilistic reasoning and Bayesian probabilities..."
tags: ["machine learning", "probabilities", "bayesian"]
---

The introduction to _Data Analysis: A Bayesian Tutorial_ by D.S. Sivia and J. Skilling offers a clear and motivational perspective. It combines philosophical depth with practical insights, making the Bayesian approach seem both intuitive and compelling. Their unapologetically opinionated stance demystifies the field, presenting it not just as a set of tools but as a coherent way of thinking about uncertainty and inference.

The book emphasizes how Bayesian methods are rooted in logical reasoning and align with the way we naturally update our beliefs when faced with new evidence. The authors base their treatment of probability theory on Cox's theorem, which derives the laws of probability for "optimal decision-making under uncertainty." This framework connects deeply with the current debates around the reasoning abilities of machines, especially with the rise of generative AI models like ChatGPT. In my opinion, this discussion makes Sivia's book, along with E.T. Jaynes' work, more relevant than ever.

As an electrical engineer, this wasn’t my first exposure to probabilities. But it was the first time the subject became compelling and motivating to me, helping me appreciate the philosophical elegance of the Bayesian framework.

It’s worth noting that this isn’t a book about machine learning. For those seeking a machine learning perspective, I recommend _Pattern Recognition and Machine Learning_ (PRML) by Christopher Bishop or the late David Mackay’s foundational work. Bishop has also written a more recent book on advanced developments in machine learning. However, even for readers primarily interested in AI, I strongly recommend reading at least the introduction to Sivia's book for its discussion of Cox's theorem. It’s a must-read for anyone curious about the interplay of math, philosophy, and artificial intelligence.

To understand how context shapes understanding, I’d also suggest watching the example shared by 3Blue1Brown. While his approach isn’t explicitly Bayesian, he illustrates the importance of context in probabilistic reasoning quite effectively.

For example, any probability distribution can be expressed as:

P(X1,X2,X3,…,XN)=P(XN∣X1,X2,…,XN−1)P(XN−1∣X1,X2,…,XN−2)…P(X1)P(X_1, X_2, X_3, \ldots, X_N) = P(X_N | X_1, X_2, \ldots, X_{N-1}) P(X_{N-1} | X_1, X_2, \ldots, X_{N-2}) \ldots P(X_1)

This decomposition highlights how context is encoded in conditional probabilities.

Often, critics of generative AI claim it is "just predicting the next token." However, this argument is weak if it’s used to assert limitations of probabilistic models. If you accept probabilities as a valid language for modeling, then predicting the next token isn’t limiting in itself—any distribution can be expressed in this form. The limitation lies in the specifics of the models (e.g., transformer architectures), not in the concept of next-token prediction. A more nuanced debate would be whether predicting the next token provides sufficient signal for systems to learn a robust internal representation.
