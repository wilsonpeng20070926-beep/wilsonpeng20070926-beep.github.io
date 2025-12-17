# Xianghang Peng

## Bio

I am an highschool researcher focused on scientific AI for materials and nanomedicine.  
Broadly, I am interested in trustworthy AI systems that accelerate scientific discovery in high-stakes domains.  
Especially, I work on structured reasoning for scientific LLMs—graph-based inference, tool-augmented verification, and multi-agent critique for nanobiomaterials design.

I currently work with AIXC, where I explore reasoning architectures for safety-critical scientific workflows and research directions aligned with conference submissions.  
I have attended [Conference 1] and plan to attend/submit to [Conference 2], with an emphasis on [topics you will explore as an intern / for submissions].

---

## Papers

### Graph of Thoughts Nanobiomaterials Assistants: Towards Logical, Tool-Augmented, and Multi-Agent Reasoning in Scientific LLMs  
**Xianghang Peng**, David Scott Lewis  
**Affiliation:** AIXC  
**Links:** [PDF](assets/papers/GoT-Nano.pdf)

**TL;DR:** We argue that nanobiomaterials assistants should move beyond linear Chain-of-Thought into graph-structured reasoning augmented by symbolic solvers and multi-agent debate, enabling backtracking, aggregation of design paths, and better logical consistency.

**Keywords:** nanobiomaterials; large language models; Graph of Thoughts; tool augmentation; symbolic solvers; formal verification; multi-agent debate; safety-critical AI

**Abstract:**  
The integration of Large Language Models (LLMs) into materials science has accelerated literature review, hypothesis generation and testing, property prediction, and code generation. However, the safety-critical domain of nanobiomaterials—defined by complex multi-attribute constraints involving surface chemistry, cytotoxicity, and immune response—exposes the fundamental limitations of current autoregressive models. Standard approaches, such as Chain-of-Thought (CoT) prompting, frequently suffer from logical inconsistencies, hallucinated constraints, and a lack of formal verifiability. This position paper argues that the next generation of AI assistants for nanobiomaterials must transition from linear, probabilistic generation to structured, rigorous reasoning architectures. We propose the Graph of Thought Nanobiomaterials Assistant (GoT-Nano), a framework that integrates Graph of Thoughts (GoT) reasoning, symbolic solver augmentation (SatLM), and multi-agent debate systems. By restructuring inference as an arbitrary graph, we enable non-linear exploration of design spaces, backtracking from toxic candidates, and the aggregation of multi-modal insights. Furthermore, we advocate for the integration of formal logical layers to enforce consistency (e.g., negation and transitivity) and the use of external symbolic tools for verifiable calculation. We contend that this shift from pattern matching to deliberate, verifiable reasoning is essential for the trustworthy deployment of AI in the high-stakes design of therapeutic nanostructures.
