---
title: "Multi-Grained Knowledge Retrieval for End-to-End Task-Oriented Dialog"
collection: publications
permalink: /publication/number2
excerpt: "Fanqi Wan, Weizhou Shen, **Ke Yang**, Xiaojun Quan, Wei Bi <br/><img src='/images/research2.png' style=\"width: 600px; height: auto;\" >"
date: July 2023
venue: 'Association for Computational Linguistics (ACL)'
paperurl: 'https://aclanthology.org/2023.acl-long.627/'
---
[paper link](https://aclanthology.org/2023.acl-long.627/)

<img src="/images/research2.png" style="zoom:80%;" />

Retrieving proper domain knowledge from an external database lies at the heart of end-to-end task-oriented dialog systems to generate informative responses. Most existing systems blend knowledge retrieval with response generation and optimize them with direct supervision from reference responses, leading to suboptimal retrieval performance when the knowledge base becomes large-scale. To address this, we propose to decouple knowledge retrieval from response generation and introduce a multi-grained knowledge retriever (MAKER) that includes an entity selector to search for relevant entities and an attribute selector to filter out irrelevant attributes. To train the retriever, we propose a novel distillation objective that derives supervision signals from the response generator. Experiments conducted on three standard benchmarks with both small and large-scale knowledge bases demonstrate that our retriever performs knowledge retrieval more effectively than existing methods. Our code has been made publicly available at https://github.com/18907305772/MAKER.