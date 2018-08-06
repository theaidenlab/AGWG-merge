# Demo Instructions for the Juicebox Assembly Tools Module

### Overview
Assembly Tools [[1]](https://www.biorxiv.org/content/early/2018/01/28/254797) is a new module in the Juicebox desktop application [[2]](https://www.cell.com/cell-systems/abstract/S2405-4712(15)00054-X) that extends the Juicebox interface for Hi-C data visualization to allow for visualization and interactive refinement of genome assemblies. When assembly errors are found, users can correct them, using a simple point-and-click interface, in a matter of seconds. Both the heatmap and the reference genome are updated in real-time to reflect these changes. The Juicebox Assembly Tools is available as part of the compiled standalone software Juicebox (versions 1.8.8 and higher). The code is open source.

### Code/software availability
The compiled software can be downloaded from https://github.com/theaidenlab/juicebox/wiki/Download. This demo was tested using Juicebox 1.9.0 (Juicebox with Assembly Tools for Mac).

The source code is shared at https://github.com/theaidenlab/Juicebox. The code includes a README listing System requirements, download guide and instruction for use.

For a quick start guide on the Assembly Tools Module, please see [this tutorial video](https://www.youtube.com/watch?v=Nj7RhQZHM18). The tutorial demonstrates how to use Juicebox Assembly Tools in the context of a demo problem (see also the Juicebox Assembly Tools preprint [[1]](https://www.biorxiv.org/content/early/2018/01/28/254797), figure 2 caption and discussion).

The demo data files can be found [here](https://www.dropbox.com/s/13cppe80692oee9/demo.zip?dl=0). The shared *.zip* archive contains two files: *figure_2.hic* and *figure_2.assembly*. The tutorial video covers opening the two demo files in the compiled version of the software, provides operation instructions and displays expected output. The run time for the demo problem is 8 minutes on a “normal” desktop computer. We recommend computers running a Macintosh Operating System.

Juicebox Assembly Tools requires Java. Download Java [here](https://java.com/en/download/).

For a detailed description of how Juicebox Assembly Tools was used in conjunction with Juicer [[3]](https://www.cell.com/fulltext/S2405-4712(16)30219-8) and 3D-DNA [[4]](http://science.sciencemag.org/content/356/6333/92) to process Hi-C data for AaegL5 genome assembly see [README.md](https://github.com/theaidenlab/AGWG-merge/blob/master/README.md) in this GitHub repository (https://github.com/theaidenlab/AGWG-merge).

### Additional information
The software is distributed under MIT License.
See our ["Genome Assembly Cookbook"](http://aidenlab.org/assembly/manual_180322.pdf) for more information about Juicebox Assembly Tools.

### References
1.	Dudchenko, O. et al. The Juicebox Assembly Tools module facilitates *de novo* assembly of mammalian genomes with chromosome-length scaffolds for under $1000. *bioRxiv* 254797 (2018). doi:10.1101/254797.
2.	Durand, N. C. et al. Juicebox Provides a Visualization System for Hi-C Contact Maps with Unlimited Zoom. *Cell Syst.* 3, 99–101 (2016).
3.	Durand, N. C. et al. Juicer Provides a One-Click System for Analyzing Loop-Resolution Hi-C Experiments. *Cell Syst.* 3, 95–98 (2016).
4.	Dudchenko, O. et al. *De novo* assembly of the *Aedes aegypti* genome using Hi-C yields chromosome-length scaffolds. *Science* 356, 92–95 (2017).
