# Research and Verification: My Examples

[⬅ Back to Examples](README.md)

Elevate Your Thinking workshop, research and verification section.

**Core idea:** AI can suggest search terms, questions, and possible sources. Treat those as leads, not conclusions. Evidence and your own checking decide what to trust.

---

## Example 1: A general example (remote work)

**Question:** Does remote work hurt productivity?

1. **Start with your question.** Write down what you ask and what you already know. Some companies are calling workers back to the office.
2. **Ask AI for leads (AI step).** Get keywords, key studies, and competing views. AI notes the answer depends on the type of job.
3. **Open the originals.** AI mentions a Stanford study. Find the actual paper, not a summary of it.
4. **Check who, when, and why.** Who ran it and paid for it? Is it peer-reviewed, or a company blog post?
5. **Compare the claims.** Does a second, independent source report the same finding?
6. **Record and separate.** Cite the paper. Keep "the study found X" (evidence) apart from "so remote work is better" (interpretation).

---

## Example 2: My research on DiP (humanoid locomotion)

**Project:** Evaluating DiP, the diffusion planner inside the CLoSD framework, on complex and compositional human motion sequences. DiP is paired with the PHC+ physics controller.

**Research question:** Can DiP perform complex motions as well as long-horizon tasks?

1. **Start with your question.** The question above, plus what I already knew about CLoSD, DiP, and PHC+.
2. **Ask AI for leads (AI step).** Reading to start with: STMC, OmniControl, BRIC, CHD, and HumanUp.
3. **Open the originals.** Read the actual papers and run DiP myself instead of trusting a summary.
4. **Check who, when, and why.** What was it trained on, and how was it tested?
5. **Compare the claims.** Compare what the papers claim with what DiP does when I test it.
6. **Record and separate.**
   - **Evidence:** two failure modes. DiP procrastinates on spatially composite actions, and the character gets permanently stuck when it lies down.
   - **Interpretation:** the procrastination was traced to pose-mismatched training data.

**Why it works as an example:** the claims in the literature were leads. Testing the model myself is what turned them into evidence.

---

## Example 3: My cancer bioinformatics research

**Project:** Computational immunology, starting with a literature and data survey on TCR-pMHC binding prediction.

- **Leads:** AI is useful for keywords, subquestions, and competing methods in an unfamiliar field.
- **Originals:** open each paper and each dataset's documentation myself before relying on it.
- **Record:** sources and notes live in a project folder on Google Drive, so every claim can be traced back to where it came from.

---

## AI tools for research

Use these for **leads** (steps 1 and 2). Then open the sources yourself (steps 3 to 6).

- **[Claude](https://claude.ai):** talk through a research question, summarize or compare documents you upload, and plan a search strategy.
- **[ChatGPT](https://chatgpt.com):** a general assistant that also has web-based research modes.
- **[Perplexity](https://www.perplexity.ai):** answers with links to sources up front, so it is handy for quick lead-finding. Open the links; don't trust the summary.
- **[NotebookLM](https://notebooklm.google.com) (Google):** answers only from the documents you upload and points back to the passages it used. Good for "work from sources you provide."

**Also worth a look**

- **[Elicit](https://elicit.com) and [Consensus](https://consensus.app):** search academic papers and summarize what they found.
- **[Semantic Scholar](https://www.semanticscholar.org), [Google Scholar](https://scholar.google.com), and [Connected Papers](https://www.connectedpapers.com):** not chat tools, but they help you find, open, and map the real papers.

---

## Compute: UTRGV HPC (Cradle)

UTRGV's high-performance computing cluster is called **Cradle**. It is built for researchers across disciplines to speed up computations, analyze large datasets, and run simulations, with GPU-accelerated infrastructure funded by NSF and Department of Defense grants.

**Why it belongs in this talk:** sometimes verifying means running the model or experiment yourself. HPC gives you the compute to do that.

**How to get access:** use the "Request Access" link on the HPC site and follow the instructions.

**Links**

- [UTRGV HPC home](https://hpc.utrgv.edu/)
- [Getting Started guide](https://hpc.utrgv.edu/getting-started) (login, file transfer, job submission, software)
- [Cluster specifications](https://hpc.utrgv.edu/specifications)

---
