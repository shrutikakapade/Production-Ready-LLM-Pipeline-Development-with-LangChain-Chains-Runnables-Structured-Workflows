<h1 align="center">Building LLM Pipelines using LangChain Chains & Runnables</h1>

<p align="center">
Designing Modular, Scalable, and Production-Ready AI Pipelines using Modern LangChain Architecture
</p>

<hr>

<h2>Why AI Pipelines Matter</h2>

<p>
Modern AI systems are no longer single prompt calls.
They are structured workflows consisting of multiple transformation, validation, reasoning, and formatting steps.
</p>

<p>
An <strong>AI Pipeline</strong> allows us to:
</p>

<ul>
<li>Break complex AI tasks into modular components</li>
<li>Control execution flow (sequential, parallel, conditional)</li>
<li>Ensure structured and validated outputs</li>
<li>Reuse components across systems</li>
<li>Scale AI applications for production</li>
</ul>

<p>
Without pipelines, LLM applications become:
</p>

<ul>
<li>Rigid</li>
<li>Difficult to debug</li>
<li>Hard to scale</li>
<li>Non-reusable</li>
</ul>

<p>
This repository demonstrates how to move from basic LLM calls to 
<strong>production-oriented AI system design</strong>.
</p>

<hr>

<h2>What is an AI Pipeline?</h2>

<p>
An AI pipeline is a structured execution flow where:
</p>

<pre>
Input → Transformation → Reasoning → Validation → Structured Output
</pre>

<p>
Each stage performs a defined responsibility, making the system modular, testable, and maintainable.
</p>

<p>
LangChain's modern <strong>Runnable architecture</strong> enables this composable pipeline design.
</p>

<hr>

<h2>Repository Overview</h2>

<p>
This repository walks through the evolution of AI pipeline architecture using LangChain:
</p>

<ul>
<li>Traditional Chains (Linear Execution)</li>
<li>RunnableSequence & RunnablePassthrough (Composable Core)</li>
<li>Advanced Runnable Types (Parallelism, Branching, Streaming)</li>
</ul>

<p>
The goal is to understand not just <em>how to call an LLM</em>, but how to 
<strong>engineer scalable AI systems</strong>.
</p>

<hr>

<h2>Industrial Use Case Example</h2>

<p>
Imagine building an <strong>Automated Resume Screening System</strong>.
</p>

<p>
Required workflow:
</p>

<ul>
<li>Step 1 → Extract resume text</li>
<li>Step 2 → Structure candidate details</li>
<li>Step 3 → Generate candidate summary</li>
<li>Step 4 → Match against job description</li>
<li>Step 5 → Return validated JSON output</li>
</ul>

<p>
This cannot be handled by a single LLM call.
It requires:
</p>

<ul>
<li>Modular logic</li>
<li>Controlled execution flow</li>
<li>Parallel processing</li>
<li>Conditional routing</li>
<li>Structured output validation</li>
</ul>

<p>
This repository demonstrates how to architect such systems properly.
</p>

<hr>

<h2>🗂 Repository Structure</h2>

<ul>
<li><strong>1️⃣ chains-vs-runnables-langchain.ipynb</strong> — Foundation Layer</li>
<li><strong>2️⃣ Pipeline_using_Runnables.ipynb</strong> — Core Production Pipeline</li>
<li><strong>3️⃣ Advanced_Runnable_Types_in_LangChain.ipynb</strong> — Dynamic & Scalable Workflows</li>
</ul>

<p>
Each notebook builds progressively toward production-grade AI pipeline design.
</p>

<hr>

<h2>🔄 Learning Evolution</h2>

<pre>
Basic LLM Calls
      ↓
Traditional Chains
      ↓
RunnableSequence Pipelines
      ↓
Parallel & Conditional Workflows
      ↓
Streaming & Dynamic AI Systems
      ↓
Production-Ready Architecture
</pre>

<hr>

<h2>1️⃣ Chains vs Runnables (Foundation Layer)</h2>

<h3>Purpose</h3>

<p>
Understand the architectural shift from rigid linear chains to flexible runnable systems.
</p>

<h3>Key Concepts</h3>

<ul>
<li>Sequential execution model</li>
<li>Limitations of traditional chains</li>
<li>Runnable abstraction</li>
<li>Composable architecture</li>
</ul>

<h3>Architectural Insight</h3>

<ul>
<li>Chains → Linear & fixed</li>
<li>Runnables → Modular & composable</li>
<li>Modern AI requires flexible orchestration</li>
</ul>

<hr>

<h2>2️⃣ Pipeline using Runnables (Core Production Layer)</h2>

<h3>Purpose</h3>

<p>
Build a structured and modular AI pipeline using composable runnable components.
</p>

<h3>Runnable Types Implemented</h3>

<ul>
<li>RunnableSequence → Step-by-step pipeline execution</li>
<li>RunnablePassthrough → Preserve original inputs</li>
</ul>

<h3>Pipeline Architecture</h3>

<pre>
Input
   ↓
Prompt Template
   ↓
LLM Model
   ↓
Parser / Formatter
   ↓
Validated Structured Output
</pre>

<h3>Production Relevance</h3>

<ul>
<li>Clear input-output contracts</li>
<li>Reusable components</li>
<li>Modular debugging</li>
<li>Structured and validated outputs</li>
</ul>

<hr>

<h2>3️⃣ Advanced Runnable Types in LangChain (Dynamic Workflow Layer)</h2>

<h3>Purpose</h3>

<p>
Design intelligent and scalable AI workflows using advanced execution patterns.
</p>

<h3>Runnable Types Covered</h3>

<ul>
<li><strong>RunnableLambda</strong> → Inject custom logic into pipelines</li>
<li><strong>RunnableGenerator</strong> → Enable streaming responses</li>
<li><strong>RunnableParallel</strong> → Execute independent tasks concurrently</li>
<li><strong>RunnableBranch</strong> → Route execution based on conditions</li>
</ul>

<h3>Advanced Execution Patterns</h3>

<pre>
Input
   ↓
Conditional Routing (Branch)
   ↓
Parallel Processing
   ↓
Custom Logic Injection
   ↓
Streaming / Incremental Output
</pre>

<h3>Enterprise-Level Capabilities</h3>

<ul>
<li>Dynamic decision-making pipelines</li>
<li>Concurrency handling</li>
<li>Low-latency responses via streaming</li>
<li>Scalable workflow orchestration</li>
</ul>

<hr>

<h2>🚀 Complete End-to-End AI Pipeline Architecture</h2>

<pre>
User Input
    ↓
Data Processing
    ↓
LLM Reasoning
    ↓
Conditional / Parallel Logic
    ↓
Structured Validation
    ↓
Production-Ready Output
</pre>

<hr>

<h2>🧠 Skills Demonstrated</h2>

<ul>
<li>LLM System Design</li>
<li>LangChain Runnable Architecture</li>
<li>Composable Workflow Engineering</li>
<li>Conditional & Parallel Execution</li>
<li>Structured Output Validation</li>
<li>Prompt Engineering</li>
<li>Scalable AI Application Design</li>
<li>Production-Oriented Architecture Thinking</li>
</ul>

<hr>

<h2>🛠 Technologies Used</h2>

<ul>
<li>Python</li>
<li>LangChain (Runnable Architecture)</li>
<li>HuggingFace Endpoint</li>
<li>Pydantic Output Parser</li>
<li>LLM Models</li>
</ul>

<hr>

<h2>🌟 Why This Repository Stands Out</h2>

<p>
Most AI projects stop at calling an LLM.
This repository goes further — it demonstrates:
</p>

<ul>
<li>Architectural thinking</li>
<li>Workflow engineering</li>
<li>System modularity</li>
<li>Scalability considerations</li>
<li>Production-readiness mindset</li>
</ul>

<p>
It reflects real-world AI system design patterns used in enterprise-grade LLM applications.
</p>

<hr>

<h2>Ideal For</h2>

<ul>
<li>AI Engineer roles</li>
<li>Generative AI Engineer roles</li>
<li>LLM Application Developer roles</li>
<li>Engineers transitioning into GenAI</li>
<li>Students building advanced AI portfolios</li>
</ul>

<hr>

<p align="center">
<strong>Engineered for Production-Oriented AI Learning & Real-World System Design</strong>
</p>
