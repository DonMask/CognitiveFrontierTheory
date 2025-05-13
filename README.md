# Beyond the Known: A Unified Theory of Cognitive Limits

This repository contains the LaTeX source and compiled PDF for the essay **“Beyond the Known: A Unified Theory of Cognitive Limits”** by Teodor Berger, presenting the Cognitive Frontier Theory (CFT) and Axiom 13.

## Access the Essay

- **View Online**: [Open the essay in your browser](https://donmask.github.io/CognitiveFrontierTheory/)  
  *(Note: Requires GitHub Pages configuration as described below)*
- **Download PDF**: [Download the essay as a PDF](https://raw.githubusercontent.com/DonMask/CognitiveFrontierTheory/main/CognitiveFrontierTheory.pdf)

## Project Structure

CognitiveFrontierTheory/  
├── CognitiveFrontierTheory.pdf  # Compiled PDF of the essay  
├── main.tex                    # LaTeX source  
├── references.bib              # BibTeX references  
├── LICENSE                     # License file (CC BY 4.0)  
└── README.md                   # This file  

## About

This essay introduces the Cognitive Frontier Theory (CFT), a framework that unites 20 unsolved problems—10 mathematical (e.g., Riemann Hypothesis) and 10 physical (e.g., Nature of Time)—into an emergent network defined by a collective cognitive limit. It proposes a shift from the current scientific paradigm (\(\Pi_{\text{curent}}\)) to a new one (\(\Pi_{\text{new}}\)), inspired by Axiom 13 (DOI: 10.5281/zenodo.15398105), and explores the role of AI in breaking these limits.

## Compilation Instructions

1. Open Overleaf (or your local TeX environment).
2. Upload or place `main.tex`, `references.bib`, and `LICENSE` in the project root.
3. Compile with **pdfLaTeX** (no external images needed; TikZ handles all diagrams).
4. The bibliography will render automatically from `references.bib`, generating `CognitiveFrontierTheory.pdf`.

## Configuring GitHub Pages (Optional)

To enable viewing the PDF directly in the browser:
1. Go to **Settings > Pages** in this repository.
2. Set the source to the `main` branch and `/root`.
3. Add an `index.html` file with the following content:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Cognitive Frontier Theory</title>
   </head>
   <body>
     <h1>Beyond the Known: A Unified Theory of Cognitive Limits</h1>
     <p>View the essay directly in your browser:</p>
     <a href="CognitiveFrontierTheory.pdf" target="_blank">Open PDF in Browser</a>
     <p>Or download the PDF:</p>
     <a href="CognitiveFrontierTheory.pdf" download>Download PDF</a>
   </body>
   </html>


   License
This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).
See the LICENSE file or visit: https://creativecommons.org/licenses/by/4.0/

Contact
•  Author: Teodor Berger
•  Email: bergerteodor@googlemail.com
•  GitHub: DonMask
Project Link
•  Repository: https://github.com/DonMask/CognitiveFrontierTheory
