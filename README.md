# Identify_Y.pestis
A computational tool for identification of Yersinia pestis detection using nucleotide sequencing data
Identify_Y.pestis is a tool based python that employs a combination of * in silico * the 97 specific tags of Yersinia pestis to rapidly identify * Y.pestis *  isolates using nucleotide sequencing data.
Users do not need to write code.
Users imports the genome of the sample to be tested into the * tryFna * folder, regardless of whether it is assembled or not, and runs the * Identify_Ypestis_from_dir.py * code to complete the analysis.
The analysis results are displayed in the current folder, "Result_dentify_Ypestis.txt". 
The identification result is determined based on whether the specific tags of Yersinia pestis are searched. The more tags are searched, the more reliable the target sample is positive.
The * tryFna * folder contains test data.
