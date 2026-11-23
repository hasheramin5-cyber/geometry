**English** | [简体中文](README.zh-CN.md) | [Español](README.es.md) | [हिन्दी](README.hi.md) | [Português](README.pt-BR.md)

# Geometry

A lifelong, open research notebook on geometry: studying known results, running experiments, writing theorems, and inventing and naming new shapes.

## Goals

- Learn geometry in public and document the journey.
- Prove, test and record theorems with clear status labels.
- Define new shapes, name them, and explore their properties.
- Visualize everything with reproducible code.

## Repository Structure

| Folder     | Purpose                                                        |
| ---------- | -------------------------------------------------------------- |
| `theory/`  | Theorems, proofs, definitions and study notes                  |
| `lab/`     | Experiments, code and observations (one folder per experiment) |
| `catalog/` | Original shapes: name, definition, properties and diagram      |

## Status Labels

Every result in this repository is tagged so its rigor is always clear:

- **Proven**: a complete, verified proof exists.
- **Conjecture**: supported by experiments, but not yet proven.
- **Observation**: a pattern noticed, with no claim of generality.

## Setup

```bash
python -m venv .venv
.venv\Scripts\Activate.ps1      # Windows (PowerShell)
# source .venv/bin/activate     # Linux / macOS
pip install -r requirements.txt
```

Optional terminal tools:

```bash
pip install -r requirements-extras.txt
```

## Tech Stack

Python (`numpy`, `scipy`, `sympy`, `matplotlib`, `shapely`, `plotly`, `networkx`, `pytest`), Jupyter, SVG.

## Status

This project is a work in progress and will be updated continuously.

## License

This repository uses two licenses:

- **Code** (scripts and notebooks in `lab/`) is licensed under the [MIT License](LICENSE-MIT).
- **Content** (theorems, proofs, notes, shape definitions and diagrams in `theory/` and `catalog/`) is licensed under [CC BY 4.0](LICENSE-CC-BY-4.0). Please credit "Hasher Amin" when reusing it.
