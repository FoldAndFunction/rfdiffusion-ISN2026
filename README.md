# RFdiffusion — ISN Mendoza 2026

Teaching notebook for designing protein binders using **RFdiffusion**, **ProteinMPNN**, and **AlphaFold/ColabDesign**.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FoldAndFunction/rfdiffusion-ISN2026/blob/main/rfdiffusion_course_3.ipynb)

## Practical exercise

The notebook guides students through:

1. Generating binder backbones with RFdiffusion.
2. Designing sequences with ProteinMPNN.
3. Validating complexes with AlphaFold.
4. Comparing confidence, interface quality, hotspot coverage, and structural clashes.
5. For the Rab11 example, assessing whether selected binders occlude the GTP/GDP-binding site.

## Usage

1. Open the notebook in Google Colab.
2. Select a GPU and the **2026.07** runtime.
3. Run the cells in order.
4. Keep `num_designs = 2` and `num_seqs = 2` for the classroom exercise.
5. Re-run ProteinMPNN-AF2 block if the scores are not good enough. 

The notebook is distributed without saved results, while retaining the predefined Rab11 structure, contigs, and hotspots.

## Important

AlphaFold confidence and geometric filtering do not demonstrate experimental binding. Designs require additional computational assessment and wet-lab validation.

Notebook version: **1.1.2**

## Software

* [RFdiffusion](https://github.com/RosettaCommons/RFdiffusion)
* [ProteinMPNN](https://github.com/dauparas/ProteinMPNN)
* [ColabDesign](https://github.com/sokrypton/ColabDesign)
