🧬 **Mitochondrial Membrane Molecular Dynamics Analyses**

This repository contains Python scripts and Jupyter/Colab notebooks developed to analyze molecular dynamics (MD) simulations of mitochondrial membranes, modeled using the MARTINI 3 coarse-grained force field.
The membrane compositions and system setup were based on the configurations described in the following reference:

*Konar S, Arif H, Allolio C. Biophys J. 2023, 122(21):4274-4287.*

🧫 **Tools and Libraries**

All analyses were performed using a combination of the following Python-based tools:

MDAnalysis
: for trajectory loading and atom/group selections.

Lipyphilic
: for detailed lipid bilayer property calculations.

FATSLiM
: for leaflet detection and membrane topology analysis.

These libraries together allow for a quantitative and visual exploration of lipid organization, membrane asymmetry, and molecular rearrangements.

📁 **Repository Contents**

Each notebook/script focuses on a specific type of analysis:

thickness_density.ipynb
Calculates the membrane thickness and density profiles of different molecular components (water, lipids, cholesterol, etc.) along the z-axis.

flip-flop_leaflets.ipynb
Evaluates flip-flop events of cholesterol molecules between the two leaflets, providing insight into lipid exchange and membrane asymmetry.

lipid_environment.ipynb
Analyzes the local environment of individual lipids, identifying neighboring lipid types and evaluating the organization and heterogeneity within each leaflet.

💡 **Purpose**

These analyses aim to deepen the understanding of mitochondrial membrane structure and dynamics, particularly how cholesterol and other lipid components influence bilayer stability and molecular interactions.
All notebooks are written in a tutorial-like format to promote reproducibility and facilitate use by other researchers interested in lipid membrane simulations.
