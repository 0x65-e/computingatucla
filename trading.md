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

SWE compensation tends to be less variable than the quantitative roles, although it is more variable than software engineering compensation in other industries. Pay transparency in the tech industry leads to more standardized compensation for SWEs when compared to the quantitative roles. Quant firms tend to have higher compensation for SWEs than other industries (especially for new grads), though they often have higher hiring bars, performance standards, and longer working hours.

### Site Reliability Engineer (SRE)

Although the role is found at most quant firms, the title is far from standard. Site Reliability Engineer is a common title outside of the trading industry (especially at Big Tech companies like Google, where the role originated in 2003), but trading firms may also call them Production Engineers, Reliability Engineers, Application Engineers, or Trading Operations Engineers. Regardless of the title, the role usually focuses on the operations pillar, with SREs responsible for maintaining the stability and uptime of trading systems. This involves application monitoring, automated deployment and infrastructure, change and release management, incident management, and developing support tools. They are often the first line response when things go wrong, and frequently provide support to QTs or SWEs. Infrastructure knowledge is critical for an SRE, but depending on the firm, they may also require solid programming experience to implement automated deployments, infrastructure-as-code, or [CI/CD practices](https://en.wikipedia.org/wiki/CI/CD).

Most SREs come from similar backgrounds to software engineers. Like in tech firms, a Bachelor's degree is the standard qualification. Check out the [software engineering guide](/guides/fields/software) for more information.

SRE compensation is very similar to SWE compensation, especially since the much larger number of SREs in the tech industry provides greater pay transparency and more opportunities. Some firms have the same compensation structure for both roles, but others offer lower compensation for SREs.

### Hardware Engineer

Hardware Engineer is probably the least-known role in quantitative trading (among students), and also tends to have fewer roles in the industry, but it is no less important (or lucrative) a career. Hardware Engineers are tasked with developing custom FPGAs and ASICs to fuel the low-latency race among the fastest market participants. This often involves processing market data, serializing and submitting orders, and very high-speed networking (10G, 25G, and beyond). Increasingly, some firms are seeking out hardware engineers with experience in machine learning acceleration, which may be an area of interest to current students. Hardware engineers need a thorough mastery of RTL development in a hardware description language (HDL), computer architecture, and FPGA/ASIC architecture. Depending on the role, other nice to have skills include experience with hardware verification, knowledge of other high-speed interconnects (e.g. PCIe), and even software engineering skills (typically in a low-level language like C).

It is unusual to find a Hardware Engineering position that is not entirely in core development.

Like software engineers and SREs, hardware engineers usually do not require a graduate degree, although graduate classes may provide an opportunity to study advanced topics not generally available to undergrads at many institutions (like high-speed networking or machine learning accelators).

Hardware Engineer compensation is often on-par with or slightly higher than software engineering, with less variability. Because there are fewer roles for Hardware Engineers, a specialized skillset or depth of experience can command a significant premium over SWEs or hardware engineers in other industries.

## Majors

### [Statistics and Data Science B.S.](https://catalog.registrar.ucla.edu/major/2024/StatisticsandDataScienceBS)

The lower division requirements of the Stats major cover single- (MATH 31A and 31B) and multivariable calculus (MATH 32A and 32B), linear algebra (MATH 33A), along with introductory statistics (STATS 10) and an intro to programming using R (STATS 20).

The upper division requirements for the major are split into three main series:
* The 100A/100B/100C series covers core theory of probability, statistics, and linear statistical modeling
* The 101A/101B/101C series covers applied analysis and regression, and generally includes modeling projects
* The 102A/102B/102C series covers computational statistics and simulation using R

The Statistics major only has two free electives to choose from. There are a lot of potential options to choose from, but the most important for anyone interested in quantitative trading by far is statistical finance (STATS C183) which covers portfolio theory and options pricing. Other courses of interest for your second elective choice include time-series statistics (STATS 170), machine learning (STATS C161), or Bayesian statistics (STATS C180).

The biggest downside of the Stats major is that all of the computing courses are taught using R, which is widely used for statistical computing, but lacks some of the general-purpose introductory software engineering courses (like data structures and algorithms) that are necessary for roles with an emphasis on core development. Python is also a much more popular language in the industry, so Statistics majors would be well-served by taking extra courses in Python (PIC 16A and 16B or STATS 21) even though these are not part of the major requirements.

The Stats major stands out for the large number of applied courses in the curriculum, which are important for building skills and experience if you want to go directly into the trading industry from your undergraduate studies. It's best suited for **Quantitative Trader** roles. The lack of upper-division mathematics courses can pose more of a challenge for pursuing graduate study for those interested in **Quantitative Researcher** positions, although many Stats majors do pursue graduate study in Statistics. As mentioned previously, the lack of any software engineering course content makes pursuing any Engineering positions difficult, likely including most **Quantitative Developer** positions.

### [Data Theory B.S.](https://catalog.registrar.ucla.edu/major/2024/DataTheoryBS)

The Data Theory major is a relatively new major somewhat unique to UCLA, first introduced in 2019. It's a mix between statistics and mathematics courses, with a little bit more on the computational side than a pure Statistics or Mathematics major. The lower division requirements cover the same foundations as Statistics, with the addition of programming courses in C++ (COMPTNG 10A or CS 31) and Python (STATS 21), and a course unique to Data Theory majors that covers data-driven modeling, analysis, and visualization (MATH 42).

The upper division requirements are also a mix of statistics and mathematics courses. The major requires almost all of the core statistics courses and adds upper-division linear algebra (MATH 115A), real analysis (131A), applied linear algebra and optimization (MATH 118), machine learning (MATH 156), and a free elective, which can be on applied numerical methods, optimization, finance, or algorithms. It also has an upper division course on commonly used tools in data science (STATS 147), and an ethics course on the impacts of data (STATS 184). Like the Statistics major, Data Theory also has a capstone course, which can be either a consulting experience or data science research.

Compared to the Statistics major, Data Theory boasts more background in computer science (especially Python and its libraries), and more mathematical foundations in key areas like linear algebra and optimization. Similar to statistics, it is a good choice for aspiring **Quantitative Traders**, and the additional mathematical foundations provide better preparation for graduate study if you're interested in pursuing a **Quantitative Researcher** position. Most of the computer science courses focus on programming for data science, which is helpful for QR roles but may be a harder sell for **Quantitative Developer** roles that are more bent towards software engineering.

### [Mathematics B.S.](https://catalog.registrar.ucla.edu/major/2024/MathematicsBS)

*This section also includes [Applied Mathematics](https://catalog.registrar.ucla.edu/major/2024/AppliedMathematicsBS), since the major requirements are very similar.*

The Mathematics and Applied Mathematics lower division requirements include single- (MATH 31A and 31B) and multivariable calculus (MATH 32A and 32B), linear algebra (MATH 33A), a full year of physics (with the option to swap some for chemistry or biology for pure math), and one introductory C++ programming course (PIC 10A).

The upper division requirements share linear algebra (MATH 115A) and analysis (MATH 131A, 131B, and 132). Pure math adds algebra (MATH 110A and 110B) and differential geometry (MATH 120A) while applied math has a course on modeling (MATH 142) and two required sequences chosen from probability and statistics, numerical analysis, or differential equations. Both majors offer electives from the math department or the core statistics series (100 through 102), though pure math has five electives to applied math's four.

Both majors' single required course in programming is a weak spot for most roles. Both majors have the option to pursue a Specialization in Computing, which requires two more courses in C++ (PIC 10B and 10C), a course in Python (PIC 16A) [Java and web programming are options, but not recommended for the trading industry], discrete structures (MATH 61), and two math electives on numerical methods or machine learning. This is only four courses beyond the requirements for either major, but it will help build practical skills for passing interviews.

The mathematics majors provide the best foundation for graduate study for **Quantitative Researchers** (especially aided with a Specialization in Computing). Orienting electives towards statistics courses can be good for **Quantitative Traders** (although it can be difficult to enroll in statistics courses as a non-major). Even with a Specialization in Computing, a **Quantitative Developer** role may still be a hard sell, as it would benefit from a deeper understanding of software engineering and especially of systems programming.

### [Mathematics/Economics B.S.](https://catalog.registrar.ucla.edu/major/2024/MathematicsEconomicsBS)

The Mathematics/Economics major includes all of the lower division math courses of the pure or applied math majors, but drops the physics/chemistry options in favor of introductory micro- (ECON 1 and 11) and macroeconomics (ECON 2) courses. The upper division courses continue the theme, sharing linear algebra (MATH 115A) and analysis (MATH 131A and 131B) while tacking on intermediate micro- (ECON 101) and macroeconomics (ECON 102) and a course in econometrics (ECON 103).

The most interesting required course in the major is mathematical finance (MATH 174E or ECON 141 or STATS C183). In particular, this can give students an introduction to financial instruments like futures and options, and the complex topic of options pricing. MATH 174E is specifically designed for Math/Econ students, and may be difficult for other mathematics majors to enroll in due to typical course capacity.

Like pure and applied mathematics, one of the weak points for some of the roles on this list is a lack of computing courses. Everything said above in regards to the Specialization in Computing holds for Math/Econ as well. The other downside of Math/Econ when compared to the other majors in the Mathematics department is its lack of elective choices. The entire major only has three electives, two in economics and one in mathematics (which is restricted to a small selection of courses). However, several of the elective choices for pure or applied math majors would likely have gone to courses that are part of the required curriculum for Math/Econ majors, including mathematical finance and introductory probability/statistics.

Overall, the Math/Econ major is very well-rounded and deserves its status as a popular choice for students pursuing **Quantitative Trader** and **Quantitative Researcher** roles. Math/Econ may be good preparation for a **Quantitative Developer** role with an emphasis on strategy research, but it is at a disadvantage to other majors on this list for more general **Software Engineering**. Every role on the list would likely benefit from a Specialization in Computing.

### [Mathematics of Computation B.S.](https://catalog.registrar.ucla.edu/major/2024/MathematicsofComputationBS)

The Mathematics of Computation major is a mix of about 60% math and 40% computer science. It shares the full suite of lower division math classes (calculus, linear algebra, and differential equations) with other math majors, but also includes Discrete Math (MATH 61) and the full three-course introductory computer science series (I recommend taking CS 31, 32, and 33 instead of the Math department's C++ programming courses).

The upper division courses are split between math and computer science:
* Core math courses in linear algebra (MATH 115A), real analysis (MATH 131A and 131B), and applied numerical methods (MATH 151A and 151B)
* Three computer science electives
* Six math or statistics electives

The major provides an incredible amount of flexibility with course selection, more so than any other major in the Math department. It can be shaped to fit almost any role on the list. With a focus on more statistics electives (although these may be harder to enroll in), the major has most of the preparation of the Statistics or Data Theory majors for **Quantitative Traders**, but with more mathematical foundations for **Quantitative Researchers**, and the opportunity to take machine learning courses from the Computer Science department. For **Software Engineer** roles, many essential topics like algorithms and machine learning are offered in both the Math and Computer Science departments, so you have the flexibility to choose the approach you prefer. Because the electives are unrestricted, Math of Comp majors have the ability to specialize in anything that Computer Science majors can (including systems and architecture), though only in one or two areas. With its mixture of math, statistics, and computer science, Math of Comp is the best major for **Quantitative Developers** despite the varied responsibilities of the role.

### [Computer Science B.S.](https://catalog.registrar.ucla.edu/major/2024/ComputerScienceBS)

*This section also includes [Computer Science & Engineering](https://catalog.registrar.ucla.edu/major/2024/ComputerScienceandEngineeringBS), since the major requirements differ by only 3 Electrical Engineering courses.*

The Computer Science major provides a very broad education in theoretical computer science. The lower division prerequisites cover the full suite of math classes (calculus, linear algebra, and differential equations), including Discrete Math (MATH 61), as well as physics. The introductory computer science series covers basic C++ programming (CS 31), data structures (CS 32), machine structures (CS 33), common software construction tools (CS 35L), and digital logic (CS M51A).

The upper division courses cover most areas of computer science, including operating systems (CS 111), networking (CS 118) [no longer required as of Fall 2025], software engineering (CS 130), programming languages (CS 131), architecture (CS M151B), algorithms (CS 180), and theory of computing (CS 181). The major provides five free [electives](https://registrar.ucla.edu/academics/course-descriptions?search=COM+SCI) [or seven, as of Fall 2025], which cover a range of topics (though largely focused on machine learning).

One benefit of being housed in the School of Engineering is that Computer Science majors have half the GEs of L&S students, and no foreign language requirement, leaving more room to take technical classes. As engineers, Computer science majors have a [Technical Breadth Area](https://www.seasoasa.ucla.edu/undergraduate-technical-breadth-area-tba/) that requires students to take courses outside their major department. This can include courses in other engineering departments, mathematics, or the most popular options, digital humanities or technology management. 

In addition, the [Sci-Tech Electives](https://www.seasoasa.ucla.edu/cs-scitech/) of the CS major (but not CS&E) allow you to take courses from a number of departments across campus. While you can technically fulfill this requirement with additional CS electives [this option is no longer available for students entering after Fall 2025], I don't recommend this path. At present, there aren't enough elective offerings to take eight computer science electives. You can take Electrical Engineering courses for more of a focus on hardware (or to take advantage of computing courses offered solely by the ECE department, like Deep Learning (EC ENGR C147A and C147B) or Computer Vision (EC ENGR 149)), or courses in Statistics and Mathematics (which is helpful for those hoping to go into roles involving strategy research).

The Computer Science (and CS&E) major is very flexible, and is a good choice for those aiming for **Software Engineer**, **Site Reliability Engineer** (CS 35L and 118 especially), and potentially (with the right TBA and Sci-Tech choices in Statistics or Mathematics) even **Quantitative Developer** roles. With a TBA and Sci-Tech in Electrical Engineering, the major ends up being very similar to the Computer Engineering major (see below), which is a good choice for **Hardware Engineers**.

I've seen many Computer Science students try for **Quantitative Trader** roles. With a TBA in mathematics and Sci-Tech in statistics, you could cover several of the core courses in the Statistics or Data Theory majors. However, enrollment pressure on the Statistics department makes this route difficult to pursue practically, and you may need to declare a Statistics double major or minor to actually get into courses. With machine learning CS electives, this could be a viable route for **Quantitative Researcher** roles as well.

### [Electrical Engineering B.S.](https://catalog.registrar.ucla.edu/major/2024/ElectricalEngineeringBS)

*This section also includes [Computer Engineering](https://catalog.registrar.ucla.edu/major/2024/ComputerEngineeringBS), since the major requirements are very similar and they prepare students for similar roles.*

Electrical Engineering and Computer Engineering share most of their lower division courses with the Computer Science major, and all the same math and physics preparation. The upper division required courses are mostly in Electrical Engineering, although with some opportunities to take Computer Science electives. Electrical Engineering and Computer Engineering majors can choose to take Computer Science courses for their [Technical Breadth Area](https://www.seasoasa.ucla.edu/undergraduate-technical-breadth-area-tba/), which provides more flexibility to specialize in topics like operating systems, algorithms, and databases. CE majors can elect to take Electrical Engineering for their TBA, which would make the major very similar to an EE major with extra computer science courses.

Electrical Engineering and Computer Engineering are the best choices for a **Hardware Engineer** role, bar none. With the right TBA and elective selections, either major could provide adequate preparation for a **Software Engineer** role as well (and may have a slight advantage for specialized low-latency positions). Like the Computer Science major, EE and CE suffer from a lack of statistical preparation for any of the quantitative roles, but without the ability to add a Statistics Sci-Tech.

## Minors

Coming soon!

## Clubs

Coming soon!

## Recommendations

Coming soon!
