<h1 align="center">Building LLM Pipelines using LangChain Chains & Runnables</h1>

<p align="center">
A complete practical guide to designing, structuring, and deploying LLM pipelines using modern LangChain architecture.
</p>

<hr>

<h2>Repository Overview</h2>

<p>
This repository demonstrates how to build structured and production-ready LLM pipelines using 
<strong>LangChain Chains</strong> and <strong>Runnables</strong>.  
It explains the architectural differences, workflow execution models, and how to design scalable AI pipelines.
</p>

<h3>💼 Industrial Example</h3>

<p>
Consider a company building an <strong>Automated Resume Screening System</strong>:
</p>

<ul>
<li>Step 1 → Extract text from resume</li>
<li>Step 2 → Structure candidate information</li>
<li>Step 3 → Generate summary</li>
<li>Step 4 → Match with job description</li>
<li>Step 5 → Return structured JSON output</li>
</ul>

<p>
Instead of writing disconnected scripts, this system requires a 
<strong>modular, reusable, and scalable pipeline</strong>.  
This repository demonstrates how to build exactly that using:
</p>

<ul>
<li>🔹 Traditional Chains</li>
<li>🔹 Modern Runnable-based Pipelines</li>
<li>🔹 Structured Workflow Design</li>
</ul>

<hr>

<h2>🗂 Repository Structure</h2>

<ul>
<li><strong>1️⃣ chains-vs-runnables-langchain.ipynb</strong></li>
<li><strong>2️⃣ Pipeline_using_Runnables.ipynb</strong></li>
</ul>

<p>
Each notebook builds on the previous one, forming a complete learning flow.
</p>

<hr>

<h2>🔄 Learning Flow & Architecture</h2>

<pre>
Foundations → Workflow Design → Production-Ready Runnable Pipeline
</pre>

<hr>

<h2>1️⃣ Chains vs Runnables (Foundation Layer)</h2>

<h3>Purpose</h3>
<p>
Understand the difference between traditional <strong>Chains</strong> and modern <strong>Runnables</strong>.
</p>

<h3>What This Notebook Covers</h3>

<ul>
<li>What is a Chain in LangChain?</li>
<li>How sequential chaining works</li>
<li>Limitations of traditional chains</li>
<li>Introduction to Runnables</li>
<li>Why Runnables are more flexible and composable</li>
<li>Modern pipeline construction approach</li>
</ul>

<h3>Key Learning</h3>

<ul>
<li>Chains are linear and rigid</li>
<li>Runnables are modular and composable</li>
<li>Runnables support parallel execution and branching</li>
<li>They are production-ready and scalable</li>
</ul>

<hr>


<h2>2️⃣ Pipeline using Runnables (Production Layer)</h2>

<h3>Purpose</h3>
<p>
Build a complete pipeline using modern Runnable architecture.
</p>

<h3>What This Notebook Covers</h3>

<ul>
<li>RunnableSequence</li>
<li>RunnableLambda</li>
<li>RunnablePassthrough</li>
<li>Composable pipeline building</li>
<li>Structured output handling</li>
<li>Clean modular execution</li>
</ul>

<h3>Runnable-Based Architecture</h3>

<pre>
Input
   ↓
Runnable (Prompt)
   ↓
Runnable (LLM)
   ↓
Runnable (Parser)
   ↓
Final Structured Output
</pre>

<h3>Key Learning</h3>

<ul>
<li>Composable AI systems</li>
<li>Production-grade design pattern</li>
<li>Flexible input-output handling</li>
<li>Modern LangChain best practices</li>
</ul>

<hr>

<h2>Complete Pipeline Flow (End-to-End)</h2>

<pre>
Chains vs Runnables
        ↓
Workflow Design
        ↓
Runnable Implementation
        ↓
Structured Production Output
</pre>

<p>
This progression mirrors how real-world AI systems are built:
</p>

<ul>
<li>Concept Understanding</li>
<li>System Design</li>
<li>Implementation</li>
<li>Deployment Readiness</li>
</ul>

<hr>

<h2>Skills Demonstrated</h2>

<ul>
<li>LLM Pipeline Design</li>
<li>LangChain Architecture</li>
<li>Runnable Composition</li>
<li>Structured Output Parsing</li>
<li>Workflow Engineering</li>
<li>Prompt Engineering</li>
<li>Production-Oriented AI Design</li>
</ul>

<hr>

<h2>Technologies Used</h2>

<ul>
<li>Python</li>
<li>LangChain</li>
<li>HuggingFace Endpoint</li>
<li>Pydantic Output Parser</li>
<li>LLM Models</li>
</ul>

<hr>

<h2>Why This Repository Matters</h2>

<p>
Modern AI systems are no longer single prompt calls.  
They are structured pipelines with validation, transformation, and modular execution.
</p>

<p>
This repository demonstrates how to transition from:
</p>

<ul>
<li>Basic LLM calls</li>
<li>To structured Chains</li>
<li>To production-grade Runnable Pipelines</li>
</ul>

<p>
It reflects real-world AI system design patterns used in enterprise-grade applications.
</p>

<hr>

<h2>Ideal For</h2>

<ul>
<li>AI Engineer roles</li>
<li>Generative AI Engineer roles</li>
<li>LLM Application Developer roles</li>
<li>Students building strong AI portfolios</li>
</ul>

<hr>

