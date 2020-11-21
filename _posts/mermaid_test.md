--- 
layout: post 
title: “Mermaid Test”
excerpt: “This is a test of Mermaid JS graph capability.”
comments: false
share: true
use_mermaid: true
categories: [blog]
tags: [testing,graph]
---

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;

```mermaid
graph LR;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```