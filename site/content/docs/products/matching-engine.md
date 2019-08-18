---
title: Matching Engine
date: 2019-08-08T08:58:24.873Z
---
# Matching Engine

We LOVE challenges!! The more interesting the better.

A while back a new lead of ours wanted to build a matching engine for their new exchange and they were looking for a partner to implement it. They found us through a friend and we entertained the idea, without having built one before simply because, like I mentioned above, WE LOVE CHALLENGES.

We set to do our research and used Go as the programming language of choice, because we've used it in the past with good results and we wanted to dive deeper into it.

The challenge was not just to build a matching engine, but to build one that can reach over 1,000,000 trades per second.

In the end we've lost the lead, but the challenge still remained and being very curious by our very nature we've started doing our own research into what it means to build a matching engine, what orders and trades are, what existing solutions are already on the market or open source, what is a market order, etc.

We've found that there is not much information out there available for free, even though these kind of systems have been powering the financial market for a long time. 

To the most part that is because these systems are built for large banks and financial institutions in a closed source, proprietary system. 

With the rise of cryptocurrencies there has been a lot of demand to build exchanges and related technology in order to serve this new market, however there has also been a lot of missing technical knowhow in how exactly these systems are built from the ground up. 

That is why there have been many hacks over the years in this space while a new group of developers were learning to build these systems without any prior technical knowhow in the space. This continues on today as well, as we see new exchanges built in PHP, Python or Ruby simply because these are the common languages used on WEB developers who were more or less pushed into this space.

Our challenge was not an easy one. We set out to push the limits, but that is only part of the journey. We also set out to open a communication into how these systems are built and how you can do it better and safer for everyone involved.

That's why we started writing on our blog about [how to build a matching engine](https://around25.com/blog/building-a-trading-engine-for-a-crypto-exchange/), as we were building it.

Fast forward a few months and we've actually started using it for a client as the backend of a real crypto exchange called ParamountDax, which you can currently visit at: <a href="https://staging.paramountdax.com" target="_blank" rel="noopener noreferrer">staging.paramountdax.com</a>.

# Features

- Over 1.000.000 trades per second
- Support for limit, market and stop orders
- Support for order cancellation
- Highly scalable infrastructure with Apache Kafka and Protobuf
- Easy deployments with Docker
- Configurable automatic backups

# License

If you want your exchange to support a large number of trades than we can help. Our matching engine is available for licensing with complete technical support. Contact us here for licensing terms and pricing: https://around25.com/contact


