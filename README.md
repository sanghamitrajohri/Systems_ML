# LLM Optimization Projects

Welcome to my repository, which showcases various projects focused on optimizing large language models (LLMs) for efficient inference and performance profiling.
Projects Overview
1. NanoGPT with KV Caching

This project extends Karpathy's NanoGPT implementation to incorporate key-value caching for optimized token generation during inference. The code has been tested and inferred on TPU T4 using Google Colab, and results show a significant improvement in per-token generation speed. An Nsight version for deeper performance analysis will be available soon.

Key Highlights:

    Implemented key-value caching to enhance inference speed.
    Benchmarked the performance on TPU T4.
    Stay tuned for the Nsight profiling results!

2. Profiling LLaMA Decode Layer

This project involves in-depth profiling of the LLaMA model's decode layer to understand performance bottlenecks. The aim is to identify optimization opportunities and improve the model's efficiency, particularly in terms of memory usage and computation speed.

Key Features:

    Detailed profiling using tools like PyTorch Profiler.
    Insights into optimizing transformer decode layers.

3. RAG from Scratch

Implemented Retrieval-Augmented Generation (RAG) from scratch, combining retrieval mechanisms with generative models for enhanced information recall and text generation. This project demonstrates how RAG can be built and optimized for real-world applications.

Core Components:

    Custom implementation of RAG pipeline.
    End-to-end integration of retrieval and generation models.
    Focus on efficient data handling and query processing.
