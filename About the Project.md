# PROJECT TITLE: 
Advanced Jet Clustering Techniques for High Energy Physics Data Analysis:  Collider Physics

# PROJECT DESCRIPTION:
This project details the research conducted during a summer fellowship at IISER Kolkata, focusing on the application of data analysis methods using mock generated and open data from CMS detectors. The primary objective was to explore collider physics through the lens of tools, aiming to enhance the efficiency and accuracy of data interpretation from high-energy particle collisions.

Before diving into advanced analysis, an initial exploration of the open CMS data was conducted to understand its basic characteristics. Descriptive statistics were calculated to summarize the central tendency, dispersion, and shape of the dataset’s distribution. This included measures such as mean, median, standard deviation, and quartiles for variables such as:
- Number of PFJets per event
- Mass of jets
- Primary Vertices (PVs) count
- PUPPI (PileUp Per Particle Identification) MET
- Number of PF Candidates

The given clustering algorithms were implemented using FastJet package and then the code was written from scratch:
## 1. kT Algorithm: 
A widely-used clustering algorithm that combines particles based on their transverse momentum.
Prioritizes the clustering of softer particles first.

## 2. Anti-kT Algorithm: 
An alternative clustering algorithm that produces more stable and easily interpretable jets.
Prioritizes the clustering of harder particles first, producing more stable and easily interpretable jets.

## 3. Cambridge/Aachen Algorithm: 
A clustering algorithm that combines features of both kT and anti-kT algorithms, focusing on the angular distance between particles.
Clusters particles based solely on their geometrical distance in the η-φ plane, without weighting by transverse momentum.
