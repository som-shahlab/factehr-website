<div align="center">
  <h1>📄 🧠 FactEHR</h1>
  <h4>
    <a href="https://stanford.redivis.com/datasets/bckk-15p0mwmz7">💾 Dataset</a> • 
    <a href="https://arxiv.org/abs/2412.12422">📝 Paper</a> • 
    <a href="https://github.com/som-shahlab/factehr">⚙️ Code & Docs</a>
  </h4>
  <h4>A benchmark for fact decomposition and entailment evaluation of clinical notes</h4>
  <p>
    2,168 notes • 8,665 decompositions • 987,266 entailment pairs • 1,036 human-labeled examples
  </p>
</div>

---

# 🧠 FactEHR: A Benchmark for Fact Decomposition of Clinical Notes

**FactEHR** is a benchmark dataset designed to evaluate the ability of large language models (LLMs) to perform **factual reasoning** over clinical notes. It includes:

- **2,168** deidentified notes from multiple publicly available datasets  
- **8,665** LLM-generated fact decompositions  
- **987,266** entailment pairs evaluating precision and recall of facts  
- **1,036** expert-annotated examples for evaluation


## 📚 Citation

If you use **FactEHR** in your research, please cite:

```bibtex
@article{munnangi2024factehr,
  title     = {Assessing the Limitations of Large Language Models in Clinical Fact Decomposition},
  author    = {Monica Munnangi and Akshay Swaminathan and Jason Alan Fries and Jenelle Jindal and Sanjana Narayanan and Ivan Lopez and Lucia Tu and Philip Chung and Jesutofunmi A. Omiye and Mehr Kashyap and Nigam Shah},
  journal   = {arXiv preprint arXiv:2412.12422},
  year      = {2024},
  eprint    = {2412.12422},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  note      = {v1, 17 Dec 2024}
}
