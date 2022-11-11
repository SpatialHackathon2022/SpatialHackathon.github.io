---
layout: page
title: Home
---
![image](https://user-images.githubusercontent.com/114547/201348988-951367e7-b36e-4c59-9020-2af6f3c45df6.png)

<p align="center">
⬤ <b>12th-16th December 2022</b> ⬤ <b><a href="[https://www.denbi.de/component/chronoforms6/?chronoform=1st_BioHackathon_Germany](https://leucorea.de/)">Leucorea, Lutherstadt Wittenberg, Germany</a></b> ⬤ <b>Hybrid event</b> ⬤
</p>
<p align="center">
  <b><a href="https://www.denbi.de/component/chronoforms6/?chronoform=1st_BioHackathon_Germany">>> Register here <<</a></b>
</p>

### Abstract
Single cell omics has revolutionised the way and the level of resolution by which life science research is conducted, not only impacting our understanding of fundamental cell biology but also providing novel solutions in cutting-edge medical research [[1](https://doi.org/10.1038/nmeth.1315),[2](https://doi.org/10.1038/s41467-020-18158-5)]. More recently, several approaches have been developed to profile spatial single cell gene expression within the tissue context, providing maps of spatial locations and interactions of cell types [[3](https://doi.org/10.1038/s41592-022-01409-2)]. Spatially resolved transcriptomics has been highlighted as an important technology for life science research through being awarded Nature Method of the Year 2020 [[4](https://doi.org/10.1038/s41592-020-01033-y)]. Despite being in the limelight for 2 years, guidelines and workflows for best practices for the analysis of imaging-based spatially resolved transcriptomics data are somewhat lacking. 
 
### Project focus
This project aims to combine the expertise of both biologically and technically focused researcheres to establish benchmarking datasets, comparing performance segmentation and cell assignment tools, and evaluating results in light of tissue specific challenges. A key foundation of the hackathon will be comparing spatial data to matched single cell data in the context of the ongoing *TXsim* project at the Helmholtz Centre Munich (Louis Kummerle, Malte Leucken and Fabian Theis). For the hackathon we will collate dataset of imaging-based spatial transcriptomics (e.g. Xenium/ISS, Vizgen/MERFISH, Resolve/MolecularCartography, seqFISH, EEL, etc) for a number of different organs (brain, lung, liver, heart) from both mouse and human to get things started. 

![image](https://user-images.githubusercontent.com/114547/201365771-dae41d4d-8706-46b8-9de5-14ebd084b444.png)

Our primary focus areas for this workshop are:

* <b>Data</b>. Identification and collation of <b>datasets for benchmarking</b>. Some key datasets will be collated and ready to use for the start of the hackathon, but we hope to expand this to include other relevant technologies and biological systems, especially with a focus on evaluating the quality of cell segmentation.

* <b>QC</b>.Identification of key quality control metrics. We hope to establish clear definitions of key parameters for defining the quality and comparability of experiments such as number of UMI/molecules detected, off-target rate, consistency with prior knowledge from scRNAseq, noisy signals, sensitivity, etc.

* <b>Cell segmentation</b>. Cells exhibit a diversity of morphologies, and the standard approach of segmenting cell nuclei/DAPI signal and expansion to model the cytoplasm doesnt always work, e.g. not all cells are uniformly round.
 
* <b>Normalisation and cell type annotation</b>. Annotation of cell types in spatial data is still in it’s infancy, but there are some interesting paradigms emerging [e.g. [5](https://doi.org/10.1038/s41592-020-01018-x)]. 

* <b>Evaluation</b>. results in light of experimental and tissue based consideration such as single-nuc vs single-cell RNAseq, cell density, tissue complexity, rare cells, non-uniformly shaped cells etc


<details>
  <summary><b>References</b></summary>
  
 [1] Tang et al (2009). “mRNA-Seq whole-transcriptome analysis of a single cell”. Nature Methods.  https://doi.org/10.1038/nmeth.1315<br>
 [2] Aldridge & Teichmann (2021). “Single cell transcriptomics comes of age”. Nature Methods. https://doi.org/10.1038/s41467-020-18158-5<br>
 [3] Moses & Pachter (2022). “Museum of spatial transcriptomics”. Nature Methods.  https://doi.org/10.1038/s41592-022-01409-2<br>
 [4] Marx (2021). “Method of the Year 2020: spatially resolved transcriptomics”. Nature Methods.  https://doi.org/10.1038/s41592-020-01033-y<br>
 [5] Stringer et al (2021). “Cellpose: a generalist algorithm for cellular segmentation”. Nature Methods. https://doi.org/10.1038/s41592-020-01018-x<br>

</details><br>

### Community engagement
An important consideration for a successful hackathon would be community engagement. We plan to further enhance outreach to relevant communities including the ELIXIR single cell omics community, SCOG, the CZI SpaceTX consortia, and other key stakeholders in the field of spatial transcriptomics within Germany and internationally. We also plan to reach out to companies (e.g. Resolve Biosciences, 10x Genomics, Vizgen, Rebus, etc) to learn from their experiences and identify key areas that require attention. In line with Open Science principles, we would aim to share our findings with the wider scientific community – by providing good data and access to robust and easy to use tools in an accessible framework, would make life a lot easier for people new to the field. We also hope to wrap up our major findings in white papers and/or contributions to ongoing studies.

### Organisational details

**Organizers**: 
1.	[Naveed Ishaque](mailto:Naveed.ishaque@bih-charite.de), Berlin Institute of Health at the Charité, Germany. Naveed leads a bioinformatics research group with a strong focus on developing and applying computation methods to better understand spatially resolved transcriptomics data.<br>
2.	[Brian Long](mailto:brianl@alleninstitute.org), Allen Institute for Brain Science, USA. Brian is a member of the Imaging Department at the Allen Institute with extensive experience in image and data analysis. He plays a driving role in the CZI funded SpaceTX consortia.<br>
3.	[Louis Kuemmerle](mailto:louis.kuemmerle@helmholtz-muenchen.de). Helmholtz Center Munich, Germany. PhD student in computational biology in the Theis and Erturk lab, with a strong focus on cell segmentation for spatially resolved transcriptomics data.<br>

**Target audience:** PhD/postdoc-level bioinformaticians familiar with spatial omics analysis. We would strongly encourage those with expertise in tissue specific segmentation challenges and/or working experience of analysing spatial/single-cell data sets to apply!

**Dates:** Monday 12th - Friday 16th December 2022

**Location:** [Lutherstadt Wittenberg - Leucorea](https://leucorea.de/) 

**Contact:** for more information email Naveed Ishaque, [naveed.ishaque@bih-charite.de](mailto:naveed.ishaque@bih-charite.de)

**Registration:** registration is free using [this webform](https://www.denbi.de/component/chronoforms6/?chronoform=1st_BioHackathon_Germany) before the deadline of 25.11.22

**Costs:** registration for the BioHackathon is free, however you will have to pay your own travel, food and accommodation expenses. de.NBI / ELIXIR Germany will pay expenses for lunch and drinks in the Leucorea.

**Accomodation:** the event will be taking place in Wittenberg, Germany. for accomodation recommendations, please refer to the [official event website](https://www.denbi.de/de-nbi-events/1454-biohackathon-germany).

### Code of Conduct
The ELIXIR Germany Code of Conduct has been created so all participants at ELIXIR Germany events organized can interact with each other in a respectful and safe environment, and have avenues to turn to in case they believe there has been a breach to this Code of Conduct.
<i>Be excellent to each other.</i>
