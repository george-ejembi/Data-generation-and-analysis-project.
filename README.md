# Water Quality & Antimicrobial Resistance Analysis

[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/psf/black)
[![CI](https://github.com/yourusername/water-quality-amr-analysis/workflows/CI/badge.svg)](https://github.com/yourusername/water-quality-amr-analysis/actions)

A comprehensive data generation and analysis platform for investigating the relationship between water quality parameters and antimicrobial resistance (AMR) patterns.

# Overview

This project provides a complete pipeline for synthetic data generation, real data integration, and advanced analytics to explore the critical intersection of environmental water quality and antimicrobial resistance. The framework enables researchers to:

- Generate realistic synthetic water quality and AMR datasets
- Integrate and preprocess heterogeneous environmental and microbiological data
- Perform statistical analysis and machine learning to identify correlations
- Create interactive visualizations and dashboards for exploratory analysis

# Features

- **Synthetic Data Generation**: Generate realistic water quality parameters (pH, turbidity, dissolved oxygen, coliform counts) and corresponding AMR profiles
- **Data Integration**: Seamlessly combine water quality measurements with antimicrobial susceptibility testing results
- **Temporal Analysis**: Analyze seasonal patterns and temporal trends in both water quality and resistance profiles
- **Machine Learning Pipeline**: Predict AMR patterns based on water quality indicators using various ML algorithms
- **Interactive Dashboard**: Explore relationships through dynamic visualizations and filtering
- **Comprehensive Testing**: Unit tests, integration tests, and data validation modules

# Data Structure

### Water Quality Parameters
- Physical: pH, temperature, turbidity, total dissolved solids (TDS)
- Chemical: dissolved oxygen (DO), biochemical oxygen demand (BOD), chemical oxygen demand (COD)
- Biological: total coliforms, *E. coli*, enterococci counts
- Environmental: sampling depth, location coordinates, season, rainfall

### AMR Parameters
- Bacterial isolates: *E. coli*, *Klebsiella pneumoniae*, *Pseudomonas aeruginosa*
- Antimicrobial classes: beta-lactams, fluoroquinolones, aminoglycosides, tetracyclines
- Resistance phenotypes: MIC values, categorical interpretation (S/I/R)
- Molecular markers: resistance gene presence (optional)

# Installation

### Prerequisites
- Python 3.9 or higher
- Conda (recommended) or pip
- Git

# Quick Start with Conda

```bash
# Clone the repository
git clone https://github.com/yourusername/water-quality-amr-analysis.git
cd water-quality-amr-analysis

# Create and activate conda environment
conda env create -f environment.yml
conda activate water-amr-analysis

# Install package in development mode
pip install -e .
