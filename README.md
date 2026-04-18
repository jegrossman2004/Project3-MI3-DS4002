## Section 1: Software and platform

We used Jupyter Notebooks via Google Colab for this project. Nothing needs to be installed outside of what is in the .ipynb file in the scripts folder. Windows was used for every aspect of this project


## Section 2: Documentation Map

- LICENSE.md
- README.md

scripts:
  - MI3Code.ipynb

output:
  - Project 3 MI3-Outputs.pdf

data:
  - Data Link
  - Data Appendix Project_3.pdf


## Section 3: Instructions for Reproducing Results

To reproduce the results, first open MI3Code.ipynb in Google Colab. Next, click on "Runtime" then "Change runtime type" and select the T4 GPU option. This makes the code run for around 1-2 hours rather than much longer. Next, simply run all cells in the notebook. The final two cells are optional, as they only save the pixel value dataset to the disk. The TASK variable can be adjusted from "A" to "B" depending on whether you want to do binary classification or 6-class classification. Additionally, the number of training epochs can be increased or decreased.
