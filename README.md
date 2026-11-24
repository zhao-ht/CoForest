# CoForest
The technique report of the mathematic harness used in human–AI collaboration that led to a proof of the codimension-one case of Ghys’s conjecture on holomorphic Anosov systems, including complex dimension three. 
Proposed in 1995, Ghys’s conjecture is a longstanding classification problem in holomorphic dynamics, asking whether every holomorphic Anosov diffeomorphism admits an algebraic model up to biholomorphic conjugacy.

## Paper

**CoForest: A Conversational Harness for Mathematical Research with Recursive Solving and Persistent Memory**

Haiteng Zhao, Yuzhe Gu, Songyang Gao, Jiesong Zhang, Zhouqi Hua, Lingkai Kong, Wenyong Huang, Shuya Zhao, Xiaotian Zhang, Chengzhi Xiong, Shuang Sun, Yan Wang, Dahua Lin, Xing Xie, Bowen Zhou, Disheng Xu, Wenwei Zhang

Technical report · November 11, 2026

[Paper website](https://zhao-ht.github.io/CoForest/) · [Full paper (PDF)](CoForest.pdf) · [BibTeX](citation.bib) · [Zenodo DOI](https://doi.org/10.5281/zenodo.24488914)

## Abstract

Mathematical research requires reasoning at scale, cumulative management of partial progress, and flexible collaboration with human experts. We present CoForest, a conversational harness that supports these requirements through a persistent research workspace. An outer dialogue loop directs research across turns, while a recursive solving module conducts the investigation within each turn. Every subproblem invokes the complete solving procedure, allowing reasoning effort to expand through local iteration and further decomposition. Global memory combines a lemma library, a problem-decomposition forest, and negative knowledge from expert rejections. Useful intermediate results remain available even when their originating problems are unresolved, enabling progress to accumulate across branches and changes of objective. Researchers provide open-ended feedback in natural language; the system interprets its actionable content and routes it to one or more execution paths for rejecting directions, proposing subproblems, continuing unresolved nodes, or pursuing new objectives with inherited memory. A sustained human–agent investigation with CoForest led to a resolution of the codimension-one case of Ghys’s conjecture on holomorphic Anosov systems, including complex dimension three. Early recursive exploration produced complementary analytic insights that the mathematician organized into a subsequent proof strategy. The system then developed and integrated the required arguments under that guidance, and the mathematical author independently verified the resulting proof. Using Intern-S2-Math, the investigation spanned four research rounds, 389 problem nodes, and approximately 861 million tokens. This investigation demonstrates the potential of CoForest to support research-level mathematics through scalable recursive reasoning, persistent memory, and flexible collaboration with human experts.

## Citation

```bibtex
@misc{zhao2026coforest,
  title        = {{CoForest}: A Conversational Harness for Mathematical Research with Recursive Solving and Persistent Memory},
  author       = {Zhao, Haiteng and
                  Gu, Yuzhe and
                  Gao, Songyang and
                  Zhang, Jiesong and
                  Hua, Zhouqi and
                  Kong, Lingkai and
                  Huang, Wenyong and
                  Zhao, Shuya and
                  Zhang, Xiaotian and
                  Xiong, Chengzhi and
                  Sun, Shuang and
                  Wang, Yan and
                  Lin, Dahua and
                  Xie, Xing and
                  Zhou, Bowen and
                  Xu, Disheng and
                  Zhang, Wenwei},
  year         = {2026},
  month        = nov,
  howpublished = {Technical report},
  doi          = {10.5281/zenodo.24488914},
  url          = {https://zhao-ht.github.io/CoForest/}
}
```

## Website

This repository contains a buildless GitHub Pages website. In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**, and save. No package installation or build step is needed. Keep the title, authors, abstract, publication date, and citation metadata in `index.html` consistent with the PDF when updating the report. Update `citation.bib` and `CITATION.cff` when the citation changes.
