# Financial Mathematics, Quant and Other Useful Resources

I've attached a few resources for people interested in Financial Mathematics, Quant Finance, Probability and some of the other things we(current MathSoc batch) might end up working on.

For now, this should be a good start.

## 1. MIT OpenCourseWare — Financial Mathematics

[MIT Financial Mathematics — full YouTube playlist](https://youtube.com/playlist?list=PLCRPN3Z81LCIZ7543AvRjWfzSC15K7l-X&si=1S0DASou5V8jduEH)

I'd suggest starting here if you're having a difficult time catching on. MIT OpenCourseWare is fairly standardized, but the course is also quite theoretical. It's a good place to build the mathematical background before moving towards the more hands-on stuff.

## 2. A Few Videos Worth Going Through

These aren't necessarily meant to be watched in any particular order. Some are directly relevant to Quant, and others are just useful for building intuition around Statistics, Probability and Mathematical Modelling.

- [Kelly Criterion — Ed Thorp and optimal position sizing](https://youtu.be/THYLv5_0Vm8?si=KU_nZeFSeYh_pYeD) — A good introduction to the idea of deciding how much capital to risk based on your estimated edge. Useful if you're interested in the mathematics behind risk and trading.
- [The Sharpe Ratio Explained](https://youtu.be/9HD6xo2iO1g?si=UEbatV7NnF4XFx6O) — An introduction to risk-adjusted returns, volatility, diversification and why returns alone don't tell you much.
- [Smoothing Splines — an introduction to flexible curve fitting](https://youtu.be/8Ae_QzwwR_U?si=rZYkbHEOrHXwsKYD) — A nice resource if you want to explore how we fit smooth curves to noisy data.
- [What Textbooks Don't Tell You About Curve Fitting](https://youtu.be/q7seckj1hwM?si=tYNq1LayJhlzx4B4) — Goes into linear regression, least squares, assumptions about noise and regularization. Worth watching if you want a better understanding of what you're actually doing when you fit a model.
- [Bayes' Theorem — a visual introduction](https://youtu.be/3jP4H0kjtng?si=Qyu1WBJeHmMdF6KM) — For getting more comfortable with probabilistic reasoning and updating beliefs based on new information.
- [A Simple Way to Learn Complex Skills — Benjamin Keep](https://youtu.be/OI_3bQ-EWSI?si=e2QoPjjtZ_1voq2k) — Not Fin-Math in particular, but I thought this was a useful video on learning difficult things, which is pretty relevant to everything else here.

Also, do look into [Very Normal — Christian P.'s Substack](https://verynormal.substack.com/?r=5sa611&utm_campaign=subscribe-page-share-screen&utm_medium=web). It has some interesting mathematical and statistical explanations, particularly if you liked the videos on curve fitting and splines.

A couple of videos on the decision-making side of Mathematics:

- [The Mathematics of Choice — Risk, Wealth and Expected Value](https://youtu.be/o-ovbHxSmuk?si=fwNFIUtrM_y-FukE) — An interesting look at why a choice with a higher expected monetary value isn't necessarily the choice everyone should make.
- [Bill Benter — How Mathematics Changed Horse-Race Betting](https://www.youtube.com/watch?v=4B0mGYZqElo) — A pretty interesting example of statistical modelling being used in the real world. More of a story than a lecture, but worth going through.
- [The Big Picture of Statistics — Very Normal](https://youtu.be/-GBppQdBF-M?si=C9OBm2XCV89jdVim) — A good overview of Statistics as a whole, especially if you're interested in understanding how different concepts fit together. Do go through it before diving into the more theoretical aspects.

## 3. Quantitative Finance — More Hands-On Resources

If you want a more hands-on experience, do look into **Roman Paolucci**, **Coding Jesus**, and the resources below.

- [Quant Guild — YouTube playlists](https://www.youtube.com/@QuantGuild/playlists) — Except for a few (click-baity) videos, the rest are goated. A lot of useful material on trading, stochastic processes, options and quantitative models.
- [Roman Paolucci's Quant Guild Library — GitHub](https://github.com/romanmichaelpaolucci/Quant-Guild-Library) — Do visit this repo. It has Jupyter notebooks corresponding to his video lectures, so you can actually work through the code instead of just watching.
- [HRT Beat — Hudson River Trading's Tech Blog](https://www.hudsonrivertrading.com/hrtbeat/) — Read through HRT's Tech Blog. It's a good place to see how some of the modelling and engineering ideas appear in quantitative trading.
- [Modeling Equities Returns: The Linear Case — HRT](https://www.hudsonrivertrading.com/hrtbeat/modeling-equities-returns/) — Do go through this write-up, and also go through the sources cited in it. It covers linear factor models, portfolio risk and performance attribution.
- [The Kelly Criterion — a mathematical explanation](https://youtu.be/-9JM9suCIHs?si=jkqme5S4tXFt9US3) — Another take on the Kelly Criterion, with more emphasis on the mathematics of long-term growth and position sizing.
- [KL Divergence — Clearly Explained](https://youtu.be/9_eZHt2qJs4?si=8UqSBLiX49KwBeQB) — Some basics that are useful for Fin-Math. KL Divergence isn't exactly an integral part of a typical Fin-Math course, but it's a statistical tool worth knowing if you're looking at probabilistic models and related pricing research.
- [Tradermath — Quant and Trading Interview Practice](https://www.tradermath.org/) — For students preparing for Quant. There are mental-math drills, probability questions and market-making games. Even if you're not into Quant, you can still do it for fun.

For people who are struggling with the theory, I'd still suggest going back to the MIT OpenCourseWare playlist. It might be a little too theoretical at times, but that foundation helps when you're trying to understand what the models are doing.

## 4. Machine Learning, Statistics and Research

- [Diffusion and Score-Based Generative Models — Yang Song (MIT CBMM)](https://youtu.be/wMmqCMwuM2Q?si=7opolhNU_MOispUp) — Originally more of an ML topic, but diffusion and score-based models are also being explored in Financial Mathematics. MIT CBMM is an underrated channel in general, not necessarily for Fin-Math in particular. There are a couple of very niche videos on Probability and Statistics that can be helpful when you're working on projects.
- [How to Read a Paper Efficiently — Prof. Pete Carr](https://youtu.be/IeaD0ZaUJ3Y?si=KySQmcJ4Xvq3vZ3j) — Do go through this if you're planning to read research papers. Knowing how to read a paper is a skill in itself, and you don't have to approach every paper like a textbook.
- [Copulas — understanding dependence between distributions](https://youtu.be/mhsTeZgip_k?si=gt8bVZrjdPKMCKcJ) — An introduction to copulas, including Gaussian copulas. Useful if you're interested in dependence modelling and the relationship between random variables.
- [Copulas 2: A Deep Dive in R — Meerkat Statistics](https://youtu.be/4JjhRx1-gU4?si=PKwXb6I7QK5uYPJM) — A fairly detailed lecture on Copulas, covering Gaussian and Archimedean Copulas, sampling methods, and Vine Copulas with practical implementations in R. Do go through it if you're interested in modelling dependencies between random variables, especially in the context of Financial Mathematics and Risk Modelling. It's a bit more theoretical in certain parts, but the coding examples should help you get a better understanding of the concepts.
- [Quant Python Stack Nobody Talks About](https://docs.google.com/document/d/1zPNDPviUlDtmfmKMazsVdQObArA-1dFZcBeqDaTpnDo/mobilebasic) — A curated list of Python libraries commonly used in Quantitative Finance, ranging from portfolio optimization and derivatives pricing to econometrics and backtesting. Do go through the document, especially if you're interested in working on projects in Fin-Math. It should give you a fairly good idea of the tools worth looking into.

## 5. Probability — Harvard Statistics 110

[Harvard Statistics 110: Introduction to Probability — full YouTube playlist](https://youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo&si=Fw9W8ZX_fFMqgUDu)

Basically Probability's CS50x. I'd strongly suggest going through this if you want to get comfortable with Probability beyond just memorizing formulas. It'll be useful for Quant, ML and Mathematical Modelling in general.

## 6. Prerequisites for B.Tech Mathematics — Mohit Tyagi

And if there are still people struggling with foundational Math (JEE Main and Advanced, not to traumatize you), Mohit Tyagi is a good channel to look into.

For now, I've attached the playlists for the topics you might want to revise before getting deeper into B.Tech Mathematics. You don't necessarily have to cover everything if you're already comfortable with the basics; just pick up the topics where you feel you're lacking.

1. [Functions — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMad5zB0Dh6gUw1eYK8dN7hP7&si=XZA7up_iD7am9B8h)
2. [Limits — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaexM2nxZt512ESPt83EshJq&si=Kw4sWvF1WBLmgBm6)
3. [Continuity — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMads1bsxLYBoJOLA3bWsY7mK&si=aOWJPLt1G2Z5VB-r)
4. [Differentiability — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMafj2vfy6rQHtTzgA_TnJsZ_&si=nEnUx75UYaazhslj)
5. [Differentiation — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaeewzwCJPpL65y1HV0VAiC4&si=hjmeue35BL6GOAbf)
6. [Applications of Derivatives — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMacK_BU3vfAcCOuOJtQOHNfI&si=-xJCFrV_dje46xaL)
7. [Inverse Trigonometric Functions — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMacqcUtkJPTPXSrvNm_5NK-v&si=mpZYwRYiF2AVEmI5)
8. [Indefinite Integration — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMacK7OyqPwHe0rvG4KqxFIum&si=dQRTR4WNZS1deLKv)
9. [Definite Integration — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMafGD8xJhm9IioyF_norREYN&si=mW0Qgmd-jrCESh7M)
10. [Area Under Curves — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaf8TqINqRXRlWeuFgl6fBgf&si=NTNXEQSveXJq5b_x)
11. [Differential Equations — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaeukUFW7G-KjoL-K2T3B3Mg&si=IMjFbN6pXvDWUAjx)
12. [Matrices — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMafsNaawDfrQl6EhgdEiWVD6&si=ExSwh3wdbDHTRzsJ)
13. [Determinants — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaex9aIhynPtk3ZO-xO_G2kJ&si=autClB4zxAJUbyJZ)
14. [Permutations and Combinations — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMae1vVGOC3Ptr4qXYZOqXvJa&si=YpeAHRXr66VyBR0y)
15. [Mathematical Reasoning — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMacsfE8rJJu5YRDrW19YbbAx&si=uIhJRCkbL1mgCpTY)
16. [Probability — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaf-WePkSulK_zt0yfQUrZgE&si=rCzumqA-BDxWQoh0)
17. [Statistics — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMadco0ISV4gL7BEkzs7ki6lm&si=tT4q2B0hxa8XPPtJ)
18. [Vector Algebra — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMafmea0RnicbuLD6Ly2EIr0X&si=zF0ff_PRFw3eFFSn)
19. [Complex Numbers — playlist](https://youtube.com/playlist?list=PL_A4M5IAkMaeLzehBWWVD_EZL7EuaVP-X&si=wnQDWn06RgGP_Dac)

**Note for CAM students:** I'd suggest covering the entire syllabus from his playlists if you feel that you're lacking somewhere, because I haven't linked the Geometry part of it and a few other topics.
