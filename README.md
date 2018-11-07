# cv_analysis

Calculate anodic and cathodic peak curents from cyclic voltammetry experimental data file list. 
Plots cyclic voltammetry, anodic and cathodic peaks and linear regression of capacitive backgroud calculated for each set. Produces output text file with anodic and cathodic peak information (current and potential). Developed for one cycle only and IUPAC's convention. 

### How to run: 
1) Open a terminal/command window.
2) Change directiories to the location where this file is saved.
3) Run the program file
```python cv_analysis.py```
4) When solicited, type the name of csv file containing file names.

### How to produce your input.csv file list:
1) Open a terminal/command window.
2) Change directiories to the location where your data is saved.
3) For mac/linux terminal: 
```ls |grep .txt```
4) For Windows command prompt 
```ls |grep .txt```
5) Copy list to file, separate itens with comma

 ### Calculations based on the following arcticles: 
 1. [Theory and Application of Cyclic Voltammetry for Measurement of Electrode Reaction Kinetics](https://pubs.acs.org/doi/10.1021/ac60230a016)
 2. [A Practical Beginner’s Guide to Cyclic Voltammetry](https://pubs.acs.org/doi/10.1021/acs.jchemed.7b00361)
