# Neuroscience-Inspired Framework for Interpreting Neural Network Training

This repository contains the implementation of a comprehensive framework inspired by neuroscience for interpreting the dynamics of neural network training. The framework treats artificial neural networks as model organisms for learning studies, using non-invasive monitoring techniques, large language models as synthetic neuroscientists, and physics-inspired diagnostics.

## Overview

Understanding the internal dynamics of neural network training remains a challenge. This framework bridges experimental neuroscience and machine learning by providing:

- **Hook-based instrumentation** (inspired by fMRI and electrophysiology) to capture layer-wise activation and gradient statistics
- **Zephyr-7B integration** as a surrogate model that maps quantitative measurements to qualitative natural language explanations
- **Rigorous validation** via faithfulness, temporal consistency, and phase alignment scores
- **Physics-inspired diagnostics** including stiffness ratio, Hamiltonian-inspired energy evolution, critical slowing detection, and convergence time estimation

## Installation

### Prerequisites

- Python 3.8 or higher
- PyTorch 1.9 or higher
- Transformers library (Hugging Face)

### Dependencies

```bash
pip install torch transformers numpy scipy
