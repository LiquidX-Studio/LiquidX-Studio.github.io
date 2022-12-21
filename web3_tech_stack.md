---
layout: default
title: Building the foundation for Web3 apps and services
description: languages, tools, and technologies used to build Web3 apps and services
---

# Languages, tools, and technologies to build a solid foundation for Web3 apps and services

![img](./img/buildingWeb3Foundations.png)

In the last few quarters, the liquidX studio's engineering team has built and shipped several web3 apps and services successfully.  

The web3 apps are built on a number of components and consequently requires one to choose between a variety of languages, platforms, services, and architecture components.  Our engineering team has tried  and tested a bunch of candidates before selecting the set that allows us to balance the tradeoffs between speed, quality, and other desired metrics.

# Target metrics
The architecture we choose and the tools and languages we choose usually is defined by the business goal we are trying to achieve.  The following list captures the metrics we choose to optimize, *your mileage may vary*.

## Quality
Although quality is on the top of the list of any software product, it is critical for web3 apps:
- First, the web3 apps' functionalities are often coupled with the value of the NFT or the currency a user holds.  As a result, a critical bug that hinders/alters the app's functionalities may have real-world negative financial impact for the users.
- Second, the value of the web3 organization is driven by its users' perceptions of the team.  A critical incident can potentially reduce the value of the organization in the eyes of those users.  That may have negative impact on its current revenue as well as future extensibility.

Considering the above observations, our aim was to choose tools and technologies that enable us to ensure high QoS for all of our products and services.

## Speed
Like any startup, the goal is to build products and services that provides functionalities that address the real-world need and can be built within a relatively short time.  For example, there are multiple languages that could be used to build webservices, e.g., Java, C#, Go, Javascript.  These languages vary in the amount of boilerplate coding, complexity of the  configurations, and availability of libraries and tools.  In this case, our choice will be the language that is easier to setup and provides libraries and tools that allow us to build the apps efficiently.

## Extensibility
Startups tend to try out a lot of ideas and refine / extend such ideas in a fast-paced manner.  This implies, the technology of choice should allow us to easily extend the products to add/refine its features.

## Ease of use (popularity)
The effectiveness and efficiency of a technical organization largely depends upon its ability to hire the right set of developers.  In the post-covid era when the tech budget is shrinking everywhere, hiring experienced and skilled engineers can be expensive and a time-consuming affair.  The woe of finding the developers could be somewhat lessened if we target the technology that is popular and has a large developer base.  

# Language
For building the web apps and services we primarily use Typescript for the following reasons:
- It provides type inference which leads to catching bugs and errors early in the development process
- Excellent support for static analysis and unit testing which lead to higher code quality and maintainability
- The code runs everywhere Javascript runs
- Has amazing support from a large number of frameworks and libraries especially for blockchain technologies
- Javascript developers (a large pool) can learn how to write Typescript code within a short period of time

Besides Typescript, we use Solidity for writing smart contracts.

# Repository

# Infrastructure

# Storage
We have chosen to use Postgresql to store the data for the apps and services.

# CI/CD


[back](./)
