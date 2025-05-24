---
layout: default
permalink: /guides/fields/trading
redirect_from:
  - /guides/fields/quant
---

# Guide to Quantitative Trading and Finance at UCLA

Quantitative finance has exploded in popularity among college students in the last half decade. Increasingly, UCLA students and even prospective admits are asking about UCLA's industry connections, name recognition, and placement rates at firms in the quant finance field. As long as the compensation remains exceptionally strong in the industry, this trend will likely continue. This guide will be a roadmap to the best majors, minors, and courses for those interested in quantitative finance at UCLA.

This guide is meant to be comprehensive and used as a reference, so please use the Table of Contents below to navigate to the most relevant section.

##### Table of Contents

* Table of Contents
{:toc}

## What is Quant Trading?

Coming soon!

## Roles

Frequently, a prospective student interested in quant finance will ask a question like "how good is UCLA for quant?" This is a frustratingly vague and ill-defined question that hinders any sort of useful answer. There are several thing that need clarifying before an attempt at answering can be made. First, what part of quantitative finance are you insterested in? Second, what do you mean by "good" — good in terms of academic preparation, career support, industry connections, student culture, or some other axis? (Or perhaps, like Bilbo Baggins, you mean [all of them at once](https://www.goodreads.com/quotes/14559-good-morning-said-bilbo-and-he-meant-it-the-sun)). We'll focus on clarifying the first question, and hopefully the other sections of this guide can shed some light on the second part.

The quantitative finance industry is large and includes a variety of participants. Typically, students or prospective students are interested in proprietary ("prop") trading firms, market makers, and hedge funds, since these types of firms tend to offer higher compensation than other participants (investment banks, asset managers, and brokers). The structure and responsibilities of roles at these firms can vary, but are often broken down into several categories that we'll cover in turn.

Each role is a blend of the three primary components of quantitative trading:
* **Strategy Research**: Developing new trading ideas, analyzing market data, designing features and signals, modeling, and optimizing portfolios. Requires statistical knowledge and mathematical foundations (and often machine learning as well) and an intuition for trading behavior.
* **Core Development**: Building execution systems, trading platforms, infrastructure, and low-latency optimization. Requires expertise in programming and software development. May require more specialized skills depending on the role (networking, distributed computing, systems programming, optimization).
* **Operations**: Monitor strategies, ensure stability and uptime, respond to real-time market changes, and sometimes make discretionary trading decisions. On the technical operations side, requires Linux knowledge, networking, monitoring and alerting tools, and devops tooling. On the trading operations side, requires market structure and trading intuition, analytical skills, and understanding of risk.

### Quantitative Researcher (QR)

You'll sometimes hear quant researchers referred to as Quant Analysts in an investment banking context. QRs are mostly tasked with strategy development, and they require the most thorough financial and statistical knowledge. At some firms (especially larger ones), QRs may be solely responsible for generating new trading ideas and signals, but at other firms they are involved in the core development as well. This is more common among "pod shops" (also known as a multi-manager firm), where the firm allocates capital to separate small teams (or "pods") that make independent trading decisions and pursue different strategies. Larger teams, and some semi-independent pods, might have enough personnel dedicated to core development or shared between pods so that QRs can focus mainly on strategy development. This is neither a good or bad thing, but is a matter of personal preference depending on your interest in the type of work you want to do.

Most QRs typically have a graduate degree (PhD or MS), although some QRs do come directly from an undergraduate program (almost exclusively through a QR internship at most firms). Quant research roles demand rigorous statistical preparation, and frequently an in-depth knowledge of machine learning as well. Software engineering skills may be a focus for roles that include core development responsibilities, although they often take second place to statistical knowledge. QRs share many similarities with Data Scientist roles at other firms, so check out the [guide to data science](/guides/fields/datascience) if you're interested in this area.

Quant researchers' compensation is typically very performance-based, since their contribution to the performance (profit and loss, or P&L) of the trading strategy is easier to measure. As a result, QRs tend to have more variable pay, a larger pay disparity between over- and under-performers, and less stability compared to core development roles.

### Quantitative Trader (QT)

A quantitative trader is a very broad role that varies between different firms. Typically, QTs are a mix of strategy research and operations, although a QT might be skewed much more towards one pillar than the other at different firms or even on different teams at the same firm. At the highest level, a QT uses quantitative models to execute trades. They may be involved in the model development, or that might be largely the domain of the quant researchers. Either way, QTs will often work closely with QRs, providing feedback on model performance, relaying insights into market behavior, and requesting improvements to aspects of the model. QTs will typically be required to be at their desk monitoring or making trades during market hours. Some QTs make discretionary trading decisions, like taking a position in advance of a news event or making a market in response to a client request, and they may have a wide degree of autonomy in constructing a portfolio. They may also be resonsible for setting parameters that are inputs to the quantitative models based on market conditions. Some fully systematic firms or teams (especially those employing high-frequency strategies) may not have any QTs to make discretionary trades, although they usually have someone tasked with monitoring the system's trading behavior in case of an emergency.

Quant traders are much more likely than quant researchers to be hired directly with an undergraduate degree, although like QRs, an internship is often the main pipeline. QTs rely more on good intuition of probability and risk, fast and accurate decision making ability, and trading instinct more than graduate-level knowledge of statistical modeling (although that is important for QTs involved in model development). QT interviews often test the candidate's knowledge of probability and ability to make decisions under pressure. This requires more specialized preparation than the other roles on this list.

Like QRs, QT compensation is very performance-based.

### Quantitative Developer (QD)

A quantitative developer sits in the middle ground between a quant researcher and a software engineer (and may even be called a quantitative software engineer), but the role varies the most of any on the list. QDs may have some mix of strategy research and core development, but the exact composition varies wildly. Some QDs may be more towards the core development side, but specialize in implementing research tools (like a backtesting engine) or productionizing and implementing trading strategies. Some QDs may be involved in strategy development, in which case there is not very much difference with a QR who is also tasked with core development. At other firms, all software engineers that work directly on the trading platform are called QDs. QDs will usually work closely with both QRs and SWEs since there is often a high overlap in their roles.

Since the QD role is so varied, it is difficult to pin down general requirements. QD roles that include strategy research tend to have requirements more similar to a QR, with at least a Masters degree preferred, and an emphasis on statistical knowledge. QD roles that skew towards core development often have requirements very similar to a software engineer (see below). It is somewhat unusual for new graduates to be hired as quantitative developers; often, firms will internally promote a software engineer with several years of experience into a position that involves strategy research, or retitle a QR who enjoys working on core infrastructure.

Compensation for QDs also skews towards either the QR or SWE model, depending on role responsibilities. As a general rule, the more involved a role is in strategy development, the more the compensation will be based on performance and have a larger pay disparity.

### Software Engineer (SWE)

Software engineers are employed in a variety of roles by quantitative finance firms. Many roles are nearly analogous to software engineering roles at firms in the tech industry, since they don't require specialized financial knowledge. Here's a sample of responsibilities that a software engineer might find at a trading firm:
* Developing market data capture and storage pipelines
* Maintaining and expanding distributed computing clusters
* Integrating with external data providers and third-party vendors
* Creating analysis tools
* Developing interfaces and dashboards to display trading information
* Building systems to monitor firm risk and ensure regulatory compliance
* Improving internal developer tooling and productivity

These types of roles are almost purely in the core development corner, with potentially some operations requirements for critical systems.

Additionally, software engineers may be employed in more specialized roles, which includes developing autotrading software, order management systems, execution routing, and optimizing for low-latency trading. These types of roles have a higher likelihood of interacting with the quantitative roles, although they usually do not involve strategy research.

Software engineers at quant finance firms usually do not require any different preparation than software engineers in other industries. Even roles that work on trading-critical components do not expect specialized financial knowledge or statistical preparation. For more information on software engineering in general, check out the [dedicated guide](/guides/fields/software).

SWE compensation tends to be the least variable when compared to the quantitative roles, although it is more variable than software engineering compensation in other industries. Pay transparency in the tech industry leads to more standardized compensation for SWEs when compared to the quantitative roles. Quant firms tend to have higher compensation for SWEs than other industries (especially for new grads), though they often have higher hiring bars, performance standards, and longer working hours.

### Site Reliability Engineer (SRE)

Although the role is found at most quant firms, the title is far from standard. Site Reliability Engineer is a common title outside of the trading industry (especially at Big Tech companies like Google, where the role originated in 2003), but trading firms may also call them Production Engineers, Reliability Engineers, Application Engineers, or Trading Operations Engineers. Regardless of the title, the role usually focuses on the operations pillar, with SREs responsible for maintaining the stability and uptime of trading systems. This involves application monitoring, automated deployment and infrastructure, change and release management, incident management, and developing support tools. They are often the first line response when things go wrong, and frequently provide support to QTs or SWEs. Infrastructure knowledge is critical for an SRE, but depending on the firm, they may also require solid programming experience to implement automated deployments, infrastructure-as-code, or [CI/CD practices](https://en.wikipedia.org/wiki/CI/CD).

Most SREs come from similar backgrounds to software engineers. Like in tech firms, a Bachelor's degree is the standard qualification. Check out the [software engineering guide](/guides/fields/software) for more information.

SRE compensation is very similar to SWE compensation, especially since the much larger number of SREs in the tech industry provides greater pay transparency and more opportunities. Some firms have the same compensation structure for both roles, but others offer lower compensation for SREs.

### Hardware Engineer

Coming soon!

## Majors

Coming soon!

## Minors

Coming soon!

## Clubs

Coming soon!

## Recommendations

Coming soon!
