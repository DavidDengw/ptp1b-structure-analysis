# Structural analysis of PTP1B active and allosteric sites using PyMOL
A structural exploration of PTP1B using PyMOL, focusing on the spatial relationship between its catalytic site and literature-reported allosteric regions. This project connects protein structure to signaling function and drug design considerations.

## Biological Context
PTP1B is a protein tyrosine phosphatase that attenuates both insulin and leptin signaling by dephosphorylating key components such as the insulin receptor and JAK2. Through this role, it contributes to the regulation of glucose metabolism, energy balance, and body weight.
Because PTP1B shares a highly conserved catalytic mechanism with other members of the PTP family, directly targeting its active site presents challenges for drug specificity. As a result, current research focuses on identifying allosteric sites that can modulate enzyme activity without disrupting other essential phosphatases.

## Objective
This project aims to:
* Identify and visualize key catalytic residues, including Cys215 and associated structural loops
* Map literature-reported allosteric sites (I19, Q78, D245, P302)
* Analyze the spatial separation between catalytic and allosteric regions

## Methods
Structural analysis was performed using PyMOL with PDB file downloaded from crystal structure 2HNQ from the Protein Data Bank, and AF-P18031-F1-v6 from AlphaFold.
The crystal structure 2HNQ contains only the catalytic domain, deposited residue count 321. The AF-P18031-F1-v6 from AlphaFold contains the entire protein 435 amino acids.

### Residue selection and visualization:
* Residues were selected using PyMOL selection commands (e.g., select wpd_loop, resi 177-188), guided by literature-defined catalytic and allosteric positions.
* Catalytic cysteine (Cys215), WPD loop, and surrounding catalytic loop were highlighted
* Allosteric residues (I19, Q78, D245, P302) were selected individually and colored distinctly


### Coloring scheme:
* Catalytic cysteine: red
* Catalytic loop: light green
* WPD loop: brown
* Allosteric residues: I19 green, Q78 orange, D245 purple, P302 light blue

## Results
### Figure 1 – Global structure organization
(Insert image)
The overall fold shows a compact catalytic domain (blue), regulatory domain (gray), and C terminus ER anchor domain (yellow).
### Figure 2 – Active site architecture
(Insert image)
Cys215 (red) is positioned within a well-defined catalytic pocket, coordinated by surrounding catalytic loop (light green) and WPD loop (brown) that enable substrate binding and phosphatase activity. The target phosphate group is represented as a sphere model (gray).
### Figure 3 – Allosteric sites
(Insert image)
Allosteric residues are distributed away from the catalytic pocket, primarily on surface-accessible regions of the protein.
