# Fusion-Oviz-demo

Documents of [Fusion-Oviz](https://fusion.oviz.org/), a Platform for Bioinformatics Visualization

# Sequencing

## Heatmap
Linkage heatmap is an useful method to visualize read linkage patterns on SV event, especially in studies with long-range sequencing data, such as 10x linked-reads. We apply the `Heatmap` visualization to display the heatmap matrix based on sequencing reads linkage between two local windowlized regions of SV case. The color depth of each cross-linked window pair is proportional to the number of linkages. Along the chromosome coordinate axis of the heatmap matrix, annotation information is added, such as Ensembl genes. To visualize data, upload a **TXT** file in the *required* format, and then use sidebar options to adjust heatmap color scheme and choose other SVs to display if uploaded data contains multiple cases.

### demo_data
- [10x_resolution80.txt](https://github.com/Nobel-Justin/Oviz-Bio-demo/blob/master/SV_Heatmap/demo_data/10x_resolution80.txt) stores the shared 10x barcodes linkage matrix.
- [pair_end_resolution25_ALK-KIF5B.txt](https://github.com/Nobel-Justin/Oviz-Bio-demo/blob/master/SV_Heatmap/demo_data/pair_end_resolution25_ALK-KIF5B.txt) stores the shared paired-end reads linkage matrix.

## Reads Support
The `Reads Support` visualization is frequently utilized to provide the detail illustration of supporting split reads for given SV events. To visualize data, a **TXT** file in the required format is needed.
### demo_data
[indels.junc.reads.txt](https://github.com/Nobel-Justin/Oviz-Bio-demo/blob/master/SV_Read_Support/demo_data/indels.junc.reads.txt) stores information of supporting split reads for given SV events.

# Structure

## Fusion Genes
the `Fusion Genes` visualization displays the whole structure of chimeric transcript structure.
### demo_data
- Check the official demo input [here](https://github.com/Nobel-Justin/Oviz-Bio-demo/blob/master/Fusion_Genes/demo_data/Fusion_Genes_demo.tsv).

