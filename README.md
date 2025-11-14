# DarkBench+: An Extended Benchmark for Evaluating Dark Patterns in Large Language Models

<div align="center">

[![AAAI-26](https://img.shields.io/badge/AAAI-2026-blue.svg)](https://aaai.org/conference/aaai-26/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8+-yellow.svg)](https://www.python.org/)

**✨ Accepted by AAAI-26 ✨**

</div>

---

## 📋 Overview

DarkBench+ is an extended benchmark designed to evaluate dark patterns in Large Language Models (LLMs). This comprehensive dataset enables researchers to assess how well LLMs can identify and understand various types of dark patterns in user interfaces and interactions.

<div align="center">
<img src="figure/fig1.png" width="800px">
<p><em>Figure 1: Examples of Dark Pattern Categories (Substantive Evasion, Credibility Hijacking, and Difference Analysis)</em></p>
</div>

## 🎯 Key Features

- **Comprehensive Coverage**: Extended benchmark covering various dark pattern categories
- **Multilingual Support**: Includes both English and Chinese datasets
- **Structured Annotations**: Carefully labeled and organized data for consistent evaluation
- **Research-Ready**: Pre-processed and ready for immediate use in research projects

<div align="center">
<img src="figure/fig2.png" width="800px">
<p><em>Figure 2: DarkBench+ Benchmark Construction Pipeline</em></p>
</div>

## 📊 Dataset Structure

The benchmark includes two main datasets:

```
data/
├── organized_labeled_darkbench_english.csv  # English version (239KB)
└── organized_labeled_darkbench.csv          # Chinese version (186KB)
```

Each dataset contains:
- **Dark Pattern Examples**: Real-world instances of dark patterns
- **Category Labels**: Systematic categorization of pattern types
- **Annotations**: Detailed labeling for evaluation purposes

<div align="center">
<img src="figure/fig3.png" width="800px">
<p><em>Figure 3: Dark Pattern Category Taxonomy</em></p>
</div>

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/lnvadev/DarkBench_Plus.git
cd DarkBench_Plus
```

### Usage

```python
import pandas as pd

# Load English dataset
df_en = pd.read_csv('data/organized_labeled_darkbench_english.csv')
print(f"English dataset: {len(df_en)} samples")

# Load Chinese dataset
df_zh = pd.read_csv('data/organized_labeled_darkbench.csv')
print(f"Chinese dataset: {len(df_zh)} samples")

# Explore the data
print(df_en.head())
```

<div align="center">
<img src="figure/fig4.png" width="800px">
<p><em>Figure 4: Model Performance Comparison (Dark Pattern Trigger Rates)</em></p>
</div>

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues or pull requests.

## 📧 Contact

For questions or collaboration opportunities, please open an issue in this repository.

---

<div align="center">

**Made with ❤️ for the AI Safety Research Community**

</div>
