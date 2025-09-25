These speaking notes are designed for an 8-minute presentation, following the structure provided in the updated template, "GA 11 Presentation Slide Template-2025V2.1.pdf".

***

### Speaking Notes: AI Video Summariser Project

**(Time Check: 0:00 – 0:30)**

**Slide 1: Title Slide**
"Good morning, Dr. Brandt, Dr. Almaktoof, and fellow students. My name is [Your Name], and I will be presenting the progress and management of my Industrial Computing Design Project: the **AI Video Summariser**."

**Slide 2: Outline**
"Our presentation today will follow the standard DES371S structure, covering the Introduction, Objectives, System Design, Methodology, key aspects of Management—focused on Graduate Attribute 11—and concluding with our next critical steps."

***

**(Time Check: 0:30 – 1:45)**

**Slide 3: 1. Introduction – Motivation and Context**
"The core motivation for this project addresses the pervasive challenge of **information overload in long-form video content**.".

"We are redefining how knowledge is processed from videos, utilizing the psychological principles often seen in short-form content, but applying them for productive knowledge acquisition to reduce time and effort.". This system is designed to be **time effective, scalable, consistent, and accessible**.

"The project operates at the intersection of AI, Machine Learning, and Computer Vision. The goal is simple: to create a pipeline that processes lengthy video inputs, semantically understands the content, and renders a new, shorter video that preserves the essential information—whether that source is a lecture, tutorial, or security footage.".

**Slide 4: 2. Project Objectives**
"Our Core Objective is to **create a pipeline to semantically render optimised videos**.".

"Crucially, our sub-objectives are deeply tied to execution. This includes setting up the dedicated server hardware, which is critical for Plan A: the **HP Proliant ML150 Gen9** equipped with an Intel Xeon CPU, 40GB of DDR4 RAM, and, most importantly, **two GTX 1080 Aorus Xtreme GPUs** for acceleration.".

"Other objectives include developing a robust pre-processing pipeline to avoid the 'Garbage In, Garbage Out' (GIGO) problem, selecting suitable AI models like `ltxvideo`, `hunyuan`, `gemini`, or `deepseek` for generation, and finally, developing a user-friendly interface for public accessibility.".

***

**(Time Check: 1:45 – 3:15)**

**Slide 5 & 6: 3. System Design – Three-Layer Architecture**
"The system relies on a **three-layer architecture** which decouples the major functional components.".

"**Layer 1 is Input and Pre-processing**. This layer handles video ingestion, splits the long video into manageable chunks, and extracts critical features through audio transcription and visual analysis.".

"**Layer 2 is the AI Core Processing Layer**. This is where the intelligence resides. It utilizes a Multi-modal Large Language Model (M-LLM) pipeline, often involving components like Vector Databases and Context-Aware Retrieval Augmented Generation (CA-RAG).". "This layer generates the metadata, understands the context of the entire video, and creates the structured summary required for the final output.".

"**Layer 3 is the Output and API Layer**. This renders the final summary video and exposes **REST APIs** for seamless integration with other external applications, alongside a user interface.".

***

**(Time Check: 3:15 – 4:15)**

**Slide 7: 4. Methodology and Current Progress**
"We follow a five-phase methodology. I am pleased to report that the foundational research, system design, and tool selection are complete. Phases 1 and 2—problem scope and requirements definition—have been fully completed.".

"Our **Current Status is Phase 3: Pipeline development and Model training iteration**, specifically the infrastructure setup phase.".

"We completed all possible preliminary tasks locally in parallel while awaiting server access, including prototyping individual pre-processing pipeline modules, conducting unit tests on scripts, and designing the detailed workflow for `ComfyUI-Distributed`—our solution for multi-GPU utilization.".

***

**(Time Check: 4:15 – 6:45)**

**Slide 8-14: 6. Management (GA 11)**

"Our project management strategy, addressing GA 11, focuses heavily on budget control, risk mitigation, and quality assurance."

**6.2 Budget:**
"Plan A operates on a **zero-cost budget**. This is achieved by leveraging Free and Open-Source Software (FOSS), such as `ltxvideo` or `hunyuan`, and utilizing the university-provided server hardware.". "Plan B exists solely as a fallback, outlining a small budget if alternative hardware is absolutely necessary.".

**6.3 Risk Analysis:**
"The primary, critical risk identified early on was the **dependency on timely access to the university server**.". "This risk was realized, impacting our original timeline.". "However, our mitigation strategy—focusing on parallel local workstreams—allowed us to complete preliminary tasks, and thankfully, server access was granted, allowing us to accelerate into the integration phase.".

"Despite resolving that dependency, we currently face a new, immediate challenge: **the server is offline due to an Nvidia update**, which is currently preventing the comprehensive performance tests we need to run.".

**6.5 Quality Assurance:**
"Quality assurance steps were implemented well in advance. Dedicated test plans were developed, and all unit tests for pre-processing scripts were conducted locally to verify functionality before server deployment.".

"Our **Key Performance Indicators (KPIs)** are clearly defined to measure long-term value, including **capable GPU acceleration for rendering, overall processing speed and optimization, coherence control, and information retention value**.".

***

**(Time Check: 6:45 – 8:00)**

**Slide 15: 7. Conclusion and Next Steps**
"In summary, the foundational research, system design, and local component validation are complete. The system architecture is finalized, and we are prepared for the intensive integration and evaluation phase.".

"We have resolved the critical dependency on initial server access, which allows us to fully proceed into Phase 3.".

"The immediate **Current Challenge** is resolving the server downtime caused by the Nvidia update, which has currently put testing on hold.".

"Our **Next Steps** are focused and critical:"
"First, we must conduct **comprehensive performance tests** on the server to verify its capability to efficiently handle the workload from the video pre-processing, summarization, and `ltxvideo` rendering layers.". "These test results are crucial for determining the **final feasibility of Plan A**.".
"Following successful verification, we will deploy automation tools and begin end-to-end tests with various long-form video inputs, iteratively refining the AI models and the pipeline, ultimately leading to the development of the final user interface and API.".

**Slide 16: Thank you and Questions**
"Thank you. I am now open to any questions you may have.". verification, we will deploy automation tools and begin end-to-end tests with various long-form video inputs, iteratively refining the AI models and the pipeline, ultimately leading to the development of the final user interface and API.".

**Slide 16: Thank you and Questions**
"Thank you. I am now open to any questions you may have.".
