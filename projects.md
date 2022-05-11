---
layout: page
title: Projects
permalink: /projects/
---

<p>
These are some of my past Projects/Research
</p>

## Nonlinear Feedback Shift Registers
During Wolfram Summer School, I have conducted a research on Nonlinear Feedback Shift Registers (NFSRs). I have formulated functions to test whether certain combinations of tap positions and nonlinear function produce the sequence of maximal length, which is length 2^n-1 (n is the length of the shift register). This is because there are only there are 2^n possible states and the sequence of all 0s cannot evolve to any new state. I tested all NFSRs with 2 taps and 3 taps for n<16, and all NFSRs with 4 taps for n<10. (Some notable nonlinear feedback functions were further tested with bigger length). I then ran several statistical randomness tests such as the equidistribution test, the serial test, and the poker test, to identify combinations that produce random sequences. I also made some analyses of the tap positions and nonlinear functions that produce long random sequences. The following function give the list of 3-tap nonlinear feedback shift registers that produce sequences of maximal length.

You can find details <a href="https://community.wolfram.com/groups/-/m/t/1135615">here</a>

## Riemann-zeta Function and Analytic Continuation
For this research, I have studied about Riemann-zeta function and its analytic continuation. Riemann-zeta function is widely used in statistics, physics, and mostly importantly, in analytic number theory. This function provides so much valuable information linking the distribution of prime numbers. However, in order to understand this function beyond some domain, we need to learn about the analytic continuation of this function, which requires implementation of complex analysis. The tools we learned during the course, such as integral over complex contour, Residue Theorem, Liouville’s Theorem, and etc. were essential in understanding how the analytic continuation is performed and what kind of characters related functions have.

You can find details <a href="https://drive.google.com/file/d/1yiqpNkjNgVeOqNNzELpA7UJ9pdyAq7Qk/view">here</a>

## When and Where Do Quant Models Fail?
With the development of computer software, quantitative models have been widely used to determine the value of financial assets and construct investment portfolios. After seeing the quantitative investment models survive the value factor struggles during the internet bubble in the early 2000s, many portfolios managers have commonly used quantitative signals such as value and momentum to make investment decisions. In fact, many quantitative equity managers had enjoyed strong performance, which resulted in attracting significant assets, until the quant meltdown in 2007.

These quant models were beneficial not only in finding patterns that allow the analysts to make predictions about the price and direction of securities but also in constructing portfolios based on their strategies. One common strategy that leveraged quantitative models were market-neutral statistical arbitrage strategies, which will be discussed in more detail in the following section. These basically had no significant beta exposure (i.e., they were immune to market gyrations). Because the goal of the hedge funds was to make the highest risk-adjusted return, many of them have employed statistical arbitrage strategies and expected that their losses would be limited.

However, during the week of August 6th in 2007, many hedge funds that used quantitative models to managing portfolios have experienced huge losses. It was especially shocking that most of the hardest-hit funds were the ones that were using statistical arbitrage strategies, which were assumed to be market-neutral by construction. This resulted in losses ranging from -5% to -30% for the most consistently profitable quant funds in the history. Such movements were so unexpected that David Viniar, Chief Financial Officer of Goldman Sachs, commented “we were seeing things that were 25-standard deviation moves, several days in a row.”

Nowadays, quant models are more widely used in financial industry. Many of the funds are now using more sophisticated tools like machine learning and artificial intelligence to better use data to making investment decisions and constructing portfolios. Thus, it has become more important to understand when and where these quant models can go wrong so that we can prepare for and prevent from quant crisis.

In the following sections, I will first discuss about what we refer to as quant models and how those quant models work. Then, I will discuss about historical cases in which quant models have failed and some possible causes and explanations to the events. Finally, I will provide some implications to the findings and close with the conclusion.

You can find details <a href="https://drive.google.com/file/d/1fGAEur1bfLt5Lzi1ypOguZ6-bPZ4bxt9/view?usp=sharing">here</a>
