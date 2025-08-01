---
title: "Multi-Objective Guidance via Importance Sampling for Target-Aware Diffusion-based De Novo Ligand Generation"
collection: publications
category: conferences
permalink: /publication/2024-multi-objective-guidance-icml
excerpt: 'ICML workshop paper on multi-objective optimization techniques for diffusion-based molecular generation using importance sampling.'
date: 2024-07-01
venue: "ICML'24 Workshop ML for Life and Material Science: From Theory to Industry Applications"
slidesurl: # Add slides URL if available
paperurl: # Add paper URL if available
citation: 'Cremer, J., Le, T., Noe, F., Clevert, D.A., & Schütt, K.T. (2024). &quot;Multi-Objective Guidance via Importance Sampling for Target-Aware Diffusion-based De Novo Ligand Generation.&quot; <i>ICML\'24 Workshop ML for Life and Material Science: From Theory to Industry Applications</i>.'
---

This ICML workshop paper focuses on the multi-objective optimization aspects of molecular generation, specifically exploring how importance sampling can be used to balance multiple competing objectives in drug design.

## Key Contributions

- **Importance Sampling Framework**: Novel application of importance sampling to molecular generation
- **Multi-Objective Optimization**: Systematic approach to balancing competing drug design objectives
- **Target Awareness**: Integration of target-specific constraints into the generation process
- **Practical Implementation**: Computationally efficient algorithms suitable for real-world applications

## Multi-Objective Challenges

Drug design inherently involves multiple competing objectives:
- **Binding Affinity**: Strong interaction with the target protein
- **Drug-likeness**: Adherence to Lipinski's rule of five and similar guidelines
- **Synthetic Accessibility**: Feasibility of chemical synthesis
- **Safety Profile**: Minimal off-target effects and toxicity
- **ADMET Properties**: Appropriate absorption, distribution, metabolism, excretion, and toxicity

## Technical Innovation

The work introduces:
- Importance sampling strategies that maintain generation quality while satisfying multiple constraints
- Adaptive weighting schemes for different objectives
- Efficient sampling procedures that scale to high-dimensional molecular spaces
- Integration with existing diffusion model architectures

## Impact on Drug Discovery

This research addresses one of the most challenging aspects of computational drug design: the need to simultaneously optimize multiple, often conflicting, molecular properties. The importance sampling approach provides a principled way to navigate these trade-offs.

## Community Engagement

Presentation at the ICML workshop provided opportunities to:
- Share insights with the broader ML for science community
- Receive feedback from both ML researchers and domain experts
- Establish collaborations with other research groups
- Influence the development of evaluation standards in the field
