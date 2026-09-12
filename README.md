# miniGPT

This repository contains the code for building a small language model from scratch, with as little reliance on libraries as possible.

The goal is to understand how LLMs actually work by implementing their main components myself, rather than treating them as black boxes. The project will initially be written in Python, with the eventual goal of rewriting the core implementation in raw C++.

## Learning

I will be following **Maarten Grootendorst and Jay Alammar's *Hands-On Large Language Models*** to learn the fundamentals of NLP, Transformers, and LLMs.

As I work through the book, I will implement the concepts myself and gradually build up `miniGPT`.

This will include:

* Tokenisation
* Embeddings
* Positional encoding
* Attention
* Transformers
* Training a language model
* Text generation
* Other fundamental components of modern LLMs

The main objective is not to build a powerful model, but to understand the ideas and code behind one.

## From Learning to Research

`miniGPT` is also intended as an intermediate project for a larger NLP project.

After developing a solid understanding of LLMs, I plan to work on reproducing the **BoxTM papers**. This will involve studying the papers, implementing their methods, and attempting to reproduce their results.

Eventually, I would like to use this foundation to experiment with the models and, if possible, develop a contribution of my own.

The overall path is:

```text
Learn LLM fundamentals
        ↓
Build miniGPT from scratch
        ↓
Reproduce BoxTM
        ↓
Experiment and extend
        ↓
Potential research contribution
```

For now, the focus is simple:

**Understand the fundamentals. Build them myself. Then use that knowledge for research.**
