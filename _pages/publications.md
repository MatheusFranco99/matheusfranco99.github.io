---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

## Alea-BFT: Practical Asynchronous Byzantine Fault Tolerance

In Proc. of USENIX Symposium on Network Systems Design and Implementation (NSDI’24), Santa Clara, CA, 2024 \
Antunes D., Oliveira A., Breda A., **Franco M.**, Moniz H., Rodrigues R. \
[Paper](https://www.usenix.org/system/files/nsdi24-antunes.pdf)

> Traditional Byzantine Fault Tolerance (BFT) state machine replication protocols assume a partial synchrony model, lead- ing to a design where a leader replica drives the protocol and is replaced after a timeout. Recently, we witnessed a surge of asynchronous BFT protocols, which use randomization to re- move the need for bounds on message delivery times, making them more resilient to adverse network conditions. However, existing research proposals still fall short of gaining practi- cal adoption, plausibly because they are not able to combine good performance with a simple design that can be readily understood and adopted. In this paper, we present Alea-BFT, a simple and highly efficient asynchronous BFT protocol, which is gaining practical adoption, namely in Ethereum dis- tributed validators. Alea-BFT brings the key design insight from classical protocols of concentrating part of the work on a single designated replica and incorporates this principle in a simple two-stage pipelined design, with an efficient broad- cast led by the designated replica, followed by an inexpensive binary agreement. The evaluation of our research prototype implementation and two real-world integrations in cryptocur- rency ecosystems shows excellent performance, improving on the fastest protocol (Dumbo-NG) in terms of latency and displaying good performance under faults.

