# Insights into the Structure and Dynamic Evolution of Complete Centromeres in Sus scrofa 
Advanced long-read sequencing technologies have revolutionized genome assembly, unlocking research into complex regions such as centromeres and marking the advent of a new era in genomics research. The complete assembly of porcine centromeres has also enabled me to investigate their structural and sequence evolution mechanisms.
Visualization：StainedGlass HICAT NTRprism
HiCAT：output the largest HOR coverage results
-r is HiCAT result directory. e.g. ./HiCAT_out
-s is which similarity be visualized. For example, 0 represents 0.94, 1 represents 0.945 and 2 represents 0.95 in default.
-sp is the number of top HORs. default is 5.
-sn is the minimum repeat number of HOR. default is 10

StainedGlass：Illustrate the degree of sequence similarity within the centromere
A sample/prefix identifier to append to your result files
sample: centromere
fasta: .centromere/CEN.fasta
Size of the window in which to breakup the input fasta before all by all alignment.
window: 5000

NTRprism：Show the size of periodic unit structures
NTRprism_ProcessFasta_v0.22.pl
NTRprism_PlotSpectrum.r
NTRprism_PlotHeatmap.r
also requires r packages ggplot2 and reshape2
