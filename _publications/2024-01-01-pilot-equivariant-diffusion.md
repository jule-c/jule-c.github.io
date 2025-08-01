---
title: "PILOT: equivariant diffusion for pocket-conditioned de novo ligand generation with multi-objective guidance via importance sampling"
collection: publications
category: manuscripts
permalink: /publication/2024-pilot-equivariant-diffusion
excerpt: 'A novel approach for generating drug-like molecules that fit specific protein binding sites using equivariant diffusion models with multi-objective guidance.'
date: 2024-01-01
venue: 'Chemical Science'
slidesurl: # Add slides URL if available
paperurl: # Add paper URL if available
citation: 'Cremer, J., Le, T., Noé, F., Clevert, D.A., & Schütt, K.T. (2024). &quot;PILOT: equivariant diffusion for pocket-conditioned de novo ligand generation with multi-objective guidance via importance sampling.&quot; <i>Chemical Science</i>. 15(36), 14954-14967.'
---

This work introduces PILOT, a groundbreaking approach for structure-based drug design that combines equivariant diffusion models with multi-objective guidance. The method generates novel ligand molecules that are both chemically valid and optimized to bind to specific protein pockets while satisfying multiple drug-like properties.

## Key Contributions

- **Equivariant Architecture**: Developed SE(3)-equivariant diffusion models that respect the rotational and translational symmetries of molecular systems
- **Pocket Conditioning**: Introduced mechanisms to condition molecule generation on specific protein binding sites
- **Multi-Objective Guidance**: Implemented importance sampling techniques to balance multiple objectives including binding affinity, drug-likeness, and synthetic accessibility
- **Experimental Validation**: Demonstrated superior performance compared to existing methods on benchmark datasets

## Impact

This work has been highly cited (18 citations) and represents a significant advancement in AI-driven drug discovery, providing a practical tool for medicinal chemists to explore novel chemical space while maintaining focus on target-specific binding.

## Technical Innovation

The method leverages the mathematical structure of molecular systems through equivariant neural networks, ensuring that the generated molecules maintain physical consistency while being optimized for multiple therapeutic objectives simultaneously.
