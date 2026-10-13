# Visualize Plastid Genome Structure

**Student Name:** Nesie D. Calipas

## Overview

In this laboratory activity, I used OGDRAW to create a circular plastid genome map of *Glycine soja* isolate HAAS216. The purpose of this activity was to visualize the genome structure, identify its major regions, examine gene locations and directions, and observe the GC content.

## Genome Information

- **Scientific Name:** *Glycine soja*
- **Isolate:** HAAS216
- **NCBI Accession Number:** PX591265.1
- **Plastid Genome Length:** 152,222 bp
- **Genome Type:** Circular chloroplast genome
- **Source:** NCBI GenBank
- **Genome Record:** https://www.ncbi.nlm.nih.gov/nuccore/PX591265.1

## Software Used

**OGDRAW (OrganellarGenomeDRAW)** was used to generate the circular plastid genome map.

Website: https://chlorobox.mpimp-golm.mpg.de/OGDraw.html

## Methodology

1. Retrieved the annotated GenBank file for *Glycine soja* isolate HAAS216 from NCBI.
2. Checked the organism name, accession number, and genome length.
3. Opened OGDRAW and uploaded the annotated GenBank file.
4. Selected standard map mode, circular genome map type, and plastid as the sequence source.
5. Used automatic detection for the inverted repeat regions.
6. Selected the GC content graph, direction of transcription, and full legend.
7. Generated the genome map and saved the PNG image in the `figures` folder.
8. Examined the map and answered the laboratory questions.

## OGDRAW Settings

The map was generated using the circular plastid map option. Automatic inverted repeat detection was selected. The GC content graph, transcription direction, and full legend were included to help visualize the genome structure and gene organization.

## Main Structural Features Observed

The genome map represents the circular chloroplast genome of *Glycine soja*. Its major structural regions are the Large Single Copy (LSC), Small Single Copy (SSC), and two Inverted Repeat regions (IRa and IRb). The map also displays annotated genes, their transcription directions, and GC content information. These features help show how genes are distributed and how the different regions are organized within the genome.

## Repository Contents

- `data/Glycine_soja_PX591265.1.gb` — Original annotated GenBank file.
- `figures/Glycine_soja_plastid_genome_map.png` — Final OGDRAW genome map.
- `answers/Lab_plastid_genome_answers.md` — Answers to the laboratory questions.
- `README.md` — Project overview, workflow, settings, and observations.

## Reference

Greiner, S., Lehwark, P., and Bock, R. (2019). OrganellarGenomeDRAW (OGDRAW) version 1.3.1: expanded toolkit for the graphical visualization of organellar genomes. *Nucleic Acids Research, 47*, W59–W64.

OGDRAW: https://chlorobox.mpimp-golm.mpg.de/OGDraw.html
