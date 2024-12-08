# 📸 Computer Vision Paper Implementations

[![Python 3.8+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

This repository contains (mostly PyTorch) implementations of seminal computer vision papers.

## 📚 Implemented Papers

| Paper | Year | Original Paper | Implementation | Key Points |
|-------|------|----------------|----------------|------------|
| LeNet-5 | 1998 | [Paper](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf) | [Implementation](papers/lenet5_1998) | First successful CNN architecture |

## 🎯 Project Goals

- Implement influential computer vision papers with modern best practices
- Provide clear, well-documented code that others can learn from
- Include experimentation and results analysis

## 🏗️ Repository Structure

```
computer-vision-papers/
├── papers/
│   └── paper_name_year/
│       ├── README.md
│       ├── notebook.ipynb
│       ├── src/
│       └── requirements.txt
└── common/
    └── utils/ # Shared utilities
```

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/agolebiowska/computer-vision-papers.git
cd computer-vision-papers
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate
```

3. Install base requirements:
```bash
pip install -r requirements.txt
```

4. Navigate to specific paper implementation and install its requirements:
```bash
cd papers/paper_name_year
pip install -r requirements.txt
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
