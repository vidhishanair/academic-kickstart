+++
# Project title.
title = "Differentiable Reasoning over a Virtual Knowledge Base"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "We consider the task of answering complex multi-hop questions using a corpus as a virtual knowledge base (KB). In particular, we describe a neural module, DrKIT, that traverses textual data like a virtual KB, softly following paths of relations between mentions of entities in the corpus. At each step the operation uses a combination of sparse-matrix TFIDF indices and maximum inner product search (MIPS) on a special index of contextual representations. This module is differentiable, so the full system can be trained completely end-to-end using gradient based methods, starting from natural language inputs. We also describe a pretraining scheme for the index mention encoder by generating hard negative examples using existing knowledge bases. We show that DrKIT improves accuracy by 9 points on 3-hop questions in the MetaQA dataset, cutting the gap between text-based and KB-based state-of-the-art by 70%. DrKIT is also very efficient, processing upto 10x more queries per second than existing state-of-the-art QA systems."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Question Answering", "Multi-Hop QA", "Deep Learning", "Knowledge Bases", "Information Extraction", "Data Structures for QA"]

# Optional external URL for project (replaces project detail page).
# external_link = "https://openreview.net/forum?id=SJxstlHFPH&noteId;=Ilh9vDgaeg"

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
#  caption = "Photo by Toa Heftiba on Unsplash"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
#  focal_point = "Smart"
+++
