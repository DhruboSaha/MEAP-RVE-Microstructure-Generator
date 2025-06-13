# MEAP-RVE-Microstructure-Generator
This repository consists of Python notebook implementations of the MEAP algorithm. 

There are 3 Jupyter Notebooks:
1. MEAP Placement: Demonstrates how MEAP places inclusions.
2. MEAP Shaking: Demonstrates periodic shaking using the mesh grid.
3. MEAP without Splines (Only Circles): Demonstrates simple MEAP using circles instead of splines.

These codes are simple to understand, and are base code that should be modified and customized according to the user's needs and preferences. 

# Paper 
The relevant paper is "Efficient mesh assisted placement algorithm for generation of random microstructures with custom inclusion shapes up to extremely high volume fractions" published in Composites Part A. Please email me at dsaha36@gatech.edu or dhrubo.saha.117@gmail.com if you don't have access to the journal, and I will send you the paper.
https://www.sciencedirect.com/science/article/pii/S1359835X25004063?via%3Dihub#da005

# Citation
If you use the codes in your work or find them useful, please cite the paper:

```bibtex
@article{saha2025meap,
  author  = {Saha, Dhrubo and Sun, Li and Lai, Chang Quan},
  title   = {Efficient mesh assisted placement algorithm for generation of random microstructures with custom inclusion shapes up to extremely high volume fractions},
  journal = {Composites Part A: Applied Science and Manufacturing},
  year    = {2025},
  volume  = {198},
  pages   = {109112},
  doi     = {10.1016/j.compositesa.2025.109112}
}
```bibtex
# SOLIDWORKS VBA API version
Another version of the MEAP algorithm in SOLIDWORKS VBA API with a video guide is in the repository below. It generates RVEs inside SOLIDWORKS using SOLIDWORKS functionalities. It is for interested coders and not mandatory to use. The paper describes this Python version, but not the VBA API one.
https://github.com/DhruboSaha/CompMCG
