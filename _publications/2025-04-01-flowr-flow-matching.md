---
title: "FLOWR: Flow Matching for Structure-Aware De Novo, Interaction-and Fragment-Based Ligand Generation"
collection: publications
category: manuscripts
permalink: /publication/2025-flowr-flow-matching
excerpt: 'Novel flow matching approach for structure-aware ligand generation that incorporates protein-ligand interactions and fragment-based design principles.'
date: 2025-04-01
venue: 'arXiv preprint'
slidesurl: # Add slides URL if available
paperurl: 'https://arxiv.org/abs/2504.10564'
citation: 'Cremer, J., Irwin, R., Tibo, A., Janet, J.P., Olsson, S., & Clevert, D.A. (2025). &quot;FLOWR: Flow Matching for Structure-Aware De Novo, Interaction-and Fragment-Based Ligand Generation.&quot; <i>arXiv preprint arXiv:2504.10564</i>.'
---

FLOWR introduces a novel flow matching approach for molecular generation that combines structure-based design with fragment-based drug discovery principles. This method represents a significant advancement in AI-driven drug discovery by incorporating multiple design modalities within a unified framework.

## Key Innovations

- **Flow Matching Architecture**: Advanced continuous normalizing flow approach that provides more stable training than diffusion models
- **Multi-Modal Generation**: Unified framework supporting de novo design, interaction-guided generation, and fragment-based approaches
- **Structure Awareness**: Deep integration of 3D protein structure information to guide molecular generation
- **Fragment Integration**: Novel mechanisms for incorporating known molecular fragments and scaffolds

## Technical Contributions

### Flow Matching Framework
- Developed continuous normalizing flows specifically adapted for molecular systems
- Implemented efficient training procedures that avoid common instabilities of diffusion models
- Created scalable architectures suitable for large-scale molecular datasets

### Multi-Modal Design
The method supports three complementary design paradigms:
1. **De Novo Generation**: Creating entirely new molecular structures from scratch
2. **Interaction-Based Design**: Leveraging specific protein-ligand interaction patterns
3. **Fragment-Based Optimization**: Building molecules around known pharmacophore fragments

## Applications and Impact

FLOWR addresses critical challenges in modern drug discovery:

- **Lead Optimization**: Systematic improvement of existing compounds
- **Scaffold Hopping**: Finding novel chemical scaffolds with similar biological activity
- **Fragment Linking**: Connecting molecular fragments to create drug-like compounds
- **Structure-Based Design**: Rational design based on target protein structure

## Future Directions

This work opens new avenues for:
- Integration with experimental high-throughput screening
- Incorporation of ADMET (Absorption, Distribution, Metabolism, Excretion, Toxicity) properties
- Multi-target drug design approaches
- Personalized medicine applications

The FLOWR framework represents a significant step toward practical AI-driven drug discovery tools that can be seamlessly integrated into pharmaceutical research workflows.
