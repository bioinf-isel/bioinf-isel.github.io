---
layout: default
---

<!--- Text can be **bold**, _italic_, or ~~strikethrough~~.

 ([Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.-->

### General presentation

<!---Title: Workshop Metabolism and mathematical models: Two for a tango – 1st Edition-->

<strong>Dates:</strong> November 4-5, 2024

<strong>Location:</strong> This workshop will be held in a virtual way

This workshop, will be on phylogeny and cophylogeny in general, mathematical modelling and algorithms, and on biology/health. The workshop is open to the community in general.

### Keynote lecturers


<img  title="a title" alt="Alt text" src="/assets/img/FranciscoPinto.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
<!--<img  title="a title" alt="Alt text" src="/assets/img/foto.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />-->
   
**<span style="color:#647436">Francisco Pinto, BioISI/FC, University of Lisbon, Portugal.</span>**

**<span style="color:#D34E24">Title: Evolution and regulation of microbial secondary metabolism </span>**<a href="/assets/presentations/FranciscoTalk.pdf">[slides here]</a> <a href="https://youtu.be/AgD8SckVtlE">[presentation online here]</a>
<br clear="left"/>

**<span style="color:#D34E24">Abstract: Microbes have disproportionate impacts on the macroscopic world.</span>** This is in part due to their ability to grow to large populations that collectively secrete massive amounts of secondary metabolites and alter their environment. Yet, the conditions favoring secondary metabolism despite the potential costs for primary metabolism remain unclear. Here we investigated the biosurfactants that the bacterium Pseudomonas aeruginosa makes and secretes to decrease the surface tension of surrounding liquid. Using a combination of genomics, metabolomics, transcriptomics, and mathematical modeling we show that the ability to make surfactants from glycerol varies inconsistently across the phylogenetic tree; instead, lineages that lost this ability are also worse at reducing the oxidative stress of primary metabolism on glycerol. Experiments with different carbon sources support a link with oxidative stress that explains the inconsistent distribution across the P. aeruginosa phylogeny and suggests a general principle: P. aeruginosa lineages produce surfactants if they can reduce the oxidative stress produced by primary metabolism and have excess resources, beyond their primary needs, to afford secondary metabolism. These results add a new layer to the regulation of a secondary metabolite unessential for primary metabolism but important to change physical properties of the environments surrounding bacterial populations.

<img  title="a title" alt="Alt text" src="/assets/img/heather1.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
   
**<span style="color:#647436">Heather Carleton, Enteric Diseases Laboratory Branch DFWED/NCEZID/CDC, US.</span>**
<br clear="left"/>

<img  title="a title" alt="Alt text" src="/assets/img/joe.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
   
**<span style="color:#647436">Joe Wirth,
Enteric Diseases Laboratory Branch DFWED/NCEZID/CDC, US.</span>**

**<span style="color:#D34E24"> Molecular surveillance in public health using phylogenetics </span>**<a href="https://youtu.be/K5mcrLAxoF4">[presentation online here]</a>


<br clear="left"/>

**<span style="color:#D34E24">Abstract:</span>** Whole Genome Sequencing (WGS) technologies have revolutionized how Public Health and Regulatory Agencies respond to foodborne, waterborne, and one-health related surveillance, detection, and response activities. WGS data is comprehensive: antimicrobial resistance, virulence markers, serotype markers, plasmids, and core and accessory genes are all characterized as part of the WGS workflow. Currently, PulseNet USA sequences approximately 65,000 Salmonella, Escherichia, Listeria, Vibrio, Campylobacter, and Shigella isolates and uses these data to detect over 400 potential outbreaks annually. Allele calls from core genome and WGS multi-locus sequence typing (MLST) are used to generate single linkage trees. These trees are evaluated to identify potential outbreaks using a set of epidemiologic and phylogenetic criteria. Other algorithms such as maximum likelihood and Bayesian inference can be used to infer evolutionary relationships and to link the emergence of clades to specific times.

 

<img  title="a title" alt="Alt text" src="/assets/img/Lars1.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
   
**<span style="color:#647436">Lars Arvestad, Stockholm University, Sweden.</span>**

**<span style="color:#D34E24"> Scalable distance-based phylogeny inference using divide-and-conquer</span>**<a href="https://youtu.be/bus0IRoDeiM">[presentation online here]</a>

<br clear="left"/>

**<span style="color:#D34E24">Abstract:</span>** Inferring a phylogenetic tree is a common task in Computational Biology, and the choice of method depends on the analytical objectives and the characteristics of the dataset. Statistical methods are preferred when constructing a phylogenetic tree is the primary goal, due to their reliability, rich model specification options, and ability to evaluate alternative solutions. Distance-based methods are often used as subroutines for other methods because of their ease of use, straightforward implementation, and adequate speed in many applications.

Neighbor-Joining (NJ) has become the most popular distance-based method for several reasons. It is easy to implement, easy to understand, and have proven to be a practical method with good results. However, the appeal of NJ is often overshadowed by its cubic time complexity, making it challenging to use on even medium-sized datasets by modern standards.

We propose a new divide-and-conquer approach, implemented in two algorithms, DNCTREE and
DNCTREE-k. Given a set S of sequences of length L and a distance-estimation method D as input, the algorithms compute an unrooted tree with the elements of S labeling the leaves. The methods partition S into three subproblems using a small set of sequences as guides, and only the distances to these guiding sequences are needed initially. The resulting trees from the subproblems are then connected to form the final tree. Base cases are computed using NJ. The DNCTREE algorithm has Atteson's convergence radius, ensuring correct phylogenies when distance estimation yields accurate results.

<img  title="a title" alt="Alt text" src="/assets/img/laurent.png" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
   
**<span style="color:#647436">Laurent Jacob, LCQB lab of Sorbonne Université, France.</span>**

**<span style="color:#D34E24">Neural networks for likelihood-free inference in evolutionary genomics </span>**<a href="/assets/presentations/LaurentTalk.pdf">[slides here]</a> <a href="https://youtu.be/DdFpRUonjxs">[presentation online here]</a>
<br clear="left"/>

**<span style="color:#D34E24">Abstract:</span>** Statistical inference in evolutionary genomics allows to estimate key
parameters such as phylogenetic trees, diversification rates or
reproductive numbers of pathogens. This inference relies on
probabilistic models that represent how observed homologous sequences
evolved given these parameters of interest. Standard approaches such
as maximum likelihood or Bayesian inference are well-suited to this
problem but require to compute likelihoods, which can become very
costly or impossible under realistic (and typically complex)
probabilistic models. I will present an alternative likelihood-free
approach exploiting samples rather than evaluations of the model. The
methods I will present rely on neural network architecture that are
specifically tailored to account for the symmetries of each inference
problem.

<img  title="a title" alt="Alt text" src="/assets/img/MarianaBraga.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
   
**<span style="color:#647436">Mariana Braga, Swedish University of Agricultural Sciences, Sweden.</span>**

**<span style="color:#D34E24"> Inferring host repertoire evolution</span>**<a href="/assets/presentations/MarianaTalk.pdf">[slides here]</a> <a href="https://youtu.be/oWjbJ2bVNpc">[presentation online here]</a>
<br clear="left"/>

**<span style="color:#D34E24">Abstract:</span>** In this talk I will describe the model for Bayesian inference of host repertoire evolution, give examples of how we have used it to investigate the evolution of species interactions, with a special focus on butterflies and their larval host plants. The talk will include results produced with software that have been available for a couple years, e.g. for reconstruction of network evolution, as well as software that is currently in development. 

<img  title="a title" alt="Alt text" src="/assets/img/Ran.jpeg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
   
**<span style="color:#647436">Ran “RON” Libeskind-Hadas, Claremont McKenna College, US. </span>**

**<span style="color:#D34E24"> Adventures in Cophylogenetics  </span>**
<br clear="left"/>

**<span style="color:#D34E24">Abstract: </span>** This talk will explore the problem of phylogenetic tree reconciliation to provide insights into the evolutionary histories of pairs of linked taxa such as hosts and parasites, hosts and symbionts, and others. We will discuss algorithmic approaches for tree reconciliation, demonstrate them using software tools developed in our research group, and discuss challenges and opportunities for further research in this area. 


<!--- This is a blockquote following a header.
When something is important enough, you do it even if the odds are not in your favor.-->
<br clear="left"/>

    
### Program

In order to cover a larger audience, the workshop will take place in the afternoon, CET time (French time), on both days.


|              | <span style="color:#D34E24"> Monday 4</span>          | <span style="color:#D34E24">Tuesday 5</span> |
|:-------------|:------------------|:----------|
|  <span style="color:#D34E24">14h00 \- 14h10</span>| Introduction to the workshop | Introduction to the second day  |
| <span style="color:#D34E24">14h10 \- 14h40</span> | Talk1: Francisco Pinto  | Talk4: Laurent Jacob |
| <span style="color:#D34E24">14h40 \- 14h55</span> | Questions and discussion on Talk 1     | Questions and discussion on Talk 4   |
| <span style="color:#D34E24">14h55 \- 15h05</span> | Short Break     | Short Break   |
| <span style="color:#D34E24">15h05 \- 15h35</span> | Talk2: Lars Arvestad  | Talk5: Heather Carleton and Joe Wirth  |
| <span style="color:#D34E24">15h35 \- 15h50</span> | Questions and discussion on Talk 2     | Questions and discussion on Talk 5   |
| <span style="color:#D34E24">15h50 \- 16h00</span> | Short break | Short break  |
| <span style="color:#D34E24">16h00 \- 16h30</span> | Discussion 1 | Discussion 2  |
| <span style="color:#D34E24">16h30 \- 17h00</span> | Talk3: Mariana Braga  | Talk6: Ran “RON” Libeskind-Hadas  |
| <span style="color:#D34E24">17h00 \- 17h15</span> | Questions and discussion on Talk 3     | Questions and discussion on Talk 6  |
| <span style="color:#D34E24">17h15 \- 17h30</span> | Final discussion and conclusion of the first day | Final discussion and conclusion of the workshop  |

#### Registration

The registration is free but compulsory. A Zoom link will be sent just before the workshop starts. Registration can be done **[here](https://www.eventbrite.com/e/tree-for-a-tango-workshop-in-phylogeny-and-cophylogeny-1st-edition-tickets-1037790067027?aff=oddtdtcreator)**.

#### Organization
Alexandre Francisco - INESC-ID/IST, University of Lisbon in Portugal.\
Blerina Sinaimeri - Luiss University, Rome, Italy.\
Cátia Vaz – INESC-ID/ISEL, Polytechnic Institute of Lisbon in Portugal.\
Francisco Pinto -  BioISI/FC, University of Lisbon in Portugal.\
João Carriço.\
Marie-France Sagot – INRIA/Université Claude Bernard (Lyon 1).\
Susana Vinga - INESC-ID/IST, University of Lisbon in Portugal.

#### Participants

We will indicate later the total number of participants.

The <a href="https://olissipo.inesc-id.pt/">H2020 Twinning Project Olissipo</a> has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 951970.

<img  title="a title" alt="Alt text" src="/assets/img/Ist.jpg" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
<img  title="a title" alt="Alt text" src="/assets/img/INRIA_CORPO_SANS_SIGNATURE_RVB.png" width="15%" height="15%" style="float: left;  padding-top:15px; padding-right: 10px; " />
<img  title="a title" alt="Alt text" src="/assets/img/logo_ISEL_principal_PNG.png" width="20%" height="20%" style="float: left;  padding-right: 10px; " />
<img  title="a title"  alt="Alt text" src="/assets/img/Ciencias_UL_Azul_H.png" width="20%" height="20%" style="float: left; padding-top:20px; padding-right: 10px; " />
<img  title="a title" alt="Alt text" src="/assets/img/Logoluiss.png" width="15%" height="15%" style="float: left; padding-top:25px; padding-right: 10px; " />
<br clear="left"/>
<img  title="a title" alt="Alt text" src="/assets/img/INESC-ID-logo_01.png" width="20%" height="20%" style="float: left; padding-top:20px; padding-right: 10px; " />
<img  title="a title" alt="Alt text" src="/assets/img/OLISSIPO_logo_v-c03.png" width="20%" height="20%" style="float: left;  padding-top:20px;padding-right: 10px; " />

<img  title="a title" alt="Alt text" src="/assets/img/logolyon.png" width="20%" height="20%" style="float: left;  padding-right: 10px; " />




