# Minimap2 Python Implementation (Codon Version)

## About This Project

This is a student project of CSC 427 that implements the core features of Minimap2 in Python, compiled with Codon. It's designed to be easier to understand than the original C version while maintaining good performance.

## Project Structure
bioinformatics/  
├── main.codon            # Main program entry  
├── sketch.codon          # Minimizer calculation  
├── index.codon           # Index building and searching  
├── chain.codon           # Chaining algorithm  
├── utils.codon           # Utility functions (FASTA/FASTQ readers)  
├── test.codon            # Test module
├── test_sketch.codon     # Sketch module tests
├── test_utils.codon      # Utils module tests
├── test.fa               # Test FASTA file
├── test.fq               # Test FASTQ file
├── invalid.fq            # Invalid FASTQ test file
└── readme.md             # Project documentation
