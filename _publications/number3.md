---
title: "An In-Depth Investigation of Data Collection in LLM App Ecosystems"
collection: publications
permalink: /publication/number2
excerpt: "Yuhao Wu, Evin Jaff, Ke Yang, Ning Zhang, and Umar Iqbal <br/><img src='/images/research3.png' style=\"width: 600px; height: auto;\" >"
date: Oct 2025
venue: 'Internet Measurement Conference (IMC)'
paperurl: 'https://arxiv.org/abs/2408.13247'
---
[paper link](https://arxiv.org/abs/2408.13247)

<img src="/images/research3.png" style="zoom:80%;" />

LLM app (tool) ecosystems are rapidly evolving to support sophisticated use cases that often require extensive user data collection. Given that LLM apps are developed by third parties and anecdotal evidence indicating inconsistent enforcement of policies by LLM platforms, sharing user data with these apps presents significant privacy risks. In this paper, we aim to bring transparency in data practices of LLM app ecosystems. We examine OpenAI's GPT app ecosystem as a case study. We propose an LLM-based framework to analyze the natural language specifications of GPT Actions (custom tools) and assess their data collection practices. Our analysis reveals that Actions collect excessive data across 24 categories and 145 data types, with third-party Actions collecting 6.03% more data on average. We find that several Actions violate OpenAI's policies by collecting sensitive information, such as passwords, which is explicitly prohibited by OpenAI. Lastly, we develop an LLM-based privacy policy analysis framework to automatically check the consistency of data collection by Actions with disclosures in their privacy policies. Our measurements indicate that the disclosures for most of the collected data types are omitted, with only 5.8% of Actions clearly disclosing their data collection practices.