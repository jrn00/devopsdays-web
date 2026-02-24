+++ Talk_date = "" Talk_start_time = "" Talk_end_time = "" Title = "Hands-On LLMOps: Build an Observable AI System in 90 Minutes" Type = "talk" Speakers = ["jeanne-mcclure"] +++

Your team shipped an LLM feature. It works—mostly. But last week it gave a customer bizarre advice, and nobody knows why. The logs show an HTTP 200. Helpful.
 LLMs fail differently than traditional software. There's no stack trace when the model hallucinates. Your APM tools see a successful API call while the output is nonsense.
 Can you debug it when it breaks? Do you know what it costs per request? Can you trace why it gave a wrong answer?
 In this hands-on workshop, you'll build a complete LLM-powered system with production-grade observability—from scratch, on your laptop, using entirely open-source tools with zero API costs.
 What you'll build: A document analysis system using RAG (Retrieval-Augmented Generation) that can answer questions about your own documents, fully instrumented with tracing and monitoring.
 
 The stack (all free, all local):
 
 OLLAMA: Run LLMs locally (no OpenAI API needed)
 Langfuse: Open-source LLM observability platform
 ChromaDB: Vector database for document retrieval
 OpenTelemetry: Industry-standard tracing integration
 
 What you'll learn:
 
 Set up a local LLM environment in minutes
 Build a RAG pipeline with proper error handling
 Instrument every LLM call with traces
 Track token usage, latency, and costs
 Debug when things go wrong (and they will!)
 Patterns for production deployment
 
 Prework required: Participants must complete setup before arriving. Instructions provided in advance via email. Plan 30-45 minutes for Docker, OLLAMA, and model installation.
 
 *Prerequisites:
 
 Laptop with Docker installed
 Basic Python knowledge (we'll explain everything else)
 8GB RAM minimum (16GB recommended)
 
 What you'll leave with:
 
 A working local LLM stack you can extend
 Observability patterns applicable to any LLM project
 Code and templates to use at work Monday
 
 This workshop is for DevOps practitioners, SREs, and developers who want to understand LLMs beyond "it's magic." Whether you're evaluating AI tools or have LLMs in production without monitoring, you'll gain practical skills to make AI systems observable.
 
 Bring your laptop, your curiosity, and prepare to break things (safely).
