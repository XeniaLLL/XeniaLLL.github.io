---
title:          CPInj Uncovering Prompt Injection Risks in Textual Collaborative Prompt Optimization  
date:           2026-07-12 00:01:00 +0800
selected:       true
pub:            "ICML AI4GOOD Workshop, COLM 2026"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       '<span class="badge badge-pill badge-custom badge-warning">Poster</span>'
pub_date:       "2026"

abstract: >-
  Textual Collaborative Prompt Optimization (TCPO) extends Textgrad (Yuksekgonul et al., 2025) to a decentralized setting by allowing multiple clients to jointly improve prompts for large language models (LLMs) while keeping their data locally. Its reliance on free-form textual updating and aggregation introduces a new and largely unexplored attack surface, i.e., malicious instructions can be injected into local prompts and propagated through server-side prompt aggregation. Unlike conventional prompt injection attacks that define success as misleading LLM generating response shifted from the original task, attacking TCPO is more challenging as malicious instructions must simultaneously remain effective after aggregation, persist under subsequent benign prompt optimization, and stay stealthy enough to evade server-side defenses. To expose this risk, we propose CPInj, a collaborative prompt injection attack that contaminates the aggregated global prompt with malicious instructions, degrades downstream task performance, resists purification by prompt optimization on benign clients, and evades advanced detection-based defenses on the server. We find that current defense methods are ineffective against CPInj. To mitigate this attack, we further propose a defense-oriented aggregation method, i.e., APAgg, which purifies malicious instructions and recovers the utility of TCPO. We conduct extensive experiments across three LLM families and five reasoning tasks, which verify that our proposed attack reveals a critical vulnerability in TCPO. Although we take a first step toward mitigation, the attack remains highly effective and far from fully resolved, calling for more robust defense for TCPO.
 
cover:          assets/images/covers/malicious_client_loop.png
authors:
  - Xinting Liao
  - Behnoosh Zamanlooy
  - Masoumeh Shafieinejad
  - David B. Emerson
  - Ruinan Jin
  - Deval Pandya
  - Xiaoxiao Li†

links:
  Code:  
  Paper: https://openreview.net/forum?id=fQqNvvyxKA
#  Poster: assets/images/poster/icml2024-ws.jpeg
  Cite: assets/bibtex/liao2026cpinj.bib.bib
---
