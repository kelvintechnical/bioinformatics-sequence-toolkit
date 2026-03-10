# bioinformatics-sequence-toolkit

> **Data Engineering for Biological Sequences**
> Memory-efficient Python utilities for processing large-scale genomic and protein data.
> Bridges traditional software engineering logic with high-performance biological data structures.

---

## 🧬 About This Repository

This toolkit is part of the **Kelvinintech** AI Engineering portfolio, built along the career arc:

**Diesel Mechanic → Software Engineer → AI Engineer (Bioinformatics)**

Every script in this repo treats biological data the way a software engineer would treat any high-performance system:

- **DNA** = Source Code
- **Proteins** = Compiled Executables
- **Mutations** = Code Refactoring
- **Tensors** = The data structure that powers it all

---

## 📁 Repository Structure
```
bioinformatics-sequence-toolkit/
├── labs/
│   └── dna_tensor_lab/
│       ├── dna_tensor_lab.ipynb
│       └── README.md
├── utils/
├── data/
│   └── .gitkeep
├── README.md
└── .gitignore
```

---

## 🔬 Labs

### Lab 001 — DNA Tensor Lab
🔗 https://github.com/kelvintechnical/DNA_Tensor_Lab.git

**Dataset:** UniProt Swiss-Prot (Human) — 20,431 reviewed protein sequences

**What you'll build:**
- Load a real `.fasta` file using Biopython
- Build an amino acid vocabulary (tokenizer)
- Encode protein sequences into integer tensors
- Batch encode 100 proteins into a 2D tensor `[100 x 512]`
- Amino acid frequency analysis
- One-hot encoded tensors `[sequence_length x vocab_size]`

**LDE Connection:**
First stage of a Latent-based Directed Evolution pipeline — converting raw biological sequences into tensor format for downstream VAE and Transformer models.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.12 | Core language |
| PyTorch | Tensor operations |
| Biopython | Sequence parsing |
| NumPy / Pandas | Data manipulation |
| Google Colab | Lab environment |

---

## 🚀 Getting Started
```bash
git clone https://github.com/kelvintechnical/bioinformatics-sequence-toolkit.git
cd bioinformatics-sequence-toolkit
pip install torch biopython numpy pandas
```

Dataset: 🔗 https://www.uniprot.org/uniprotkb?query=reviewed:true&format=fasta
Place `.fasta` file in `data/` folder — not committed to Git.

---

## 🧠 Research Direction

**Latent-based Directed Evolution (LDE) Pipeline:**
```
Raw Sequences → Tensor Encoding → Embedding Layer
→ Transformer Encoder → Latent Space (VAE)
→ Directed Navigation → Generated Protein Candidates
```

Long-term goal: M.S. AI Engineering (WGU, Dec 2026) → Ph.D. Computational Biology

---

## 👤 Author

**Kelvin R. Tobias** — AI Engineer | Software Engineer | Bioinformatics Researcher
🔗 [Kelvinintech](https://github.com/kelvintechnical)
