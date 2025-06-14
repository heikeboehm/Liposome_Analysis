# Liposome_Analysis
Comprehensive analysis framework for liposome characterization including NTA (Nanoparticle Tracking Analysis) and future DLS measurements.

## Overview

This framework provides sophisticated analysis tools for characterizing synthetic vesicles and liposomes, with a focus on rigorous statistical treatment and uncertainty propagation. Currently implements comprehensive NTA data analysis with plans to expand to DLS and other characterization methods.

## Current Features: NTA Analysis

### What it does
- Analyzes NTA data files from ZetaView (Particle Metrix QUATT, ZetaView version 8.06.01 SP1)
- Handles both single files and multi-file replicate analysis
- Performs bin-by-bin averaging with uncertainty propagation
- Calculates comprehensive statistics with asymmetric confidence bounds
- Generates publication-ready visualizations

### Key Capabilities
- **Multi-file averaging** with rigorous uncertainty quantification
- **Multiple distribution types**: Number, volume, and surface area weighted
- **D-value calculations** (D10, D50, D90) with confidence bounds
- **Automated metadata extraction** and quality control
- **Comprehensive output files** for downstream analysis
- **Standardized visualizations** across linear and logarithmic scales

## Files

- `NTA_Analysis_Framework.ipynb` - Complete Jupyter notebook with sequential workflow

## Usage

1. Execute cells sequentially starting from Cell 01
2. Configure file paths and analysis parameters in Cell 01
3. Follow the guided workflow through data processing and visualization
4. Output files are automatically generated with standardized naming

## Requirements

- Python 3.x
- Jupyter Notebook
- Standard scientific libraries (numpy, pandas, matplotlib, scipy)

## Author

Heike Boehm, Department of Cellular Biophysics, MPI for Medical Research, Heidelberg, Germany

## License

MIT License - see LICENSE file for details

## Coming Soon

- DLS (Dynamic Light Scattering) analysis module
- Additional characterization methods

## Related Resources

- [EV-Maker Educational Program](https://publish.obsidian.md/heikesdiscoverygarden/EV-Maker-Overview)
- [Heike's Discovery Garden](https://publish.obsidian.md/heikesdiscoverygarden)
