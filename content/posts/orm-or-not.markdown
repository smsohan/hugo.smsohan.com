---
layout: post
title: "ORM or Not?"
date: 2012-11-06
comments: true
categories: ['Architecture']
---

Yes to ORM, No to custom queries. Here's a bullet list:

1. You'd probably end up writing your own ORM anyway.
2. Doing so, you'd spend <strong>a lot of money</strong> writing library level code instead of your business logic.
3. The time tested ones are likely to be <strong>better than yours</strong>.
4. Beware, you'd have to figure out some <strong>complex issues</strong>: connection pooling, concurrency/locking, caching, transactions, updates, versioning, documentation etc.

If you find yourself ORM is falling short of what you need, you're either presenting information overload or using a transactional database as a reporting store.

In this article, I mean ORM to be an object database mapping, so it applies to both SQL/NoSQL databases.

Disagree? I'd like to find your opinion in the comments.

