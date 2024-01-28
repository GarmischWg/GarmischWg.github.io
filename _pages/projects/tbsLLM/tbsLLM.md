---
layout: splash
title: "Large Language Model integration"
permalink: /tbsLLM/
header:
  overlay_color: "#000"
  overlay_filter: "0.7"
  overlay_image: /_pages/projects/tbsLLM/tbsLLM.jpg
excerpt: TBS internship
---
Apologies for not including the sub points in the revised version. Here is the revised text, including the sub points:

## Task
- Improved internal communications between engineering departments at TBS.
- Facilitated communication by answering questions based on the company code base.
- Collaborated with another intern who focused on fine-tuning the Language Model (LLM).
- Integrated different systems into Langchain at TBS.

## Exploration
**Explored different methods of hosting an LLM**
  - Local: Secure, private, but limited by hardware resources.
  - Hugging hosting: Limited model options, recurring fee, and privacy concerns.
  - OpenAI API: Privacy concerns with data being sent to external servers.

**Explored different methods of data preprocessing**
  - Balanced token limit and information density.
  - Converted data into vectors.
  - Considered the impact of chunking size.

**Explored different implementations of Retrieval-Augmented Generation (RAG)**
  - Reason Action (MRKL - ReAct): Emphasized the importance of high-quality retrieved information.
  - Agents & tools: Considered the computational resources and time required for spawning agents.
  - Multishot Agent: Achieved reasonable performance but consumed excessive tokens.
  - Short term memory: Enabled successful continuous conversation but faced VRAM limitations.

**Explored different types of LLM models**
  - Base models (7B, 13B, 32B): More parameters generally yielded better performance, but higher VRAM usage and longer inference times.
  - GPTQ: Quantized models consumed less VRAM but performed slightly worse than unquantized models.
  - ggml: Designed for CPU usage, but found to be too slow during the internship.
  - Instruct models: Better at following instructions, but had slightly poorer common sense due to training methods.

## Other Learning
**Learned and utilized the Pydantic library**
  - Enforced type safety in Python.
  - Ensured stable code, particularly important in a production environment.
**Explored virtualization and networking in greater depth**
  - Utilized proxmox to create a virtualized environment, allowing for the independent deployment of LLMs and separation of data, simulating a production environment.
  - Leveraged this setup to facilitate collaboration between interns, enabling both of us to work on the same machine simultaneously.

Please let me know if there are any further changes or additions you would like to make.

## Conclusion
- Developed a deep appreciation for the exploration of LLM during my internship at TBS.
- Found the experience of working with a library in the alpha stage, undergoing frequent changes, to be intellectually stimulating.
- Acknowledged the limitations imposed by the technology available at the time.
- Eager to embrace new opportunities and advancements in technology, ready to embark on the project once again with renewed enthusiasm.
- Excited to leverage new software and hardware to explore and implement cutting-edge strategies and methodologies, such as preprocessing data using LLM.
