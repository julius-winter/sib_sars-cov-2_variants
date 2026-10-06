# Solutions to exercises for SIB SARS-CoV-2 workshop

## Find and download SARS-CoV-2 sequences
1. Reference [https://ncbi.nlm.nih.gov/nuccore/NC_045512.2](https://ncbi.nlm.nih.gov/nuccore/NC_045512.2)
2. Alpha [https://www.ncbi.nlm.nih.gov/nuccore/MZ344997.1](https://www.ncbi.nlm.nih.gov/nuccore/MZ344997.1)
3. Omicron [https://www.ncbi.nlm.nih.gov/nuccore/OL672836.1](https://www.ncbi.nlm.nih.gov/nuccore/OL672836.1)
4. Authors, information about sampling, translations of the genes, etc.
5. Ref.: China, Alpha: United Kingdom, Omicron: Belgium
6. Scroll down to gene S, surface/spike glycoprotein

## Find mutations by aligning sequences
There are 50 nucleotide differences between the reference and the alpha variant.

## What mutations change the translated protein?

| Variant | DNA sequence | Amino acid sequence |
| ----------- | ----------- | ----------- |
| Reference | CAA TCA TAT GGT TTC CAA CCC ACT AAT GGT GTT GGT TAC | QSYGFQPTNGVGY |
| Alpha | CAA TCA TAT GGT TTC CAA CCC ACT TAT GGT GTT GGT TAC | QSYGFQPTYGVGY |
| Omicron | CGA TCA TAT AGT TTC CGA CCC ACT TAT GGT GTT GGT CAC | RSYSFRPTYGVGH |

1. All of them
2. GTX any of these will be Valine

## Let's have a closer look at the Spike protein
1. You can find the input in solution/spike_alignment_input.txt
2. 5
3. 39

## Nextclade, a tool that does it all
[https://www.ncbi.nlm.nih.gov/nuccore/OZ511251.1](https://www.ncbi.nlm.nih.gov/nuccore/OZ511251.1) XFG.3, 146 mutations