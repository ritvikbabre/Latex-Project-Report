# VR Driving Learning Simulator - LaTeX Project Report

This repository contains the LaTeX source files for the M.Tech project report on **VR Driving Learning Simulator** for driving schools.

## Project Overview

A high-fidelity VR-based driving simulator designed for driving school training environments, featuring:
- Meta Quest 3 VR headset integration
- Custom Bluetooth-enabled hardware controls (steering wheel, pedals, gear shifter)
- Realistic vehicle physics and environmental simulation
- Performance analytics for driver evaluation

## Building the PDF

### Prerequisites
- LaTeX distribution (MiKTeX, TeX Live, or TinyTeX)
- Biber (for bibliography processing)

### Quick Build Commands

#### Windows (PowerShell)
```powershell
pdflatex -interaction=batchmode main.tex
biber main
pdflatex -interaction=batchmode main.tex
pdflatex -interaction=batchmode main.tex
```

#### Linux/Mac
```bash
pdflatex -interaction=batchmode main.tex
biber main
pdflatex -interaction=batchmode main.tex
pdflatex -interaction=batchmode main.tex
```

### Using VS Code with LaTeX Workshop

If you're using VS Code with the LaTeX Workshop extension:
1. Open `main.tex`
2. Save the file (Ctrl+S) - auto-compilation will trigger
3. Click the PDF preview icon or press `Ctrl+Alt+V`

## Project Structure

```
.
├── main.tex              # Main document file
├── metadata.tex          # Project metadata (title, authors, advisors)
├── reportSty.sty         # Custom style package
├── ref.bib              # Bibliography database
├── chapters/            # Chapter files
│   ├── introduction.tex
│   ├── lit_review.tex
│   ├── system_analysis.tex
│   └── results.tex
├── front/               # Front matter
│   ├── cover.tex
│   ├── declaration.tex
│   ├── abstract.tex
│   └── AckAndWork.tex
├── figs/                # Figures and diagrams
└── tables/              # Table files
```

## Author

**Ritvik Babre**  
Roll Number: 242190002  
M.Tech. in Computer Engineering (Specialized in Software Engineering)  
Veermata Jijabai Technological Institute, Mumbai

**Project Guide:** Dr. V.B. Nikam

## License

This project report is submitted as part of the M.Tech program requirements.
