# DNA_Tensor_Lab

> **Tensor Engineering for Biological Sequences**
> Converting real human protein data into PyTorch tensors —
> the foundational step of a Latent-based Directed Evolution (LDE) pipeline.

---

## 🧬 About This Repository

Part of the **Kelvinintech** AI Engineering portfolio.

**Career Arc: Diesel Mechanic → Software Engineer → AI Engineer (Bioinformatics)**

- **DNA** = Source Code
- **Proteins** = Compiled Executables
- **Mutations** = Code Refactoring
- **Tensors** = The data structure that powers it all

---

## 📁 Repository Structure
```
DNA_Tensor_Lab/
├── labs/
│   └── dna_tensor_lab/
│       ├── dna_tensor_lab.ipynb
│       └── README.md
├── data/
│   └── .gitkeep
├── README.md
└── .gitignore
```

---

## 🔬 Lab 001 — DNA Tensor Lab

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

## 🔗 Repository

🔗 https://github.com/kelvintechnical/DNA_Tensor_Lab.git

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
git clone https://github.com/kelvintechnical/DNA_Tensor_Lab.git
cd DNA_Tensor_Lab
pip install torch biopython numpy pandas
```

Dataset: 🔗 https://www.uniprot.org/uniprotkb?query=reviewed:true&format=fasta
Place `.fasta` file in `data/` — not committed to Git.

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
