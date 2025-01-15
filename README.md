# Nucleic Acid Nanostructures
A custom script for AmberTools to construct and design nucleic acid nanostructures. This tool simplifies the creation of complex DNA/RNA architectures for molecular modeling and simulation workflows.
You need to install amber tools to run this code. 

# Nucleic acid Modeling with NAB (AMBER Tools)

This repository contains a NAB (Nucleic Acid Builder) script for generating Nucleic acid structures with specific rise, twist, and sequence parameters using AMBER Tools. The script outputs PDB files of modeled Nucleic acid helices and assembled Nucleic acid complexes.

## Features
- Generate Nucleic acid helices with custom sequences and geometric parameters.
- Assemble Nucleic acid complexes with multiple strands.
- Outputs PDB files for further analysis or visualization.

## Requirements
- **AMBER Tools**: The NAB script requires AMBER Tools to run. You can download and install it from [AMBER's official site](https://ambermd.org/).
- A working knowledge of NAB scripting language is helpful but not required.

## Script Overview
The script defines the following:
- **Rise**: Helical rise per residue (for DNA: `3.38 Å` and for RNA: `2.81 Å`).
- **Twist**: Helical twist per residue (for DNA: `36.0°` and for RNA: `32.7°`).
- **Nucleic acid Sequences**: Multiple Nucleic acid strands with custom sequences are specified and assembled.
- **Outputs**:
  -  Intermediate structures with pdb files.
  -  Run the xleap file using xleap -f xleap.dat to generate the final structure
