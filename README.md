# SMILES-to-PDB-Converter
This Python script utilizes the RDKit library to convert SMILES (Simplified Molecular Input Line Entry System) strings into PDB (Protein Data Bank) format files. The script reads a CSV file containing SMILES strings and their associated drug names, generates 3D molecular structures using RDKit, and writes them to PDB files

## Key Features

- Reads SMILES strings and drug names from a CSV file
- Converts SMILES to RDKit molecule objects
- Writes valid molecules to PDB files in a specified output directory
- Robust error handling for file operations and invalid SMILES strings

## Requirements

Make sure you have the following installed:

- Python
- RDKit library installed
You can install RDKit via python command: pip install rdkit

## Prerequisites

The script requires a CSV file named `ligands.csv` in the same directory. This file must contain the columns "[Names, Smiles]"

##  License
This project is licensed under the MIT License
