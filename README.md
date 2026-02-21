# Hi, I'm Dan Park 👋

**AI Engineer & Founder at [MagicPoint.ai](https://magicpoint.ai)**

I build tools that stop AI from breaking your code. 

Right now, the standard approach to AI code generation is to dump massive codebases into a massive context window and hope the LLM understands it. But as context grows, the AI gets confused, loses focus, and introduces silent bugs (what I call the "Foggy Boundary"). 

I am building an alternative: **neuro-symbolic architectures** that force AI to write reliable, verifiable code. 

### 🚀 What I'm Building

#### ◬ [Nexus: The AI IDE That Won't Break Your Code](https://github.com/dparksports/Project-Chevron)
Nexus is a next-generation development environment. Instead of feeding an LLM your entire project at once, Nexus forces the AI to build software **one isolated module at a time**. 
* **Auto-Decomposition:** It scans your messy, monolithic codebase and breaks it down into strict, logical modules.
* **Deterministic Verification:** Before any AI-generated code is accepted, a secondary "Weaver" system uses standard AST parsing to guarantee the AI hasn't hallucinated any hidden dependencies.

#### ⚙️ [Project Chevron (Spatial Constraint Protocol)](https://github.com/dparksports/Project-Chevron)
The open-source engine powering Nexus. To get LLMs to stop hallucinating, Chevron replaces conversational English prompts with a custom DSL based on mathematical symbols. 
* **The Result:** We compress what used to take 100,000+ tokens of context into about 700 tokens of pure architectural signal. 
* **The Impact:** In early testing, this approach reduced AI-introduced code regressions from **14.3% down to <0.1%**. 

📄 **Want the deep technical dive?** Read the paper: [*The Partition Function Explosion: An Energy-Based Analysis of Attention Decay*](https://github.com/dparksports/dparksports/raw/main/SCP%20II%20-%20Neuro-Symbolic%20Resolution.pdf).

### 🛠️ What I Work With
* **AI & LLMs:** Gemini, Claude, GPT, Local Models, Agentic Workflows, Prompt Engineering
* **Concepts:** Static Analysis (AST), Information Theory, Rejection Sampling, Neuro-Symbolic AI

### 📫 Let's Connect
If you're interested in making AI coding agents actually reliable, building deterministic AI workflows, or just want to talk about the limits of LLM attention, I'd love to connect.
* **Website:** [MagicPoint.ai](https://magicpoint.ai)
