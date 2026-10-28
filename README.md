<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=064E3B,059669,34D399&height=220&section=header&text=Numerical%20Series%20Generator&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Linear%20Sequence%20Algorithms%20and%20Stream%20Generator%20Optimization&descSize=16&descAlignY=60&descAlign=50" width="100%" alt="Numerical Series Generator Banner"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Python%203.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Language Python 3.10+"/>
  <img src="https://img.shields.io/badge/Domain-Sequence%20Algorithms-059669?style=for-the-badge" alt="Domain Sequence Algorithms"/>
  <img src="https://img.shields.io/badge/Complexity-O%28N%29%20Time%20/%20O%281%29%20Space-34D399?style=for-the-badge" alt="Complexity O(N) Time / O(1) Space"/>
  <img src="https://img.shields.io/badge/License-MIT-A7F3D0?style=for-the-badge" alt="License MIT"/>
</p>

---

## Executive Summary / Overview
### Problem Statement & Context
Generating numerical series is one of the primary tasks in computational programming. When operating at scale, generating sequences via naive memory buffering can quickly consume excessive RAM, demanding lazy stream generator patterns.

### Solution Overview
This repository presents clean, efficient implementations for **Generating Numerical Series** in Python. It analyzes range bounds, sequence formatting, and memory consumption when producing linear series up to N.

---

## Interactive Table of Contents
- [Executive Summary / Overview](#executive-summary--overview)
- [Key Features & Capabilities](#key-features--capabilities)
- [System Architecture / Pipeline](#system-architecture--pipeline)
- [Tech Stack Breakdown](#tech-stack-breakdown)
- [Reproducible Quickstart & Setup](#reproducible-quickstart--setup)
- [Project Directory Layout](#project-directory-layout)
- [Author & Contributions](#author--contributions)

---

## Key Features & Capabilities
- **Linear Sequence Generation:** Deterministic generation of numbers from 1 to N with customizable step sizes.
- **Minimal Space Overhead:** Implements iterative streaming with O(1) auxiliary space complexity.
- **Edge-Case Tolerance:** Gracefully handles non-positive bounds and single-element ranges.

---

## System Architecture / Pipeline
```mermaid
flowchart LR
    N[Input Limit N] --> Range[Range Iterator: range 1, N+1]
    Range --> Stream[Item Stream]
    Stream --> Format[Formatted Standard Output]
```

---

## Tech Stack Breakdown
| Layer | Technology | Details |
| :--- | :--- | :--- |
| **Languages** | Python 3.10+ | Pure Python standard library |
| **Libraries** | Built-in Range Primitives | Generator expressions and iterators |
| **Tools** | Jupyter Notebook | Interactive execution and validation |
| **Architecture** | Stream Generator Pipeline | Lazy linear iteration with O(1) auxiliary RAM |

---

## Reproducible Quickstart & Setup
```bash
# 1. Clone repository
git clone https://github.com/suryateja-155/print-n-numbers.git
cd print-n-numbers

# 2. Run notebook
jupyter notebook "print n numbers.ipynb"
```

---

## Project Directory Layout
```text
print-n-numbers/
├── print n numbers.ipynb   # Sequence generation and formatting notebook
└── README.md               # Technical overview and algorithmic complexity
```

---

## Author & Contributions

**Gettupalli Surya Teja**  
- GitHub Profile: [@suryateja-155](https://github.com/suryateja-155)  
- Portfolio Index: [Gettupalli-Surya-Teja](https://github.com/suryateja-155/Gettupalli-Surya-Teja)

Contributions, issue reports, and feedback are always welcome! Feel free to open an issue or pull request.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=064E3B,059669,34D399&height=100&section=footer" width="100%" alt="Footer Banner"/>
</p>
