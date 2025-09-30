---
title: Welcome to InstructLab!
description: The overview of 🐶 InstructLab.
logo: images/ilab_dog.png
---
# Welcome to the 🐶 InstructLab Project

![Banner](images/instructlab-banner.png)

InstructLab is a model-agnostic open source AI project that facilitates contributions to Large Language Models (LLMs).

!!! note
    ==**Community Announcement (Sept 2, 2025)**==

    Over the past year, we’ve been honored by your creativity, insights, and shared passion for advancing generative AI through **InstructLab**. Whether you added a new “knowledge” via pull request, offered feedback, joined a community call, or helped translate documentation, you’ve shaped our project in meaningful ways. Thank you.

    To better align with evolving technical needs, we’re announcing an evolution for the InstructLab community. We will be refactoring the project by separating the components out to improve its maintainability and usability, primarily as a framework SDK for model tuning.

    **What's Changing**

    To enhance the long-term viability and efficiency of the InstructLab project, a strategic decision has been made to relocate its foundational building blocks into separate, dedicated project repositories. This carefully considered shift is anticipated to yield substantial benefits, primarily in the areas of maintainability and independent component maturation. This independent development will foster greater agility, allowing for more focused improvements and faster iteration cycles for individual parts of the project.

    **Looking Ahead**

    We’re excited about this next chapter and believe it will lead to more robust, flexible, and powerful tools for the generative AI community. We encourage you to follow the individual component projects in their new homes and continue contributing to their growth.

    SDG: [https://github.com/Red-Hat-AI-Innovation-Team/sdg_hub](https://github.com/Red-Hat-AI-Innovation-Team/sdg_hub)

    Training: [https://github.com/Red-Hat-AI-Innovation-Team/training_hub](https://github.com/Red-Hat-AI-Innovation-Team/training_hub)

---

## Why InstructLab

There are many projects rapidly embracing and extending permissively licensed AI models, but they are faced with three main challenges:

* Contribution to LLMs is not possible directly. They show up as forks, which forces consumers to choose a “best-fit” model that isn’t easily extensible. Also, the forks are expensive for model creators to maintain.
* The ability to contribute ideas is limited by a lack of AI/ML expertise. One has to learn how to fork, train, and refine models to see their idea move forward. This is a high barrier to entry.
* There is no direct community governance or best practice around review, curation, and distribution of forked models.

**InstructLab is here to solve these problems.**

The project enables community contributors to add additional "skills" or "knowledge" to a particular model.

InstructLab's model-agnostic technology gives model upstreams with sufficient infrastructure resources the ability to create regular builds of their open source licensed models not by rebuilding and retraining the entire model but by composing new skills into it.

Take a look at "lab-enhanced" models on the [InstructLab Hugging Face page](https://huggingface.co/instructlab).

## 📋 Requirements

- **🍎 Apple M1/M2/M3 Mac or 🐧 Linux system** (tested on Fedora).
  We anticipate support for more operating systems in the future.
- C++ compiler
- Python 3.10 or Python 3.11
- Approximately 60GB disk space (entire process)

!!! note
    Python 3.12 is currently not supported, because some dependencies don't work on Python 3.12, yet. As of now, we only support Python 3.10 or Python 3.11 (preferred). Any other Python version would install an older version of InstructLab (e.g., 0.17).

!!! tip
    When installing the `ilab` CLI on macOS, you may have to run the `xcode-select --install` command, installing the required packages previously listed.

