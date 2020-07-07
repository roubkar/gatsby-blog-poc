---
path: launching-aim
date: 2020-07-07T16:56:43.047Z
title: Launching-aim
description: AIM - An open AI development environment
---
> Can tools for AI be as good as they are for the rest of software engineering?

# AI is eating software.

Back in 2015, AI grabbed the attention of builders, investors and companies. Deep learning is now mainstream because it’s a super efficient way to solve many types of problems, where we used to hardcode rules and features.

# **But AI tools are broken.**

For the rest of software, we engineers have always built awesome tools for ourselves, like IDEs, version control, packaging, containers and monitoring. Launching a production-strength website, lib or app has never been easier.

But for AI the development cycle is very long — a preprocessing bug may be discovered only after training on 1024 TPUs, or never.

![](https://miro.medium.com/max/2220/1*rEd8LuhXtjx8i2m4hJq6bw.png)

# One pain, many teams

The many teams that are solving high-value problems with deep learning are too focused on building to drop everything and work on production-strength tools for themselves and for the world. They invest just enough in throwaway scripts to survive another day.

The regular software engineers, let alone managers or product people won’t and can’t build the tools to stop pains that they don’t feel or understand. Young researchers fresh out of Stanford computer science PhD or Coursera data science courses mainly haven’t been exposed to other aspects of software engineering and respective tools ecosystems to imagine a better world.

I felt this pain building AI and its infrastructure at [Altocloud](https://www.linkedin.com/company/altocloud/) (now Genesys) where half my time was spent simply tracking and comparing experiments. It was generic work that gets repeated across thousands of teams, even within the same company. But it was nothing unique to what we were building.

# **Our vision of a better world**

Since 2017 my friend [Gor](https://github.com/gorarakelyan) and [I](https://github.com/SGevorg) have been thinking about this problem while working in our respective companies. We waited for a toolstack that fundamentally changed the way we work as AI engineers and it never came, so we decided to build it.

We wanted a toolstack that was **fast-paced** and **collaborative**, with **one source of truth**. The requirements were features to:

\- **discover**, **compare**, **tag** and **outline** the best runs for future reference

\- **track the lineage** of experiments and models

\- **navigate through** and **easily execute** interdependent experiments

And the tools had to handle the long cycles and large datasets that make AI different from normal engineering, and be customizable so we could add problem-specific insights for debugging and interpretation.

With these requirements, we set out to create an AI development environment that is 10x better than any current approach.

![](https://miro.medium.com/max/2800/1*dPZtB86mewx3lBlhGZ2olg.png)

Take control of your experiments!

# Working with AI teams

We founded [AimHub](https://aimhub.io/) and started building tools for AI teams that had the same problems and wanted awesome tools for AI. Now we’re open-sourcing and sharing the ADE — AI Dev Environment — and the version control and storage behind it:

## **[Aim Development Environment](https://github.com/aimhubio/aimde)**

AI Dev Environment (ADE) for tracking, searching and discovering experiments

## **[Aim Version Control](https://github.com/aimhubio/aim)**

Version control for AI experiments

## **[Aim Records](https://github.com/aimhubio/aimrecords)**

Storage, tracking and search for AI experiments

These are **framework-agnostic** tools for AI engineers with one goal: make building AI 10x faster.

These tools have found their home on [AimStack](https://aimstack.io/). With this blog post we are sharing it with fellow AI Engineers.Intuitive experiment management

# Free, open source and community-driven

Like all the best dev tools, these new tools for AI development are completely free, open source and community-driven and always will be.

Now it’s time to share, listen, collaborate and build more!

With these community-driven tools we hope other engineers too will use to dramatically accelerate their AI development and the adoption. On that journey we also hope to help advance the notion of open-source AI research.

Try out AIM, join our [community](https://aimstack.io/) and let’s build the next generation of AI tools together!! If you have questions — I am always happy to chat!

```
pip install aim-cli

aim init

aim de up
```

``

Go to [docs](https://docs.aimstack.io/user-guide/quick-start) for more info on how to set up your first AIM project.