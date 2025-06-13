# MEAP-RVE-Microstructure-Generator
This repository consists of Python notebook implementations of the MEAP algorithm. 

There are 3 Jupyter Notebooks:
1. MEAP Placement: Demonstrates how MEAP places inclusions.
2. MEAP Shaking: Demonstrates periodic shaking using the mesh grid.
3. MEAP without Splines (Only Circles): Demonstrates simple MEAP using circles instead of splines.

These codes are simple to understand due to the modular and annotated nature, and are base code that should be customized according to the user's needs and preferences. For example, you can combine a) MEAP + RSA from MEAP Placement with b) periodic shaking from MEAP Shaking, to create a main program while loop that caters to your preferences. If you need help, send an email to the email addresses below, and I may be able to help. 

# Paper 
The relevant paper is "Efficient mesh assisted placement algorithm for generation of random microstructures with custom inclusion shapes up to extremely high volume fractions" published in Composites Part A. Please email me at dsaha36@gatech.edu or dhrubo.saha.117@gmail.com if you don't have access to the journal, and I will send you the paper.
Perpetual Link:
https://www.sciencedirect.com/science/article/pii/S1359835X25004063?via%3Dihub#da005

Limited Time Free Link from Elsevier until August 2025 below:
https://www.sciencedirect.com/science/article/pii/S1359835X25004063?dgcid=coauthor

# SOLIDWORKS VBA API version
Another version of the MEAP algorithm in SOLIDWORKS VBA API with a video guide is in the repository below. It generates RVEs inside SOLIDWORKS using SOLIDWORKS functionalities. It is for interested coders and not mandatory to use. The published paper describes this Python version in this repo, but not the VBA API one in that repo.
https://github.com/DhruboSaha/CompMCG

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


