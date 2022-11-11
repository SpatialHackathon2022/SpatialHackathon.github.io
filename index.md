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
Single cell omics has revolutionised the way and the level of resolution by which life science research is conducted, not only impacting our understanding of fundamental cell biology but also providing novel solutions in cutting-edge medical research [[1](https://doi.org/10.1038/nmeth.1315),[2](https://doi.org/10.1038/s41467-020-18158-5)]. More recently, several approaches have been developed to profile spatial single cell gene expression within the tissue context, providing maps of spatial locations and interactions of cell types [[3](https://doi.org/10.1038/s41592-022-01409-2)]. Spatially resolved transcriptomics has been highlighted as an important technology for life science research through being awarded Nature Method of the Year 2020 [[4](https://doi.org/10.1038/s41592-020-01033-y)]. Despite being in the limelight for 2 years, guidelines and workflows for best practices for the analysis of spatially resolved transcriptomics data are somewhat lacking. 
 
### Project focus
This project aims to combine the expertise of both biologically and technically focused researches to establish benchmarking datasets, identify highly performant tools and pipelines, and implement reproducible and portable workflows single-molecule/imaging -based spatially resolved transcriptomics (e.g. Xenium/ISS, Vizgen/MERFISH, Resolve/MolecularCartography, seqFISH, etc). There is also potential to focus on in-situ spatial transcriptomics methods where guidelines for data analysis are lacking (e.g. high resolution Stereo-seq [[5](https://doi.org/10.1016/j.cell.2022.04.003)]). Potential focus areas for such a workshop include:

* Identification and collation of <b>datasets for benchmarking</b>. Some key datasets will be collated and ready to use for the start of the hackathon, but we hope to expand this to include other relevant technologies and biological systems, especially with a focus on evaluating the quality of cell segmentation.

* Identification of <b>key quality control metrics</b>. We hope to establish clear definitions of key parameters for defining the quality and comparability of experiments such as number of UMI/molecules detected, off-target rate, consistency with prior knowledge from scRNAseq, noisy signals, sensitivity, etc.

* Defining and implementing key <b>processing guidelines</b> for single molecule spatial transcriptomics:
  * a)	While in-situ capture methods (e.g. Visium) have clearer pre-processing steps, there is no clear standard for single molecule spatial transcriptomics data. We will look into (i) interfacing with output formats from the starfish pipeline [[6](http://github.com/spacetx/starfish)] which is establishing itself as the uniform pre-processing package, as well as standard outputs from companies; (ii) removing artifact signals arising from overlapping tiles after stitching; (iii) removing off target signals.
  * b)	(Semi-)automated cell type assignment. Annotation of cell types in spatial data is still in it’s infancy, but there are some interesting paradigms emerging [e.g. [7](https://doi.org/10.1038/s41592-020-01018-x)]. 
  * c)	Interfacing with downstream analysis frameworks Seurat [[8](https://doi.org/10.1038/nbt.3192)] and Squidpy [[9]( https://doi.org/10.1038/s41592-021-01358-2)].

* <b>Documentation</b> (e.g. RTDs) and dissemination (e.g. workflow hubs, Galaxy)

Our preliminary focus will be on <b> collation of datasets for benchmarking segmentation</b> and <b>(semi-)automated cell type assignment</b>. Keep an eye on our website (https://spatialhackathon.github.io/) for the latest news, or contact Naveed.ishaque@bih-charitde.de for more information.

<details>
  <summary><b>References</b></summary>
  
 [1] Tang et al (2009). “mRNA-Seq whole-transcriptome analysis of a single cell”. Nature Methods.  https://doi.org/10.1038/nmeth.1315<br>
 [2] Aldridge & Teichmann (2021). “Single cell transcriptomics comes of age”. Nature Methods. https://doi.org/10.1038/s41467-020-18158-5<br>
 [3] Moses & Pachter (2022). “Museum of spatial transcriptomics”. Nature Methods.  https://doi.org/10.1038/s41592-022-01409-2<br>
 [4] Marx (2021). “Method of the Year 2020: spatially resolved transcriptomics”. Nature Methods.  https://doi.org/10.1038/s41592-020-01033-y<br>
 [5] Chen et al (2022). “Spatiotemporal transcriptomic atlas of mouse organogenesis using DNA nanoball-patterned arrays”. Cell. https://doi.org/10.1016/j.cell.2022.04.003<br>
 [6] Axelrod et al (2018). “starfish: scalable pipelines for image-based transcriptomics”. GitHub. http://github.com/spacetx/starfish<br>
 [7] Stringer et al (2021). “Cellpose: a generalist algorithm for cellular segmentation”. Nature Methods. https://doi.org/10.1038/s41592-020-01018-x<br>
 [8] Satija et al (2015). “Spatial reconstruction of single-cell gene expression data”. Nature Biotechnology. https://doi.org/10.1038/nbt.3192<br>
 [9] Palla et al (2021). “Squidpy: a scalable framework for spatial omics analysis”. Nature Methods. https://doi.org/10.1038/s41592-021-01358-2<br>

</details><br>

### Community engagement
An important consideration for a successful hackathon would be community engagement. We plan to further enhance outreach to relevant communities including the ELIXIR single cell omics community, SCOG, the CZI SpaceTX consortia, and other key stakeholders in the field of spatial transcriptomics within Germany and internationally. We also plan to reach out to companies (e.g. Resolve Biosciences, 10x Genomics, Vizgen, Rebus, etc) to learn from their experiences and identify key areas that require attention. In line with Open Science principles, we would aim to share our findings with the wider scientific community – by providing good data and access to robust and easy to use tools in an accessible framework, would make life a lot easier for people new to the field. We also hope to wrap up our major findings in white papers and/or contributions to ongoing studies.

### Organisational details

**Organizers**: 
1.	[Naveed Ishaque](mailto:Naveed.ishaque@bih-charite.de), Berlin Institute of Health at the Charité, Germany. Naveed leads a bioinformatics research group with a strong focus on developing and applying computation methods to better understand spatially resolved transcriptomics data.<br>
2.	[Brian Long](mailto:brianl@alleninstitute.org), Allen Institute for Brain Science, USA. Brian is a member of the Imaging Department at the Allen Institute with extensive experience in image and data analysis. He plays a driving role in the CZI funded SpaceTX consortia.<br>
3.	[Louis Kuemmerle](mailto:louis.kuemmerle@helmholtz-muenchen.de). Helmholtz Center Munich, Germany. PhD student in computational biology in the Theis and Erturk lab, with a strong focus on cell segmentation for spatially resolved transcriptomics data.<br>

**Target audience:** PhD/postdoc-level bioinformaticians familiar with spatial omics analysis. We would strongly encourage those with working experience of data sets, analysis pipelines and single cell modelling to apply!

**Dates:** Monday 12th - Friday 16th December 2022

**Location:** [Lutherstadt Wittenberg - Leucorea](https://leucorea.de/) 

**Contact:** for more information email Naveed Ishaque, [naveed.ishaque@bih-charite.de](mailto:naveed.ishaque@bih-charite.de)

**Registration:** registration is free using [this webform](https://www.denbi.de/component/chronoforms6/?chronoform=1st_BioHackathon_Germany) before the deadline of 25.11.22

**Costs:** registration for the BioHackathon is free, however you will have to pay your own travel, food and accommodation expenses. de.NBI / ELIXIR Germany will pay expenses for lunch and drinks in the Leucorea.

**Accomodation:** the event will be taking place in Wittenberg, Germany. for accomodation recommendations, please refer to the [official event website](https://www.denbi.de/de-nbi-events/1454-biohackathon-germany).

### Code of Conduct
The ELIXIR Germany Code of Conduct has been created so all participants at ELIXIR Germany events organized can interact with each other in a respectful and safe environment, and have avenues to turn to in case they believe there has been a breach to this Code of Conduct.
<i>Be excellent to each other.</i>
