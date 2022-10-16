---
layout: page
title: Home
---

## de.NBI/ELIXIR-Germany 1st BioHackathon: Spatial Transcriptomics

**12-16 December 2022 | Lutherstadt Wittenberg - Leucorea | [Official Announcement](https://www.denbi.de/de-nbi-events/1454-biohackathon-germany)**

**The event will by hybrid - there will be limited in person places, but will do our best to inclusive**

Single cell omics has revolutionised the way and the level of resolution by which life science research is conducted, not only impacting our understanding of fundamental cell biology but also providing novel solutions in cutting-edge medical research [1,2]. More recently, several approaches have been developed to profile spatial single cell gene expression within the tissue context, providing maps of spatial locations and interactions of cell types [3]. Spatially resolved transcriptomics has been highlighted as an important technology for life science research through being awarded Nature Method of the Year 2020 [4]. Despite being in the limelight for 2 years, guidelines and workflows for best practices for the analysis of spatially resolved transcriptomics data are somewhat lacking. 
 
This project aims to combine the expertise of both biologically and technically focused researches to establish benchmarking datasets, identify highly performant tools and pipelines, and implement reproducible and portable workflows for 2 major spatially resolved transcriptomics technologies: in situ capture (e.g. Visium) and single molecule profiling (e.g. Xenium, Vizgen, Resolve). In line with Open Science principles, we would aim to share our findings with the wider scientific community – by providing good data and access to robust and easy to use tools in an accessible framework, would make life a lot easier for people new to the field. We also hope to wrap up our major findings in a paper to be submitted to bioRxiv and perhaps also to an open access peer-reviewed journal.
 
An important consideration for a successful hackathon would be community engagement. We plan to further enhance outreach to relevant communities including the ELIXIR single cell omics community, SCOG, the CZI SpaceTX consortia, and other key stakeholders in the field of spatial transcriptomics within Germany and internationally. We also plan to reach out to companies (e.g. Resolve Biosciences, 10x Genomics, Vizgen, Rebus, etc) to learn from their experiences and identify key areas that require attention.
 
## Provisional program
Combing the spatial transcriptomics domain specific expertise with computational expertise of de.NBI will underpin the success of this proposal. The preliminary modules for such a workshop can include:
1.	Identification and collation of datasets for benchmarking. Some key datasets will be collated and ready to use for the start of the hackathon, but we hope to expand this to include other relevant technologies and biological systems.
2.	Identification of key quality control metrics. We hope to establish clear definitions of key parameters for defining the quality and comparability of experiments such as number of UMI/molecules detected, off-target rate, consistency with prior knowledge from scRNAseq, noisy signals, sensitivity, etc.
3.	Defining and implementing key processing guidelines for single molecule spatial transcriptomics:
1.	Defining analysis pipelines for new high resolution in-situ capture methods  (e.g. Stereo-seq [5])
2.	While in-situ capture methods (e.g. Visium) have clearer pre-processing steps, there is no clear standard for single molecule spatial transcriptomics data. We will look into (i) interfacing with output formats from the starfish [6] pipeline which is establishing itself as the uniform pre-processing package, as well as standard outputs from companies; (ii) removing artifact signals arising from overlapping tiles after stitching; (iii) removing off target signals.
3.	Cell segmentation. We aim to establish environments and workflows for a model zoo for segmentation including e.g. the CellPose [7] tool. Other performant or highly used tools will be identified and included.
4.	Interfacing with downstream analysis frameworks Seurat [8] and Squidpy [9].
4.	Creating a semi-automated data processing workflows/notebooks for in-situ capture methods (e.g. Visium), which have clearer analysis guidelines in place. We will identify the key processing steps and most commonly used tools and establish software environments and workflows where there are lacking
5.	Documentation (e.g. RTDs) and dissemination (e.g. workflow hubs, Galaxy)
 
**References**<br>
[1] Tang et al (2009). “mRNA-Seq whole-transcriptome analysis of a single cell”. Nature Methods.  https://doi.org/10.1038/nmeth.1315<br>
[2] Aldridge & Teichmann (2021). “Single cell transcriptomics comes of age”. Nature Methods. https://doi.org/10.1038/s41467-020-18158-5<br>
[3] Moses & Pachter (2022). “Museum of spatial transcriptomics”. Nature Methods.  https://doi.org/10.1038/s41592-022-01409-2<br>
[4] Marx (2021). “Method of the Year 2020: spatially resolved transcriptomics”. Nature Methods.  https://doi.org/10.1038/s41592-020-01033-y<br>
[5] Chen et al (2022). “Spatiotemporal transcriptomic atlas of mouse organogenesis using DNA nanoball-patterned arrays”. Cell. https://doi.org/10.1016/j.cell.2022.04.003<br>
[6] Axelrod et al (2018). “starfish: scalable pipelines for image-based transcriptomics”. GitHub. http://github.com/spacetx/starfish<br>
[7] Stringer et al (2021). “Cellpose: a generalist algorithm for cellular segmentation”. Nature Methods. https://doi.org/10.1038/s41592-020-01018-x<br>
[8] Satija et al (2015). “Spatial reconstruction of single-cell gene expression data”. Nature Biotechnology. https://doi.org/10.1038/nbt.3192<br>
[9] Palla et al (2021). “Squidpy: a scalable framework for spatial omics analysis”. Nature Methods. https://doi.org/10.1038/s41592-021-01358-2<br>


## Details

**Organizers**: 
1.	[Naveed Ishaque](Naveed.ishaque@bih-charite.de), Berlin Institute of Health at the Charité, Germany. Naveed leads a bioinformatics research group with a strong focus on developing and applying computation methods to better understand spatially resolved transcriptomics data.<br>
2.	[Brian Long](brianl@alleninstitute.org), Allen Institute for Brain Science, USA. Brian is a member of the computational neuroanatomy group at the Allen Institute with extensive experience in image and data analysis. He plays a driving role in the CZI funded SpaceTX consortia.<br>
3.	[Louis Kuemmerle](louis.kuemmerle@helmholtz-muenchen.de). Helmholtz Center Munich, Germany. PhD student in computational biology in the Theis and Erturk lab, with a strong focus on cell segmentation for spatially resolved transcriptomics data.<br>

**Target audience:** PhD/postdoc-level bioinformaticians familiar with spatial omics analysis. We would strongly encourage those with working experience of data sets, analysis pipelines and single cell modelling to apply!

**Dates:** Monday 12th - Friday 16th December 2022

**Location:** Lutherstadt Wittenberg - Leucorea 

**Contact:** for more information email Naveed Ishaque, [naveed.ishaque@bih-charite.de](naveed.ishaque@bih-charite.de)
