# Machine Learning Enabled Nonlinear Phase Noise Mitigation for Coherent Optical Systems

**MSc Thesis in Photonics** — Sergio Steven Gutierrez Pulgarin  
Lund University · KTH Royal Institute of Technology · RISE Research Institutes of Sweden  
May 2020

---

## Abstract

Long-haul coherent optical fiber systems are fundamentally limited by nonlinear phase noise arising from the Kerr effect — a signal-power-dependent phase distortion that degrades constellation quality at high launch powers. This thesis investigates the use of machine learning classifiers (Support Vector Machines and Random Forests) to replace conventional hard-decision boundaries in the receiver, optimizing decision regions directly from the received constellation data. The approach improves symbol error rate performance under both linear and nonlinear noise conditions across 4-QAM, 16-QAM, 64-QAM, and 256-QAM modulation formats.

## Reading the thesis

The compiled PDF is included: [**Thesis.pdf**](Thesis.pdf)

## Repository structure

```
Thesis.tex              Main LaTeX document
Chapter1.tex – Chapter5.tex   Individual chapters
acronyms.tex            Acronym definitions
format.tex              Formatting and style
frontpage.tex           Title page
Reference.bib           Bibliography
Images/                 All figures (~90 images)
ExtraFiles/             Popular summary and self-reflection (examination requirements)
dmathesis.cls           LaTeX document class
```

## Building from source

Requires a LaTeX distribution (TeX Live or MiKTeX) with `pdflatex` and `bibtex`:

```bash
pdflatex Thesis.tex
bibtex Thesis
pdflatex Thesis.tex
pdflatex Thesis.tex
```

## Related repository

The simulation code and ML experiments for this thesis are in:  
[**optical-fiber-ml-classifier**](https://github.com/ChiefGuti/optical-fiber-ml-classifier)

## License

Provided for reference and academic use. Please cite appropriately if you use any content.
