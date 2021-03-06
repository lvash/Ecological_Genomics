# Ecological Genomics Spring 2017    

## Author: Lauren Ash      

## Overall Description of notebook      

This is my online notebook for the Ecological Genomics course. I will update with new techniques I learn, questions that I come up with, and general notes. 


## Date started: 2017-01-19 
## Date end: 2017-05-08       

## Philosophy   
Science should be reproducible and one of the best ways to achieve this is by logging research activities in a notebook. Because science/biology has increasingly become computational, it is easier to document computational projects in an electronic form, which can be shared online through Github.

### Helpful Resources   
[Andrew's Ecological Genomics Webpage](https://adnguyen.github.io/2017_Ecological_Genomics/)   
[Unix Cheat Sheet](https://files.fosswire.com/2007/08/fwunixref.pdf)   
[RNA-seq exercise RMD](./RNASeqPowerActivity.Rmd)        





<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


### Table of contents for 60 entries         
* [Page 1: 2017-01-19](#id-section1). First journal article: Ellegren 2014 
* [Page 2: 2017-01-23](#id-section2). Class notes [MISSED]
* [Page 3: 2017-01-24](#id-section3). Articles: Rockman 2012 and Lee et al. 2014
* [Page 4: 2017-01-25](#id-section4). Class notes [QTNs and SSWD info] 
* [Page 5: 2017-01-30](#id-section5). Choosing SSWD questions
* [Page 6: 2017-02-01](#id-section6). Info Update Blitz
* [Page 7: 2017-02-01](#id-section7). Unix Tutorial and Tips
* [Page 8: 2017-02-03](#id-section8). Article: Dunning et al. 2014
* [Page 9: 2017-02-06](#id-section9). Info update for RNA seq and article discussion
* [Page 10: 2017-02-06](#id-section10). RNA-seq Coding
* [Page 11: 2017-02-08](#id-section11). Transcriptomics info update
* [Page 12: 2017-02-10](#id-section12). Prepping for Todd et al. info update    
* [Page 13: 2017-02-15](#id-section13)  SNPs and Population Genomics Info Update
* [Page 14: 2017-02-15](#id-section14). Article discussion: Zhao et al. 2016
* [Page 15: 2017-02-15](#id-section15). Sequence alignment (SAM) files and Read Count Extraction
* [Page 16: 2017-02-22](#id-section16). DESeq2 in R
* [Page 17: 2017-02-27](#id-section17). Edwards paper
* [Page 18: 2017-03-01](#id-section18). Homework Assignment info and WGCNA
* [Page 19: 2017-03-06](#id-section19). Population Genomics: Steve's Info Update and Alex's Discussion
* [Page 20: 2017-03-06](#id-section20). Population Genomics Tutorial
* [Page 21: 2017-03-07](#id-section21). **Homework 2: RNA sequencing for gene expression analyses**
* [Page 22: 2017-03-08](#id-section22). Effective Population Size and Substitution Rate Info Update
* [Page 23: 2017-03-08](#id-section23). Population Genomics Part 2 Tutorial
* [Page 24: 2017-03-20](#id-section24). Bill Kilpatrick's Info Update
* [Page 25: 2017-03-20](#id-section25). Population Genomics Part 3 Tutorial
* [Page 26: 2017-03-22](#id-section26). Population Genomics Part 4 (Finishing heterozygosity estimates and PCA)
* [Page 27: 2017-03-27](#id-section27). Selective sweep info update (Allison)
* [Page 28: 2017-03-29](#id-section28). Detecting local adaptation info update (Lauren Ashlock)
* [Page 29: 2017-04-03](#id-section29). Karl Fetter Guest Lecture: Fst; outliers
* [Page 30: 2017-04-04](#id-section30). **Homework 3: Population genomic diversity and structure**
* [Page 31: 2017-04-05](#id-section31). Melissa's Info update: Annotation/Enrichment
* [Page 32: 2017-04-05](#id-section32). Gene Annotation Tutorial
* [Page 33: 2017-04-08](#id-section33). Paper Discussion prep: "Bacterial community dynamics are linked to patterns of coral heat tolerance"
* [Page 34: 2017-04-08](#id-section34). Microbiome: Steve's info update and Melanie's coding session
* [Page 35: 2017-04-12](#id-section35). Host genetic associations with the microbiome  
* [Page 36: 2017-04-19](#id-section36). Alex's Info Update
* [Page 37: 2017-05-08](#id-section37). **Final Project R Code**
* [Page 38:](#id-section38).
* [Page 39:](#id-section39).
* [Page 40:](#id-section40).
* [Page 41:](#id-section41).
* [Page 42:](#id-section42).
* [Page 43:](#id-section43).
* [Page 44:](#id-section44).
* [Page 45:](#id-section45).
* [Page 46:](#id-section46).
* [Page 47:](#id-section47).
* [Page 48:](#id-section48).
* [Page 49:](#id-section49).
* [Page 50:](#id-section50).
* [Page 51:](#id-section51).
* [Page 52:](#id-section52).
* [Page 53:](#id-section53).
* [Page 54:](#id-section54).
* [Page 55:](#id-section55).
* [Page 56:](#id-section56).
* [Page 57:](#id-section57).
* [Page 58:](#id-section58).
* [Page 59:](#id-section59).
* [Page 60:](#id-section60).  

------   
<div id='id-section1'/>  

### Page 1: 2017-01-19. First journal article: Ellegren 2014

Here are [Andrew's thoughts](https://github.com/adnguyen/2017_Ecological_Genomics/blob/master/ANBE_notebook.md#page-2-2017-01-20-readings-for-2017-01-25-monday) on the paper "Genome sequencing and population genomics in non-model organisms" (under the heading **Now paper notes:**).   

### My thoughts while reading the paper

The paper has a glossary of terms and I wanted to write a few down:

**Effective population size (N<sub>e</sub>):** a measure of the size of an idealized population in which the effect of genetic drift on allele frequencies is similar to the population under consideration.   

**Genetic architecture:** the genetic background to phenotypic traits, including their number, effect sizes,and dominance.   

**Genome-wide association studies (GWAS):** studies based on the use of large numbers of SNP markers genotyped in a group showing a particular trait, and in a control group, with the aim of finding association between trait and markers.   

**Scaled selection coefficient:** the selection coefficient (*s*, the relative fitness dis-/advantage of a derived allele) multiplied with N<sub>e</sub>, to take into account the fact that the efficiency of selection is directly proportional to population size. 

**Transcriptome:** the complete repertoire of transcribed sequences in the genome, including expression of both from protein-coding genes and from noncoding RNAs.   

Some parts that stood out to me:  

* **Adaptive evolution** should be more common in those regions of the genome experiencing high rates of recombination.   
* **GC-biased gene conversion** is a process in which C and G nucleotides have a higher probability of being the donor -> genomic regions with high recombination rates should evolve towards a high GC content -> explains heterogeneous landscape of base composition   
* Not fully explored: biased gene conversion has potential to reduce efficacy of purifying selection in high recombination regions by aggravating the removal of deleterious AT/CG mutations.   
* Being able to quantify the proportion of the genome evolving under purifying selection is important (identifying conserved sequences) * There is a debate about what contributes to the 'functionality' of the genome (transcribed sequence, histone modification, open chromain indicative of function vs only proven purifying selection)
* When **scaled selection coefficents** are higher, one might expect to see larger fractions of the genome conserved   
* Having genome access, we can conclude gene duplication and neofunctionalization represent common mechanisms for formation of new phenotypes and thereby a seedbed for adaptation.   
* Adaptive evolution can be estimated by comparing the rate of nucleotide substitutions (likely to have functional consequences) vs presumably neutral substitutions, but it is hard to estimate in small populations.   
* **Population genomics:** the use of sequence or genotype data from multiple, although individually analyzed, loci spread across the genome; scales up inference power AND offers a means to study the genomic landscape and variance of allelic diversity within and between populations.   
  + Typical pipeline:   
    1. Design of sequencing strategy (# of individuals per population; # of populations; etc)    
    2. Generation of sequence data   
    3. Mapping of sequence reads to the assembly   
    4. Variant calling (genotyping)   
    5. Downstream population genetic or molecular evolutionary analyses  
* **Trait mapping** example: resequenced pigeon genomes with and without a head crest phenotype and identified a particular allelic variant present in the crested breeds, absent in the others.   
* Regions with low diversity within populations are indicative of recent selective sweeps and regions with high divergence between populations point to diversifying selection and limited gene exchange

**Overall messages:**  
* Having access to genomes is letting us infer evolutionary processes affecting sequence evolution from the whole-genome perspective instead of a random sample of loci.   
* The technology is rapidly evolving (next generation sequencing is no longer a fitting name)
* Population genomics is becoming a venue for the identification of genes/genomic regions involved in fitness-related traits and speciation.   

**How can I apply to my research?** Trait mapping? Could compare genomes of asymptomatic and symptomatic ranavirus-infected individuals and seeing if there are allelic variants


------   
<div id='id-section2'/>  

### Page 2: 2017-01-23 Course notes [MISSED]

Andrew posted notes of the class and Melissa's info update that I missed [here](https://github.com/adnguyen/2017_Ecological_Genomics/blob/master/ANBE_notebook.md#page-3-2017-01-23-day-2-course-notes).   

Info I looked up after reading Andrew's notes:   

Sanger sequencing: "The first method of sequencing the genetic code was devised by Fred Sanger. To sequence the DNA, it must first be separated into two strands. The strand to be sequenced is copied using chemically altered bases. These altered bases cause the copying process to stop each time one particular letter is incorporated into the growing DNA chain. This process is carried out for all four bases, and then the fragments are put together like a jigsaw to reveal the sequence of the original piece of DNA." [Reference](https://www.dnalc.org/view/15479-Sanger-method-of-DNA-sequencing-3D-animation-with-narration.html)   

Illumina: Illumina next-generation sequencing utilizes a fundamentally different approach from the classic Sanger chain-termination method. It leverages sequencing by synthesis (SBS) technology – tracking the addition of labeled nucleotides as the DNA chain is copied – in a massively parallel fashion. [Reference](https://www.illumina.com/technology/next-generation-sequencing.html)      

------ <div id='id-section3'/>

### Page 3: 2017-01-24 Articles: Rockman 2012 and Lee et al. 2014

### Lee et al. 2014: Identifying the genes underlying quantitative traits: a rationale for the QTN programme   

**QTN: quantitative trait nucleotide**      
* Goal = identifying the genes or nucleotide variants underlying quantitative and adaptive traits   
* Criticisms   
  + QTN programme has asserted that finding the genes and nucleotides for adaptive/quant. traits is a goal without explaining why it is a goal   
  + Logical flaws in how results are interpreted (i.e. overestimating phenotypic consequences; biased picture of importance)   
  + Holds little value: focuses on patterns instead of evolutionary processes
* Exciting: adaptive phenotypes can be understood as a collection of single-nucleotide polymorphisms (SNPs)   

**Rationale for QTN**   
* Vertical integration   
  + Understanding the evolution of adaptation from genetic variation at causal nucleotides to -> heritablity in natural populations -> strength of contemporary selection -> how patterns of genetic variation and selection depend on geography/ecological context
  + Suprising in the lack of complete vertical integration examples   
  + Example: Hopkins and Rauscher 2011 - found nucleotide diversity patterns indicative of recent, strong natural selection and investigated how pollinators affect intensity/color of flowers   
  + Few examples exist where selection on QTN for truly quantitative traits has been demonstrated (focus on qualitative like pink vs red flowers)   
* Genetic parallelism and pleitropy   
  + QTN research can reveal underlying mechanisms of convergent phenotypic evolution across related organismal groups   
  + Only way to directly test for the extension of convergence down to the nucleotide level   
  + Production of common phenotype can imply either i) there are developmental/structural constraints on the production of the trait or ii) repeated changes are favored because they have fewer deleterious pleiotropic side-effects relative to others
* Maintenance of standing genetic variation    
  + Why is there such an abundance of heritable variation in nature?   
  + Mutation-selection balance: equilibrium between mutation introducing deleterious variation and purifying selection depleting it; variants are mostly rare, recessive alleles   
  + Balancing selection hypothesis: negative and positive selection acting on same site for different components of a trait; result in maintenance of both alleles and predicts polymorphisms at intermediate frequencies   
  + QTN programme can examine how selection acts on standing variation, thereby connecting theory, quantitative genetics, and population genetics.
* Role of standing genetic variation in the wild    
  + Evolutionary responses to selection will differ greatly depending on whether the 'substrate of adaptation' comes from new mutations or standing variance   
  + Adaptation from new mutation is accompanied by the signature of a 'hard sweep' (steep decline in nucleotide diversity around a fixed site; excess of rare alleles close to selected site)   
  + Adaptation from standing variance is accompanied by the signature of a 'soft sweep' (lesser decline in diversity and associated with intermediate-frequency alleles)   
* Understanding the role of genomic architecture in adaptation   
  + QTN programme can clarify the role of aspects of genomic architecture (chromosomal inversions, translocations, 'supergenes' in areas of suppressed/restricted recombination) in adaptation   
  + Can clarify genetic basis and evolutionary forces responsible for polymorphisms (i.e. that directly influence plant mating and fitness)   
  + Necessary for evaluating role of genomic architecture in studies on role of chromosomal inversions in local adaptation, which could 'capture' locally advantageous haplotypes and spread quite rapidly  
  + Ex: monkeyflower - could estimate the relative contribution of inversion to reproductive isolation between the two ecotypes   

  **Take away:** We should refocus and redouble our efforts to gain insight into the evolutionary process, use effective genetic data, and test evolutionary hypotheses

**How can this relate to my research?** Could look at different virus strains? Try to relate nucleotides to adaptation in virulence?   

### Rockman 2012: The QTN Program and the alleles that matter for evolution: all that's gold does not glitter  

The problem: For the QTN program to succeed, the allelic variants it discovers must be representative examples of the underlying pool; this condition is rarely met. Current catalog of QTNs represents a biased sample of evolutionary causes and molecular functions.   

Rockman outlines 5 critiques of the QTN Program:  
* Known Causal Variants are Not Typical QTNs   
   + Our QTN successes have only sampled the most extreme outliers in the geometic model's distribution's tail   
   + Not very informative   
* The LOD that Failed: QTLs are Uninformative   
   + Does not address question of relative importance of major vs minor genes in evolution   
   + We have a bias in studying dramatic traits with discrete differences between populations/species   
   + The null hypothesis for most QTL mapping is the absence of QTL, not abundance of infinitesimal QTLs
* Theory does not Require a Preponderance of Large-Effect QTNs   
   Three contexts in which theoretical expectation of large-effect QTNs does not apply:    
   1. adaptation to a moving optimum (small mutational steps predominate rather than large steps)   
      2. adaptation from standing variation (new models focus on new-mutation models)   
      3. nonadaptive evolution (adaptive fixation is not whole of natural selection; there are questions that can't be addressed with geometric model of adaptive fixation)   
* Fisher Redivivus: Unbiased QTNs are Often Small-Effect Polygenes  
   + Genetics of genome-wide gene expression - it's complex!    
   + Genome-wide association studies - incapable of pinpointing causal variants   
   + Genomic selection in agriculture - allows every marker to have an effect on the trait; works as well as weighting?     
   + Population studies of weak selection - large fraction of all segregating variants have fitness consequences, even if magnitudes are too small for selection to detect in typical populations     
* There is a Relationship Between Phenotypic Effect Size and Molecular Function   
   + The population holds an enormous store of common small-effect QTNs whose molecular function is disproportionately noncoding   

**The Future**
* Large-effect QTNs that are amenable to discovery are informative about the genetics of evolution
* We need to develop more meaningful classifications of biological contexts   
* We could devote resources to the discovery of QTNs of smaller and smaller effect    

**How can I apply to my research?** Don't look for nucleotide variants 'just because.' Come up with a compelling reason to do so and how the results can relate to the broader picture of evolution and the virus.

### Small group discussion of Rockman 2012:   
- Most effect sizes are small - we are not getting a good representation   
- Small effect alleles are most likely not operating the same way large effect alleles
- Are these methods identifying interactions between locis? NO!   
- Should relate to broader picture/question   

### Debate of Rockman 2012 and Lee et al. 2014:   
* Lee et al. 2014
  + Hoping to see bigger picture of how genetic processes interact with larger scale processes   
  + Should collect data now and generate questions later?   
  + Ask you question and apply appropriate tool

Is it worth 4 years of PhD research?    

**Theme:** It depends on your question, use tools to answer it; perhaps broad sweeps aren't very informative.

If comparing resistance versus susceptibility in populations: which populations would benefit from connectivity (looking at gene flow; could be conservation aspect)? Are certain QTNs related to resistance with a particular genetic background? How repeatable and transferable is the evolutionary process?   


------ <div id='id-section4'/>

### Page 4: 2017-01-25 Class notes [QTNs and SSWD info]   

[Handout and Notes Page 1](https://cloud.githubusercontent.com/assets/15003012/22557682/3f9c49ac-e939-11e6-851f-628492b6a93d.jpg)   
[Handout and Notes Page 2](https://cloud.githubusercontent.com/assets/15003012/22557681/3f92678e-e939-11e6-8651-c6f9ee686310.jpg)   

Things to do:   
**Pick an info update paper and discussion paper by Monday**   
Sign up to audit the class   
​    
Info Update Outline:   

1) What are QTNs?   
2) Quantitative Genetic Theory of Adaptive Traits   
* V<sub>A</sub>   
* h<sup>2</sup>   
  3) Methods   
* Linkage maps   
* GWAS   
* Selection scans   

QTN = quantitative trait nucleotides   

adaptive trait examples:   
flowering time (continuous/quantitative traits, could be graphed as normal distribution with flowering time on x axis and frequency on y axis)    
flower color (discrete/Mendelian, could be graphed with bars)   
thermal tolerance, venom potency, defense compounds, toxin tolerance, drought tolerance, altitude tolerance (hypoxia)
```
trait 
	   |       /
	   |     /   } alpha <- QTN
	   |   / }    "average effect"
	   |_/_________
	   AA  Aa  aa
	   p2  2pq q2
```
V<sub>A</sub> (additive variance)
h<sup>2</sup> = V<sub>A</sub>/V<sub>p</sub>   

more efficient to have many small mutations than large because large can push populations to their extremes (reference handout for drawing)   

Methods to determine how alleles affect traits:   



### Sea Star Wasting Disease  

* Affecting dozens of species   
* Some are more resistant, some are vulnerable   
* Hours to days until loss of turgor, lesions, arms are falling off, insides explode, goo           
* The pathogen is unknown: no viral load studies   
* First report in 2012, intensified in 2013, really bad 2014 (never as severe/widely distributed as then), less severe now  
* Densovirus (DNA virus) implicated; could be opportunistic after host is sick 
* Previous outbreaks in 1970s in Monterey Bay and Baja, CA area and Densovirus present in museum specimens  
* Goop is byproduct of being sick and inability to enact collagen   
* Seems more prevalent intertidally than subtidally because colder water/less stress in subtidal areas   
* [Link to map](http://data.piscoweb.org/marine1/seastardisease.html) - blue dots are not currently observed   

**Actual study:**    
* *Pisaster ochraceus* is the subject of this study: found from Alaska to Baja
* Took sick sea star, chopped it up and put it in the water with healthy, did a time course - not this study?   
* Came healthy, developed disease on their own   
* Maintained in individual aquaria   
* Collected from two sites: intertidal and subtidal around Monterey (super diverse between/within populations)     
* MM abbrevation: fluctuated between sick and healthy   
* Sampling   
  + Epidermal biopsy   
  + Extracted total RNA   
  + Poly-A tail selection for mRNA   
  + Sequenced on 5 Illumina HiSeq lanes   
  + Amplified out ribosomal 16S for all microbes   
  + 16S data and images for all 93 samples and 'holes' in data table   
* Which individuals or days to subset for question?   

Questions:   
* Does genetic diversity/variance relate to becoming sick?      
* Resistance genes for those that stayed healthy and went from sick to healthy   
* Intertidal versus subtidal: genetic differences (local adaptation) or gene expression?    
* Just within intertidal healthy versus sick genetic differences   
* All individuals died versus stayed alive: genetic differences/gene expression?   
* Heritability of microbiome (day as replicate)      
* Microbiome through time   
* Immune related genes (reverse pathology); specific classes of genes; respond if there is a virus present   



------ <div id='id-section5'/>

### Page 5: 2017-01-30 Choosing SSWD questions   

[Sea Star Wasting Disease Data](https://cloud.githubusercontent.com/assets/15003012/22557818/a82b9f0e-e939-11e6-9862-db46aa909de8.jpg)   

More info on study:   
* single-stranded DNA virus (sequenced RNA to obtain active not just present particles)   
* collected from same site but intertidal vs subtidal   
* more stressful collecting at intertidal because they are exposed and need to be 'ripped off' rock - influence symptoms?      
* had positive control for densovirus, did not amplify for qPCR   
* epidermal biopsy (biome is from outside, top of sea star, not gut)   

## Immune-related gene expression
* Design: break up between healthy versus sick (exclude MM? look at gene expression through time?)   
* Subset: two points in time (first, last or healthy, very sick), all sick versus all healthy   
  + Steve thinks polarizing may be best method to subset (first and last)   
* Reverse pathology: looking at different immune pathways   
* Is difference in expression more than what we would expect at random? Have random matched genes   
  + Normalize: over total amount of reads   

Info: Jonathan Rast - sea urchin immunity   
Design: Break them up according to transition; may be different for individuals   
Healthy->Healthy   
analysis: repeated measure ANOVA; survival analysis: which variables predict susceptibilty/death? gene expression/ microbiome?   
Three groups: HH, HS, SS (5 each, 15 individuals, 2 time steps)    

Questions:
* Can we tell anything about the pathogen identity based on gene expression of known immune-related genes?  
  + What is immune response of this species of starfish?    
  + Is expression of immune-related genes different between two species of starfish?   
  + Difference in immune response between densovirus positive and negative individuals      
  + Compare microbiome in individuals that show immune response versus those that don't; before/after sick      

Justification for 'control' of background gene comparison: transcriptome wide changes among the three groups - to be certain that only immune genes are different, we want to compare to background random genes

**Intertidal versus subtidal group:**  
* Focus on differences in gene expression between two groups and community structure (# of species versus one taxa) in microbiome   
* Identifying difference in stress response versus immune response: broad survey first
* Day 3 first to pick up stronger environment signature   

**Temporal variation**   
* Which genes are expressed through time?   
* Account for variation of when individuals got sick   

**Intertidal** 
* Assess genomic difference using SNPs with individuals that stayed healthy (n=3)   
* Compare basic genomes of healthy vs sick   
* Compare healthy subtidals and see if there are no differences, include in healthy group    
* Looking at microbiome at end and maybe through time   

### Potential Analyses:    
* crude subtraction    
* Fst approach   
* PCA/discriminate analysis   


## Next Steps:    
* As a group, write a one-page proposal following hand-out for essential information    
* List exact sample names      
* Due Monday February 8 (one per group)   
* MS Word, email to Steve and Melissa   

This Wednesday: Library prep types blitz to learn about how libraries are made and different types of data they produce; whole genome, RAD Seq, Amplicon sequences, GBS (no person has signed up)   
GBS: restriction enzymes - reduce representation across genome so you can focus sequencing efforts; pop gen differences   


------ <div id='id-section6'/>

### Page 6: 2017-02-01 Info Update Blitz

**Whole Genome Sequencing**   
* Applications: 
  + Population genetics (genetic relatedness, admixture events)   
  + Conservation (monitoring, controlled breeding)   
  + Screen for variation and adaption potential  
  + Understand inbreeding potential; impacts of genetic variation; plastic responses to the environment   
  + Benefits: High power, high resolution   
* Prior Considerations   
  + Potentially need a reference genome   
    + No:   
      + De novo assembly
      + Adaptations   
      + Gene expression (can be addressed without reference genome)   
    + Yes: Select important variation   
      + Epigenetic modifications   
      + DNA to protein process   
      + Gene expression studies can benefit from reference genome    
  + Need: money and computational resources (>1 T; work with a server, using command line and programming language)   
  + Limitations:  
    + Polymorphic genes and paraloges - core genes that are highly conserved; difficult to assemble genome   
    + Rapidly evolving genes and large gene families - have poor representation in genome      
    + Using 1 individual: does that sequence represent the genome of that species?   
    + Pool samples: there will be individual variation that can affect sequence  
    + Impossible to sequence all nucleotides: heterochromatic regions (in centromeres, telomeres, around histones - sometimes can't be reached) and highly repetitive regions (can't figure out where it should go)   
  + Sequencing platforms   
    + Short reads: Illumina sequencing (150bp); SOLiD (50bp)   
    + Long reads: Pacific Biosciences (5 kilobites); Ion Torrent (~500 bps); Illumina Moleculo (up to 10 Kb)   
  + Knowledge on organism   
    + Genome size (can estimate with a few methods; K-mer approach: short, unique element of DNA sequence of length K)   
    + Repeat content  
    + Sequence error rates (of platform)   
    + Degree of genome duplications (polyploidy)   
* Methods   
  + Wet lab   
    + Tissue   
      + High quality DNA: 
        + Avoid energetically active tissue (muscle) because it has high content of mitochondrial DNA which can affect depth read)   
        + Avoid gut and skin
      + Quantity: 1mg to around ~6ug (short reads)   
      + GC content, duplicates and repeat abundance (trim)  
  + Library Prep   
    + Assemble into contigs with shotgun sequencing
      + Single end reads that go in any direction in relation to genome sequence   
      + Paired end reads that are put together by overlap  
      + Mate pair are pairs that are far away (can assemble scaffold)     
  + Quality control: statistics like N50 (the length (# bp in 'middle' contig) of the 50% of assembled genome ~median statistic); error detection account for misorientation (Reaper); foreign DNA (BLAST)   
  + Annotatation can help determine what the different genes would code for if you have info of related organism (could be done automated with software and manually)   
  + Publish! Can find on NCBI   

**RNA-seq**   
Advantage    
* Can get differention of genome expression between diff populations, between diff treatments   
* Allele specific expression (from environmental response or adaptation)   
* Functionally relevant subset of the genome   

| RNA seq                        |               Micro array                |
| ------------------------------ | :--------------------------------------: |
| Wide range of expression value |                   N/A                    |
| N/A                            | Saturation of analog-type (flourescent) signal |
| Info on splicing events        |                    ??                    |

Limitation: post transcriptional modifications can't be captured with RNA seq   

**Work flow**   
Experimental setup -> Tissue prep + Library -> High thorough put sequencing -> Transcriptome reconstruction -> Alignment of reads -> read quantificaton and Marker development -> Biological inference   

Purpose (before you start RNA sequencing): 
1. Proof coding or regulatory non-coding?   
2. Reference Genome?   
3. Alternative splicing?   
4. Technology?   
5. Population or specific treatments?   

Work flow   
* Set up  
  + Biological replication is very important   
  + Choice of tissue (which time are you taking the tissue? Different life stage; pool small organisms)  
* Wet lab   
  + RNA extraction   
    + RNA prone to contamination so RNase free environment   
    + Treat with DNase (DNA/RNA hybrids?)  
    + Get rid of rRNAs   
    + Enrich mRNA with poly-A tails    
  + cDNA   
    + Use oligodT primers to get reverse transcriptase and forms cDNA   
  + Library   
    + Single end   
    + Paired end
* Seq strategy    
  + Pyrosequencing by Roche, Ion Torrent: incorrect homopolymers -> can affect gene expression profile      
  + GA/Hiseq by Illumina: easily affected by GC content -> can affect gene expression profile   
  + Sequence coverage: >100 million bp - 10 million bp    
  + Programming -> Unix, Python, R   
  + Seq strategy: de novo approach if no reference genome; assembly approach (reconstruction -> splice junction -> map/align the reads -> Library   
* Bio-info   - will cover next week   
* Statistical measures  - will cover next week    

**Amplicon Sequencing**   
​    
[Amplicon Sequencing Handout](https://cloud.githubusercontent.com/assets/15003012/22557684/3fa71800-e939-11e6-816d-1e5645c57828.jpg)    
​    
Glossary:   
* Amplicon sequencing: targeted approach for analyzing genetic varation in **specific genomic regions**   
* Amplicon: Targeted gene (region) to be amplified via PCR w/specific primers    

**Methods**    
* Library Prep   
* Sequencing   
* Data Analysis   

**Extract**   
->   
**PCR (1st)**   
* Amplify gene (200-600bp with variable and conserved regions)   
* Specific primers   
  ->   
  **Clean (PCR purify)**   
* Run a gel; extract amplicon from gel   
* Put through column    
  ->   
  **Sequence**   
* Send to facility   
* Or another PCR (2nd)     
  + Barcodes   
  + Adaptors  
    ->   
    **Clean**   
    ->   
    **Pool**   
    ->   
    **Sequence**   
* 454 sequencing is out of date      
* MiSeq (Illumina); paired end sequencing    
* [Library prep video](https://www.youtube.com/watch?v=_yC0Bzw3WbQ) on handout   

**Data Analysis**   
1. Trim some bp off ends    
2. Align (use conserved areas)   
* Sometimes have to manually align    

**Applications**   
* If you know what you are looking for (which gene; ex: 16S), you can identify species    
* Compare genes between treatments      

**GBS**   
```
Whole genome seq ---------RNA seq---------------------------GBS (RAD seq)------------------Amplicons   
everything               just gene space expressed        lots of SNPs across genome      single gene         (completeness)    
1 individual             a few individuals (~10s-100s)       lots of indivs     many individuals (1000s?)    (sampling tradeoffs)		
```

GBS doesn't care about specific genes; can randomly sample genome space   
GBS - genotyping by sequencing (get SNPs by process of genotyping)   
RAD - restriction assisted DNA sequencing (common to be used synonmously)   

1. restriction enzyme - cuts double stranded DNA; finds sequence enzyme recognizes and cuts at appropriate sequence; creates overhangs called 'sticky ends' (looks like tetris pieces)   
2. Adaptors and barcode ligate to sticky ends     
3. PCR 
4. Sequence (usually single end reads; doesn't really benefit from paired end)    

Not all individuals have same restriction sites (restriction sites can be polymorphic)   
**Individuals**    
| 1 | 2 | 3 | 4 |     
| + | - | + | + |   
| - | - | + | - |  

**Fragments/Loci on y axis**

Limitations   
* Individuals that vary in methylation will vary in fragments that are produced (restriction enzymes sensitive to epigenetic modifications - may skip over)   
* Reduced representation   


------ <div id='id-section7'/>

### Page 7: 2017-02-01 Unix Tutorial and Tips   

Link to [Unix Tutorial](https://github.com/stephenrkeller/PBIO381_srkeller_labnotebook/blob/master/Tutorials/Tutorials_CommandLine.md) 
* How to connect to server (use netID with UVM password)    
* Server has 24 cpu cores; 32Gb RAM   
* 1 TB HD   
* top shows how much memory is being used and who is working (q for quitting out)   
* / goes back to most basal directory   
* ~/ goes to home directory   
* head -n 15 ssw_samples.txt (-n is an option to specify number of rows you want to see)   
* mv moves files: ```mv *only* subsets/``` * will choose files with any text before (*only.txt) or after (*only*)   
* mv also renames files (ex: mv subsets subsets_by_disease) mv currentname newname   


[Andrew's Ecological Genomics Webpage](https://adnguyen.github.io/2017_Ecological_Genomics/)   
[Unix Cheat Sheet](https://files.fosswire.com/2007/08/fwunixref.pdf)    
​    
------ <div id='id-section8'/>

### Page 8: 2017-02-03 Article: Dunning et al. 2014   
### Divergent transcriptional responses to low temperature among populations of alpine and lowland species of New Zealand stick insects (*Micrarchus*)   

**Background**    
* Subzero temperature exposure leads to: membrane rigidity, apoptosis (cell death), oxidative stress, and loss of sodium ions/water from haemolymph (insect blood)   
* Cold-responsive loci have been identified in *Drosophila* (roles of gene regulation, immune function, metabolism, stress, cuticles, membranes, and cytoskeleton, but do not overlap with those identified in other insects and gene expression patterns differ among species
* **Hypothesis**: species with poor dispersal abilities are likely to have strong phylogenetic structure as a result of genetic drift and possibly local adaptation; resulting divergent genetic backgrounds are likely to contribute to variation in transcriptional responses to environmental stress   
* Study organism: New Zealand stick insect genus with varying extremes in temperature encounterd of 4 species (M nov. sp. 2 encounters more extreme cold temperatures (+3.6 degrees C) and ten times more freeze-thaw cycles than other 3 species)   

**Methods**   
* Phylogeny   
  + Nuclear and mitochondrial DNA sequence data collected   
  + Assembled/aligned with Geneious   
  + Model was chosen with jModelTest   
  + Bayesian tree: MrBayes   
  + Maximum Likelihood tree: Garli   
* Cold shock experiments on females   
* Total RNA extracted, ambiguous bases were removed; cleaned reads were grouped by population and assembled de novo   
* R packages were used to determine which genes were differentially expressed (considered diff. expressed if significant for at least 1 analysis)   
* Subset of 6 genes was selected for qPCR analysis; with two non-differentially expressed reference genes for normalization between genes   
* Biological replicates: different individuals from the same population   
* Technical replicates: replicates of same individual (ex: qPCR run in duplicate)   
* SNP data were generated from a new Trinity assembly   

**Results**   
Fig 1: phylogeny 28S of the 4 species; shows geography and haplotypes   
Fig 2: phylogeny of mitochondria does not separate out as much; geographically proximal populations often grouping (possible introgression/hybridization)   
Fig 3: a. maximum likelihood estimation (k=3 best fit) of ancestry using SNP data b. PCA - 3 separate populations   
Fig 4: very little shared response among the 3 populations; the middle Venn diagram is most different (Micrarchus nov. sp. 2)   
Table 1: number of DEGs with three methods - no comparison, unfortunately; variability between the 3 methods   
Table 2: nov. sp 2. has most variety in function of genes; both # DEG in both control and treatment tell us something    
Fig 5: tries to relate qPCR results (look at copy number of cDNA) with differential expression (compare with read #s)

**Discussion**   
Take home biological: a lot of diff. expressed genes in nov. 2 sp. could suggest selection   
Take home technical:  no Venn diagrams! justify statistical analysis    
​    
**Discussion in class**   
Unigenes: collapse alternative splice variant contigs into 'unigenes' and takes the longest one to be the representative contigs   
enrichment: functional classification (can group genes into pathways; figure out which genes are related to 'cold tolerance')   
BlastX to NR (gene annotation); to uniprot [of proteins] database (Gene Ontology [GO] functional categories)   

60k unigenes: 10% related to cuticular hydrocarbons   
2K DGE: ~20% cuticular HC group   
Is this more than expected? Use Fisher's exact test   



------ <div id='id-section9'/> 

### Page 9: 2017-02-06 Info update for RNA seq and article discussion   

Beforehand: 
* Figure out approach   
* Experimental design   
* Library prep    
* Sequencing (facility)   
* Receive data  
* Computer/server set up

**RNA seq work flow**   
```
1. Clean reads (fastq or fq.gz files)   
- Get rid of adaptors   
- Nucleotide quality   
- Length   

2. Evaluate the quality   
   
3. De novo transcriptome assembly (if reference genome unavailable; fasta files)      
- then evaluate assembly: what percentage match closely related species; compare to reference CEG (core eukaryotic genes); N50; # contigs   
- Annotation (BLASTX; GO: Gene Ontology)   
   
4. Map reads to reference transcriptome -> generates alignment files  (.sam sequence alignment files)   
   
5. a. Extract read count information   
- number of reads that map to each contig for each sample   
   
5. b. Identify SNPs (single nucleotide polymorphisms)   
   
6. a. Differential gene expression analyses (DGE)   
- Co-expression network analyses   
   
6. b. Population genomics with SNPs   
- Analyses for genetic differentiation between groups   
- Population structure   
- Demographic history    
- Test for signatures of selection   
```




------ <div id='id-section10'/>

### Page 10: 2017-02-06 RNA-seq Coding   

[RNA seq Tutorial](https://adnguyen.github.io/2017_Ecological_Genomics/Tutorial/2017-02-06_RNAseq_tutorial.html)   

cd /data/project_data/fastq   

My samples I am in charge of: 19_5-20_S_5_R1.fq.gz and 19_5-20_S_5_R2.fq.gz   

zcat 19_5-20_S_5_R1.fq.gz | head   
zcat 19_5-20_S_5_R2.fq.gz | head   

The fast file format has 4 lines for each read: the read identifier, the read sequence, “+”, and a sequence of quality scores for each base. [Phred quality scores](http://www.drive5.com/usearch/manual/quality_score.html)   

We'll use **Trimmomatic** program to clean the reads for each file   
**Moved script from main directory scripts folder to my scripts folder:**
cd /data/scripts/   
cp trim_example.sh ~/scripts/   

Edit script with vim - change file names and extensions   
escape :w to save   

**Results:** Input Read Pairs: 23380667 Both Surviving: 19638718 (84.00%) Forward Only Surviving: 2818120 (12.05%) Reverse Only Surviving: 381554 (1.63%) Dropped: 542275 (2.32%)
TrimmomaticPE: Completed successfully

Last line I run: fastqc /data/project_data/fastq/19_5-20_S_5_R1.fq.gz   

------ <div id='id-section11'/>

### Page 11: 2017-02-08 Transcriptomics info update   

Outline:   
Introduction   
Brief Overview of Transcriptomics   
Main Questions   
Future Directions   

Why wild systems? 
- A way of looking at non-model organisms (or non-traditional model organisms) in natural settings   
- Silent genes responding to multiple stimuli   
- Novel transcripts without homologues in closely related organisms   

Two ways of studying transcriptomics:   
- Microarrays 
  + Older   
  + Easy for ecological analyses
- RNAseq   
  + Newer   
  + Allows for genome-wide ecological transcripts   
  + Data/analyses much more time consuming and involved   

Questions:   
**1. How much variation is there in gene expression and how is it structured?**   
Evolutionary process: gene expression is heritable so natural selection can act upon it   
Epigenetics   
Qst-Fst comparisons   
eQTL - expression quantitative trait loci mapping   
Macro evolution: drift, selection, bottleneck   
**2. How do environmental stimuli affect gene expression?**  
Abiotic stress   
Environmental heterogeneity in time or space      
Host-parasite interactions   
Selective biotic and abiotic interactions   
-Molecular response   
-Genotype   
-Phenotypic plasticity   
Flash freeze samples; taking a snapshot of transcription at that point in time (unless time-course analyses)      
**3. How does gene expression affect phenotype?**  
Alternate phenotypes: how does expression difference translate into phenotypic variation? how does pollution/drought tolerance affect phenotypes?   
Push to move from correlation to causation: manipulation of transcription (transgenics, RNAi, CRISPER/CAS); knock down of genes to determine if you still get phenotype   

Where do we go?   
- Using combined microarrays and RNAseq to test gene expression hypotheses in natural populations? (microarrays are outdated)  
- Expand database for proposed ecological variation annotations   

Problems: bias in signals; heterologous arrays (for microarrays); polyploidy; RNA pooling; statistical analyses; unannotated genes   

Glossary:   
**transcriptomics:** the study of the transcriptome which is the complete set of RNA transcripts produced by the genome   
**Qst-Fst comparisons:** a means to distinguish between genetic drift and natural selection in driving differentiation in a population   
*Qst*= amount of variation in quantitative traits in a population   
*Fst*= variation at neutral loci   

**Article discussion: DeWit et al. 2012**
Cactophilic *Drosophila* species with primary and secondary host expression differences  

### RNAseq coding Pt 2 
Skills learning objectives:   
* Modifying script   
  + Paths: program, input, output   
  + Filenames: in, out   
* Moving through directories and files   
* Moving files from server to PC (scp)    
* Executing scripts   
* Calling programs      

- Finish cleaning (trimmomatic)   
- fastqc (vis.)   
- Make table of reads   
- Design assembly tests   
- Start assemblies   
- Evaluate assembly

------ <div id='id-section12'/>

### Page 12: 2017-02-10 Prepping for Todd et al. info update      

## The power and promise of RNA-seq in ecology and evolution   

### Glossary terms:   
**Sequence coverage:** describes the average number of reads that align to, or "cover," known reference bases. [Link](https://www.illumina.com/science/education/sequencing-coverage.html)   
**Read depth:** the total number of bases sequenced and aligned at a given reference base position [Link](https://www.illumina.com/science/education/sequencing-coverage.html)     
**Statistical noise:** unexplained variation/randomness in a sample     
**Statistical power:** probability that it will reject a false null hypothesis; reflects ability to distinguish true differential expression due to treatment effect from background noise      
**Biological variance:** natural variation in gene expression measurements due to environmental or genetic differences   
bio rep: individals from same trt; technical: same sample     
effect size: effect size as the contribution of the SNP to genetic variance of the trait (standard deviations from mean)   

### Outline:   
#### RNA-seq Background:   
+ **Enables examination of DE** underlying **interindividual and interpopulation variation**   
  + Disease resistance   
  + Mating behavior   
  + Adaptive significance in changing environments   
+ Key technology for using integrative biology to understand **molecular mechanisms of phenotypic/behavioral plasticity**   
+ **Limitations:** reference genome quality; gene annotation availability; expense of per sample library prep 

   
#### Issues   
+ RNA-seq studies still **underutilize biological replication** (diff individuals in a trt)   
  + Defined in paper as **'requiring independent library preparations'**/multiple libraries representing biologically distinct samples from each condition  
  + **Pooling multiple independent samples** saves costs but only provides **average of the expression states across samples (not true biological replication)**   
  + **23/158 studies, 15%, used more than 3 biological replicates**   
  + Many **derive broad biological conclusions from data with little/no biological replication**   
+ Study designs **prioritize sequencing depth over replication**, so fail to capitalize on the power of RNA-seq technology for DE inference 
+ Wide dynamic range makes **RNA-seq data potentially very noisy**   
  + **Poisson counting error** - uncertainty inherent in any count-based measurement   
  + **Non-Poisson technical variance** (ex: sample collection/storage/processing, RNA quality, flow cell and lane effects during Illumina sequencing)   
  + **Biological variance** - natural variation in gene expression measurements due to environmental or genetic differences (**represents greatest source of within-group variance**)      

#### R exercise: Visualize influence of replicates on power of an experiment   
+ Power equation in RNA-seq influenced by sample size, depth, choice of Type 1 error rate (falsely rejecting true null hypothesis; alpha), expression landscape, bio/tech variation   
  + Inherent power bias in RNA-seq towards longer transcripts and transcripts with higher expression (see Activity)   
  + Acceptable power >80%   
  + effect size measured in fold change (Control gene with 10 reads vs DE gene 20 reads; fold change of 2)   
  + R code; depth; **n (replicates); cv (biological coefficient of variation);** effect (effect size in fold change); **alpha (false positive rate)**   
+ Conclusions: Large effect size and/or low biological variance -> higher power   
+ Why lower power with low effect size? Difficulty differentiating true expression differences from background noise    

#### General Rules of thumb:   
1. Sequence **more replicates rather than increasing read depth** (improved estimation of bio variance)      
2. Sequence each sample to a **depth** that ensures the majority of transcripts are covered by **>10 reads** (minimizing sampling noise bias and Poisson counting error plateaus; **~10-20M mapped reads/sample** is sufficient)   
3. Sequence at least **3 biological replicates per condition**, more when biological variance is high and/or when the research question inclues small expression differences   
4. Conduct a **pilot sequencing experiment** (**What is best/powerful experiment I can afford? What is smallest fold change I can reliably detect?**) Use **tools!**  

There are a few software tools that can evaluate statistical power and calculate appropriate sample sizes and depths for DE experiments    
##### If there is time:   
Take into account research question (exceptions):   
+ Rare transcripts   
+ Subtle fold changes   
+ Isoform-level analysis   
+ De novo transcriptome assembly required   


## Using Screen in Terminal   
screen
bash bwaaln.sh

press ctrl + a + d (detach)   

screen -r (reattach)

------ <div id='id-section13'/>

### Page 13: 2017-02-15. SNPs and Population Genomics Info Update

**Glossary**

**SNP (single nucleotide polymorphisms)**: single base differs between 2 genomes
AAATCT vs AAATGT

**InDels (Insertion/deltion)**: single base has been deleted/inserted into one genome relative to another

**Fst**: percentage of genetic material explained by differences among populations



Hard to determine if true SNP or just error so: 

**Guidelines:**

1. Tissue -> obtain breadth of tissue in different developmental stages to capture variation (exon skipping)
2. Pool and sequence libraries -> ~30-100M paired-end long reads
3. Process raw sequence data for quality and errors; important for SNP detection
4. Digital normalization of sequence data - remove high coverage reads which will remove errors contained in reads 
   *Loss of quantitative info*  (reduces sampling variation; can't assess expression levels)
5. Assemble cleaned pair end long reads
6. Prune - reduce DNA contamination; non-coding RNA, gen fragments
7. Assembly evaluation (use reference genome or use COGs - conserved eukaryotic ortholog genes)
8. SNP detection
   * software that looks for constant patterns of sequence variation; 
     * problems: sequence error; try eliminates SNPs with low frequency
     * artifacts caused by InDels; try to filter SNP clusters near Indels and use quality scores
   * Validation - primers; sequencing, mass spec

<u>Applications</u>

- differences in population structure

- natural selection acting on particular loci

  Outliers

- For a given locus, what's the level of differentiation compared to differentiation across the genome?

- Extreme divergence of Fst (think normal distribution) - directional selection on those genes/loci

  Non-outlier

- Tests high Fst loci for other features associated with selection

  - How are they associated with fitness? 
  - Enrichment for certain functional roles

SNPs act as 'footprints' for natural selection and can let us know if we need to test further



------ <div id='id-section14'/>

### Page 14: 2017-02-15. Article discussion: Zhao et al. 2016

[Andrew's Notes](https://adnguyen.github.io/2017_Ecological_Genomics/ANBE_notebook.html#id-section10)

**diapause**: a period of suspended development in an insect, other invertebrate, or mammal embryo, especially during unfavorable environmental conditions. Temperature, nutrient availability, and photoperiod can drive diapause

Question: Are clinal SNPs associated with diapausing?

**Methods:** 

4 popoulations (northern) east coast us: sampled in october with 50 isofemale lines each orchard
​	isofemale line: Originating from a single wild female

<u>Diapause</u>: arrest before vitellogenesis (process of yolk formation via nutrients being deposited in the oocyte)
<u>Non-diapause</u>: vitellogenin was observed (a protein present in the blood, from which the substance of egg yolk is derived).

*isoform*: splice variant of gene; exon skipping 

Figure 1: RPKM/FPKM: reads/fragments per kilobase of transcript per million mapped reads;  the relative expression of a transcript is proportional to the number of cDNA fragments that originate from it; scales according to size of transcript

They found the a priori genes (cp, tim, dp110) were not DE but certain isoforms of those genes were!

Figure 4: integrates DE info with previous SNPs associated with clinal and seasonal enrichment; only downregulated in diapausing head were significantly associated; metabolism? 

Questions: Does gene level DE count isoforms as one gene? 



------ <div id='id-section15'/>

### Page 15: 2017-02-15 Sequence alignment (SAM) files and Read Count Extraction Coding  

[Link to tutorial](https://adnguyen.github.io/2017_Ecological_Genomics/Tutorial/2017-02-15_RNAseq_Map_Count.html)   

[Vim Cheat Sheet](https://vim.rtorr.com/)

​	$ jumps to end of the line
​	w jumps forward to start of a word
​	b jumps backwards to start of a word

Important [tags](http://bio-bwa.sourceforge.net/bwa.shtml) to look at (they are at end of line in .sam file): XT(Type: Unique/Repeat/N/Mate-sw *Unique is best*); X0 (Number of best hits *1 is best*); X1 (Number of suboptimal hits found by BWA)

The following code lets us see how many reads map to a unique gene (1) and how many number of best hits=1  (2) 

```
grep -c XT:A:U 195-20S5bwaaln.sam
5098785

grep -c X0:i:1 19_5-20_S_5_bwaaln.sam 
5138735

```

Trying to run the python script gives an error because of the contig names (too long, semi colons)

```
python countxpression_PE.py 20 35 countstatssummary.txt 19_5-20_S_5_bwaaln.sam 

Traceback (most recent call last):
  File "countxpression_PE.py", line 159, in <module>
    countxpression(file, sys.argv[1], sys.argv[2], 0, 'text', file[:-4]+'_counts.txt', sys.argv[3])
  File "countxpression_PE.py", line 75, in countxpression
    contigs[cols[2]][0]+=1
KeyError: 'TRINITY_DN29662_c0_g1::TRINITY_DN29662_c0_g1_i1::g.5880::m.5880'
```



Using sed (command line find and replace)
```-i``` is find and replace at command line
```s```  search
```/ /``` separates what we're looking for
```::``` what we're looking for (offending character string)
```\```  because underscore is special character we need \ to recognize it as an actual underscore
```_``` replacing with underscore
```g``` do it globally across the entire file (not just first line)=replace all

```
sed -i 's/::/\_/g' 19_5-20_S_5_bwaaln.sam
```

Now we have reasonable contig names! The python script works and creates ```19_5-20_S_5_bwaaln_counts.txt```

We are interested in first column (total unique reads)



------ <div id='id-section16'/>

### Page 16: 2017-02-22 DESeq2 in R

### Moving the R scripts and files from the server to Ecological Genomics 
* Open new terminal window and set the working directory to where you want to move files
* Use scp to move: Don't forget the **period after the file name!!!!** It tells it to move it to where you are
```
cd Desktop/UVM/Courses/Ecological_Genomics/
scp lvash@pbio381.uvm.edu:/data/project_data/DGE/* . 
```
The following code loads the package into R
```
source("http://bioconductor.org/workflows.R")
workflowInstall("rnaseqGene")
```


------ <div id='id-section17'/>

### Page 17: 2017-02-27 Scott Edwards paper    

**Glossary**
* **coalescent (multi-species coalescent; MCS)** - two lineages tracing back in time finding common ancestor   
* **reticulation** -   
* **purifying/background selection** -   
* **gene trees vs species trees** - Can we make gene trees with SNPs?    
* **introgression/recombination** - hybridization (two different species exchanging genetic info)   
* **incomplete lineage sorting** - passage of allele is following divergence of species, but divergence of alleles predate speciation; large population size and short time can affect this (large t/Ne resembles species tree);   
* **recombination** - another type of reticulation; blurs gene boundaries


Craig Moritz (last author) - Australia; reptiles/amphibian population genetics   

------ <div id='id-section18'/>

### Page 18: 2017-03-01 Homework Assignment info and WGCNA

### WGCNA - Weighted correlation network

**Glossary**   
* Module - Modules are clusters of highly interconnected genes. In an unsigned co- expression network, modules correspond to clusters of genes with high absolute correlations. In a signed network, modules correspond to positively correlated genes.   
* Connectivity - For each gene, the connectivity (also known as degree) is defined as the sum of connection strengths with the other network genes: ki =  u iaui. In co- expression networks, the connectivity measures how correlated a gene is with all other network genes.   
* Intramodular connectivity - measures how connected, or co-expressed, a given gene is with respect to the genes of a particular module. The intramodular connectivity may be interpreted as a measure of module membership.   
* Modular Eigengene - defined as the first principal component of a given module. It can be considered a representative of the gene expression profiles in a module.   
* Eigengene significance - When a microarray sample trait y is available (e.g. case control status or body weight), one can correlate the module eigengenes with this outcome. The correlation coefficient is referred to as eigengene significance.   
* Gene significance - the higher the absolute value of GSi, the more biologically significant is the i-th gene; also be defined by minus log of a p-value. The only requirement is that gene significance of 0 indicates that the gene is not significant with regard to the biological question of interest. The gene significance can take on positive or negative values.   

Outline:   
1. Overview of WGCNA   
2. Network Construction  
3. Module Detection   
4. Incorporation of External Info into Network   
5. Topological properties   
6. Other features   
7. Limitations   

- R package: applies correlation network methods to describe correlation (coexpression) patterns among genes in micro-array samples   

2. **Network Construction**   
Node - gene   
Edges - how strongly correlated in terms of expression   
Package provides different co-expression measures   
Makes signed (+/-) or unsigned networks (absolute value of correlation)   

Identify modules (clusters of gene) then test for correlation in traits/factors (clusters of genes associated with being sick/low score/location/etc?); 'collapse' weak correlations
```
		         1  2   3       n individuals
sea star  = l1 | g11 g12 g13 ... g1n |
 data	    l2 | g21 g22 g23 ... g2n | 
	        lm | gm1 gm2 gm3 ... gmn | 
```

unweighted network analysis 
- hard threshold for whether genes are linked or network for expression   
- can lose information

vs weighted network analysis
- package allows for soft or hard threshold   
   
3. **Module detection**   
- unsupervised clustering (less bias / no a priori defined gene sets)   
- removes weak clustering   
- summarizes profiles of modules (involves eigengene)   

4. **Relating info with external information**   
- depends on questions   
- gene significance -> assigns a positive number to each gene; tells whether genes are associated with trait of interest   
   
Ran out of time, didn't finish

### Assignment   
- Due Wednesday, March 8   
- Looking at sick and healthy and then sick/healthy and location   
- ~1 page of text and then figures/tables   
- Reference online notebook for scripts and work   
	    

------ <div id='id-section19'/>

### Page 19: 2017-03-06 Population Genomics: Steve's Info Update and Alex's Discussion   

**Glossary**   
* paralog: gene duplicate   
* π: pairwise nucelotide diversity   
* SFS: Site frequency spectrum = histogram of allele frequencies   
* Ne: effective population size   

**Population genomics (def):**    
- SNPs and lots of them   
- sampling unit is individuals within species   
- processes:   
	+ population structure   
	+ population diversity within and between populations   
	+ selection (different kinds of selection - negative/'purifying' or positive)   
	
**Pipeline**   
Raw reads -> Clean/trimmed -> Assembled draft transcriptome -> Mapped clean reads reference **->** transcriptomics (count # of reads per transcript) -> differential gene expression   
   
Raw reads -> Clean/trimmed -> Assembled draft transcriptome -> Mapped clean reads reference **->** "Population Genomics" Call SNPs (is given position of transcript variable? if yes, then SNP) and Genotypes (is it heterozygote or homozygote?) -> allele frequencies; SFS; nucleotide diversity (π)   

**Challenges of SNP calling**   
* Sequencing error (Illumina error rate is ~1%)
	+ Filters: minor allele frequency (how many individuals is it found in? filter out rare SNPs across individuals)   
	+ Depth (less confident with less depth)   
	
** Challenges of Genotype (AA AT TT) calling**   
* If G=AT, predict A=T=0.5   
* Assign probabilities (AAAAAAATTT) T=3/10; probability of heterozygote is high   

**Challenges of Paralogy**   
* Gene duplicates   
* One gene has AAAAAAAAAA and the duplicate has a SNP TTTTTTTTTT   
* This leads to ~100% of individuals being heterozygotes (violates Hardy-Weinberg)      
* Can use Hardy-Weinberg = p^2^ +2pq + q^2^ to test for excess of hetereozygoes which points to paralogy   

**π**   
* Expected heterozygosity   
* For two sequences in population (i and j), π = sum(xi * xj * πij) (frequency of i times frequency of j times times number of differences between sequences)   
* πsyn (syn = synonomous sites; don't change nucleotides) = 4Ne * mu (mutation rate)   
* πnonsyn more affected by selection; don't want bias affecting population size estimate   
* πnonsyn/πsyn = 1 with no selection; pretty much always less than one because selection acting on nonsyn (because nonsyn sites almost always deleterious); use ratio as how strong selection is working; low ratio = purifying selection       

### Gayral et al. 2013 paper discussion   
#### Reference-Free Population Genomics from Next- Generation Transcriptome Data and the Vertebrate– Invertebrate Gap   

* Our expectation is that small-Ne species should show a lower pN, a lower pS, and a higher pN/pS ratio than large-Ne species. (mutations occur in meiosis; large populations are reproducing more leading to more meiosis and more mutations)   






------ <div id='id-section20'/>   

### Page 20:2017-03-06 Population Genomics Tutorial 
[Link to Tutorial](https://adnguyen.github.io/2017_Ecological_Genomics/Tutorial/2017-03-06_Tutorials_PopGenomics1.html)   

```:set nowrap``` in vim does not wrap text and makes it easier to read

```vcftools --vcf SSW_bamlist.txt.vcf``` summarizes data     
   
Did it detect the correct number of individuals? kept 24 out of 24 Individuals   
How many SNPs do we have? 7472775   

```grep "unres" SSW_bamlist.txt.vcf | wc ``` this searches for SNPs deemed unresolved ("unres") and pipes it to a wordcount (wc) function   
Output: 
```5631864 185851488 1028494934
``` 
**5631864 were unresolved**   

```
lvash@pbio381 reads2snps]$ grep "para" SSW_bamlist.txt.vcf | wc
   4354  143652  795592
```
**4354 were paralogs**   

**1,836,557 SNPs survived the filter** of unres and para (SNPs that were not unresolved or paralogs)   

We only want bi-allelic SNPs (more than two alleles is most likely an error) so we use this code:   
```
vcftools --vcf SSW_bamlist.txt.vcf --min-alleles 2 --max-alleles 2
After filtering, kept 20319 out of a possible 7472775 Sites   
```   
**Minor allele frequency (MAF)**: Gets rid of very rare SNPs - If we have a SNP that is only seen very rarely, it may be a sequencing error, and should be discarded. For us, the most liberal MAF filters would be 1 allele copy out of the total 2N copies, or 1/48 = 0.02   
```
$ vcftools --vcf SSW_bamlist.txt.vcf --maf 0.02   
After filtering, kept 5656584 out of a possible 7472775 Sites
```   
**Missing data across individuals**: individuals are missing data for a given SNP; this code allows 20% missing data   
```
vcftools --vcf SSW_bamlist.txt.vcf --max-missing 0.8
```
Now we can combine all of the filters and direct the output to our home directory (produces log file with output of how many SNPs and individuals were kept) and a vcf file that lists all of the genes and corresponding genotypes: 
```
vcftools --vcf SSW_bamlist.txt.vcf --min-alleles 2 --max-alleles 2 --maf 0.02 --max-missing 0.8 --recode --out ~/mydata/biallelic_20percentmissingdata_MAF02
```
We can look at the observed and expected heterozygosity for each SNPs and test if any violate Hardy-Weinberg equilibrium expectations (give an output file of out.hwe that we will load into R):   
```
vcftools --vcf filtered_filename.vcf --hardy
```

We can use R in the Terminal!! (Just type R and press enter)   
```
$ R
> getwd()
[1] "/data/users/l/v/lvash/mydata"
> hardy<-read.table("out.hwe", header=T)
> str(hardy)
> hardy[which(hardy$P_HET_EXCESS<0.001),] ## which rows are significantly deviated from H-W (excess heterozygosity)   
<0 rows> (or 0-length row.names)
> hardy[which(hardy$P_HET_DEFICIT<0.01),]
                                                                 CHR POS
277 TRINITY_DN45155_c27_g2_TRINITY_DN45155_c27_g2_i2_g.18743_m.18743 216
291 TRINITY_DN45155_c27_g1_TRINITY_DN45155_c27_g1_i1_g.18742_m.18742  99
293 TRINITY_DN45155_c27_g1_TRINITY_DN45155_c27_g1_i1_g.18742_m.18742 138
401     TRINITY_DN39079_c3_g1_TRINITY_DN39079_c3_g1_i1_g.8354_m.8354 244
406     TRINITY_DN39696_c4_g1_TRINITY_DN39696_c4_g1_i1_g.8926_m.8926 283
    OBS.HOM1.HET.HOM2. E.HOM1.HET.HOM2. ChiSq_HWE        P_HWE P_HET_DEFICIT
277             22/0/2  20.17/3.67/0.17        24 1.418440e-03  1.418440e-03
291            11/0/13  5.04/11.92/7.04        24 9.114786e-08  9.114786e-08
293             19/0/5  15.04/7.92/1.04        24 6.498371e-06  6.498371e-06
401            13/0/11  7.04/11.92/5.04        24 9.114786e-08  9.114786e-08
406            13/0/11  7.04/11.92/5.04        24 9.114786e-08  9.114786e-08
    P_HET_EXCESS
277            1
291            1
293            1
401            1
406            1
```
**These five loci above show heterozygosity deficit which can be indicative of inbreeding**   
 OBS.HOM1.HET.HOM2. (observed homozygous/heterozygous/homozygous) 
 E.HOM1.HET.HOM2. (expected under H-W)


Linkage: defines maximum number of physical bases between the SNPs being tested for LD   
How much of SNPs on one transcript statistically linked with SNPs on another transcript?

So we're gong to use --geno-r2 (vcftools in Terminal)
Calculates the squared correlation coefficient between genotypes encoded as 0, 1 and 2 to represent the number of non-reference alleles in each individual. This is the same as the LD measure reported by PLINK. The D and D’ statistics are only available for phased genotypes. The output file has the suffix ".geno.ld".

Let's go back into R and visualize output:
```
$ R
> LD<-read.table("out.geno.ld", header=T)
> LD$dist<-abs(LD$POS1-LD$POS2) # distance in each base pair being compared; as you get further away 
> pdf("LD.plot.pdf")
> plot(LD$dist,LD$R.2)
```

------ <div id='id-section21'/>

### Page 21: 2017-03-07 Homework 2: RNA sequencing for gene expression analyses

Here is the code I used to subset out the data into Intertidal versus Subtidal   
```
library("DESeq2")
library("ggplot2")


conds <- read.delim("cols_data_trim.txt", header=TRUE, stringsAsFactors=TRUE, row.names=1)
colData <- as.data.frame(conds)
colDataINT<-subset(colData, colData$location=="int") ## subsetting colData is easy
colDataSUB<-subset(colData, colData$location=="sub")

countsTable <- read.delim('countsdata_trim2.txt', header=TRUE, stringsAsFactors=TRUE, row.names=1)
countData <- as.matrix(countsTable)
## subsetting countData is trickier because we have to match up the row names in the colData with the column names in the count data to accurately subset
countDataINT<-countData[, which(colnames(countData) %in% row.names(colDataINT))] 
countDataSUB<-countData[, -which(colnames(countData) %in% row.names(colDataINT))]
dim(countDataINT)
dim(countDataSUB)
```
Here is my code for the first model (controlling for location):   
```
#################### MODEL NUMBER 1: TEST EFFECT OF HEALTH CONTROLLING FOR LOCATION

ddsFULL <- DESeqDataSetFromMatrix(countData = countData, colData = colData, design = ~ location + health)

ddsFULL <- ddsFULL[ rowSums(counts(ddsFULL)) > 100, ]

colData(ddsFULL)$health <- factor(colData(ddsFULL)$health, levels=c("H","S"))

ddsFULL <- DESeq(ddsFULL)
resFULL <- results(ddsFULL)
resFULL <- resFULL[order(resFULL$padj),] #sorts according to pvalue
head(resFULL)
summary(resFULL)
```
Here are the subsetted models (first just intertidal then just subtidal):   

```
##### MODEL SEPARATELY IN EACH LOCATION: INTERTIDAL
ddsINT <- DESeqDataSetFromMatrix(countData = countDataINT, colData = colDataINT, design = ~ health)

ddsINT <- ddsINT[ rowSums(counts(ddsINT)) > 100, ]

colData(ddsINT)$health <- factor(colData(ddsINT)$health, levels=c("H","S"))

ddsINT <- DESeq(ddsINT)
resINT <- results(ddsINT)
resINT <- resINT[order(resINT$padj),] #sorts according to pvalue
head(resINT)
summary(resINT)

##### MODEL SEPARATELY IN EACH LOCATION: SUBTIDAL
ddsSUB <- DESeqDataSetFromMatrix(countData = countDataSUB, colData = colDataSUB, design = ~ health)

ddsSUB <- ddsSUB[ rowSums(counts(ddsSUB)) > 100, ]

colData(ddsSUB)$health <- factor(colData(ddsSUB)$health, levels=c("H","S"))

ddsSUB <- DESeq(ddsSUB)
resSUB <- results(ddsSUB)
resSUB <- resSUB[order(resSUB$padj),] #sorts according to pvalue
head(resSUB)
summary(resSUB)
```
I performed a likelihood ratio test to compare the model controlling for location with a model that doesn't   
```
ddsLRT <- DESeq(ddsFULL, parallel=T, test="LRT", reduced = ~ health)
resLRT <- results(ddsLRT)
resLRT$symbol <- mcols(ddsLRT)$symbol
resLRT<-resLRT[order(resLRT$padj),]
summary(resLRT)
### look at the pvalue and padj to see if full model is sig diff; if any padj values are significant, indicates that whole model is sig diff
u<-resLRT$padj<0.01
length(u[u==TRUE]) #[1] 10151 genes are significantly different between models
```
Here is the code for the count plots (all models; 2 genes)   
```
###### COUNT PLOTS FOR GENE DN43080c1g1 #########
## Full model
dFULL <- plotCounts(ddsFULL, gene="TRINITY_DN43080_c1_g1_TRINITY_DN43080_c1_g1_i3_g.14110_m.14110", intgroup=(c("health","score","location")), returnData=TRUE)
pFULL2 <- ggplot(dFULL, aes(x=score, y=count, color=location, group=health))
pFULL2 <- pFULL2 +  geom_point() + ggtitle("DN43080c1g1: Full") + stat_smooth(se=FALSE,method="loess") +  scale_y_log10() + scale_color_manual(values=c("#999999", "#E69F00"))   

## Subtidal model
dSUB2 <- plotCounts(ddsSUB, gene="TRINITY_DN43080_c1_g1_TRINITY_DN43080_c1_g1_i3_g.14110_m.14110", intgroup=(c("health","score")), returnData=TRUE)
pSUB3 <- ggplot(dSUB2, aes(x=score, y=count, color=health))
pSUB3 <- pSUB3 +  geom_point() + ggtitle("Subtidal") + stat_smooth(se=FALSE,method="loess") +  scale_y_log10()

## Intertidal model
dINT <- plotCounts(ddsINT, gene="TRINITY_DN43080_c1_g1_TRINITY_DN43080_c1_g1_i3_g.14110_m.14110", intgroup=(c("health","score")), returnData=TRUE)
pINT2 <- ggplot(dINT, aes(x=score, y=count, color=health))
pINT2 <- pINT2 + ggtitle("Intertidal") + geom_point() + stat_smooth(se=FALSE,method="loess") +  scale_y_log10()

### COUNT PLOTS FOR GENE DN42073c0g1 #########
## Subtidal model
dSUB <- plotCounts(ddsSUB, gene="TRINITY_DN42073_c0_g1_TRINITY_DN42073_c0_g1_i1_g.12173_m.12173", intgroup=(c("health","score")), returnData=TRUE)
pSUB2 <- ggplot(dSUB, aes(x=score, y=count, color=health))
pSUB2 <- pSUB2 +  geom_point() + ggtitle("Subtidal") + stat_smooth(se=FALSE,method="loess") +  scale_y_log10()

## Intertidal   
dINT2 <- plotCounts(ddsINT, gene="TRINITY_DN42073_c0_g1_TRINITY_DN42073_c0_g1_i1_g.12173_m.12173", intgroup=(c("health","score")), returnData=TRUE)
pINT3 <- ggplot(dINT2, aes(x=score, y=count, color=health))
pINT3 <- pINT3 + ggtitle("Intertidal") + geom_point() + stat_smooth(se=FALSE,method="loess") +  scale_y_log10()

## FULL
dFULL2 <- plotCounts(ddsFULL, gene="TRINITY_DN42073_c0_g1_TRINITY_DN42073_c0_g1_i1_g.12173_m.12173", intgroup=(c("health","score")), returnData=TRUE)
pFULL3 <- ggplot(dFULL2, aes(x=score, y=count, color=health))
pFULL3 <- pFULL3 + ggtitle("DN42073c0g1: Full") + geom_point() + stat_smooth(se=FALSE,method="loess") +  scale_y_log10()+scale_color_manual(values=c("#999999", "#E69F00"))

library(gridExtra)
### Combining different models for 2 genes: DN43080_c1_g1 and DN42073_c0_g1
grid.arrange(pFULL2, pINT2, pSUB3,pFULL3,pINT3,pSUB2, ncol=3)

```
Here is the code for the PCA plots (all models)
```
### PCA FOR HEALTHY VS SICK: FULL, SUBTIDAL, INTERTIDAL
vsdFULL <- varianceStabilizingTransformation(ddsFULL, blind=FALSE)   
vsdSUB <- varianceStabilizingTransformation(ddsSUB, blind=FALSE)
vsdINT <- varianceStabilizingTransformation(ddsINT, blind=FALSE)


PCA1<-plotPCA(vsdFULL, intgroup=c("health"))
PCA1<-PCA1 + ggtitle("Location Control")
PCA2<-plotPCA(vsdINT, intgroup=c("health"))
PCA2<-PCA2 + ggtitle("Intertidal")
PCA3<-plotPCA(vsdSUB, intgroup=c("health"))
PCA3<-PCA3 + ggtitle("Subtidal")

grid.arrange(PCA1,PCA2,PCA3, ncol=1)
```
  
**I found a [website](http://www.gettinggeneticsdone.com/2014/05/r-volcano-plots-to-visualize-rnaseq-microarray.html) that shows how to create volcano plots** with count data, which I was able to apply to this data set.     

```
## Volcano Plot- Full
#### I TRIMMED THE GENE NAME TO ONLY SHOW UNIQUE GENE ID WITHIN LONG NAME 
library(calibrate)
head(substr(row.names(resFULL), 9,21))
#### Add the shortened names to the results
resFULL$Gene<-substr(row.names(resFULL), 9,21) #Made a new column so I can label genes
head(resFULL)

with(resFULL, plot(log2FoldChange, -log10(padj), pch=20, main="Differential Gene Expression in Healthy versus SSWD Infected Sea Stars", xlim=c(-2.5,4),cex.main=1.8, cex.axis=1.5, cex.lab=1.5))
with(subset(resFULL, padj<.01 ), points(log2FoldChange, -log10(padj), pch=20, col="blue"))
with(subset(resFULL, abs(log2FoldChange)>1.5), points(log2FoldChange, -log10(padj), pch=20, col="orange"))
with(subset(resFULL, padj<.01 & abs(log2FoldChange)>1.5), points(log2FoldChange, -log10(padj), pch=20, col="red"))
## Add labels
with(subset(resFULL, padj<.000005 & abs(log2FoldChange)>2), textxy(log2FoldChange, -log10(padj), labs=Gene, cex=1.15))
```
Here is the [output](https://cloud.githubusercontent.com/assets/15003012/23735295/ae9d674e-0452-11e7-91b9-72bf08c656c4.png) from one of my earlier versions (later I substituted pvalue for adjusted p-value)   

------ <div id='id-section22'/>   

### Page 22: 2017-03-08 Effective Population Size and Substitution Rate Info Update   
   
### Rate of evolution due to the relationship of effective population size and the substitution rate (NeRR)   

Effective population size (Ne): 4 methods to measure
* Species life history - Ne = (4 * NmNf)/(Nm+Nf) with Nm number of males and Nf number of females   
* Variance in allele frequency between genome   
* Genetic polymorphous data   
* Correlated trait (like body size): correlate body size with effective pop size   

Ne varies across species and genome (genetic hitchhiking/selective sweeps; background selection; fewer sex chromosomes than autosomes - males contribute more mutations than females)   
These happen with no recombination:   
selective sweep - harmful mutations increase because beneficial mutations are selected for (and they are linked)   
background selection - beneficial mutations decrease because linked to harmful/deleterious mutations   

Mutations -      
* whole gene/chromosome: duplications; inversions; deletion; translocations (chunk of chromosome moves and attaches elsewhere)      
* base level: point mutation -> substitutions   
	+ Transitions (purine - purine; pyrimidine - pyrimidine)     
	+ Transversions (purine - pyrimidine; pyrimidine - purine)      
* Two types of point mutations   
	+ Synonymous - silent site -> DNA seq change, amino acid doesn't change; no selection (drift operates)   
	+ Non synonymous - replacement mutations -> DNA seq change, amino acid changes - selection operates   
		+ Purifying selection - reducing deleterious alleles    
		+ Positive selection - advancing beneficial alleles   
* Five mutation classes   
	+ Neutral: fitness effect (w) ~ 0, < 1/Ne; no selections; drift operates      
	+ Slightly deleterious: small effect on fitness; haploid 1/Ne; diploid 1/2Ne; selection and drift operate   
	+ Slightly advantageous: small effect on fitness; haploid 1/Ne; diploid 1/2Ne; selection and drift operate      
	+ Completely deleterious: big effect on fitness; > 1/Ne ; **negative** impact on NeRR; selection operates mainly  
	+ Completely advantageous: big effect on fitness > 1/Ne ; **positive** impact on NeRR; selection operates mainly   
* Variation in mutation rate (mu)   
	+ Generation time can influence it (short generation time -> higher mutation rate -> higher NeRR)   
	+ Selection reduces mutation rate (controversial!!! selection at species or individual level) -> lower NeRR    

NeRR and Linkage   
* Selective sweep (favors positive mutations but linked to negative)   
* Clonal interference - 2 individuals; each one has adaptive mutation; which mutation 'wins' and proceeds to next generation   

NeRR and Spatio temporal variation - may be variation across time and space     

NeRR and all mutation (perhaps U shape with Ne on x-axis)      

Fitness landscapes - optimal peaks of fitness for a given trait; populations near the 'peak' will have slower mutation rates than populations far from the peak      

### Take Home Messages   
* The study of NeRR helps us to uderstand the processes that drive and limit evolution   
* Drift and selection are the most important forces determining NeRR   
* We need to work on a better way to estimate Ne   
* With time, decrease in DNA seq costs will let us better estimate Ne, substitution rate, mutation rates   
* Most mutations are deleterious   

### Steve's input   

Theta = Ne * mutation rate   (2Ne * mu for diploid, hermaphroditic species; 4Ne * mu for diploid 2 sex organisms)   
πsyn ~ theta (nucleotide diversity on synonomous sites at most neutral sites estimates theta)   
**Ne = π/(4 * mu)**   
estimating mu: time (MY) since common ancestor (phylogenetic distance) can be looked at to see how many mutations per branch leading to species and convert to number of mutations per generation   





------ <div id='id-section23'/>   

### Page 23: 2017-03-08 Population Genomics Part 2 Tutorial   
   
[Link](https://adnguyen.github.io/2017_Ecological_Genomics/Tutorial/2017-03-08_Tutorials_PopGenomics2.html) to Tutorial   

### Using R to look at H-W data   
```
cd /data/project_data/snps/reads2snps/
vcftools --gzvcf SSW_byind.txt.vcf.gz --min-alleles 2 --max-alleles 2 --maf 0.02 --max-missing 0.8 --recode --out ~/SSW_all_biallelic_MAF_02_Miss_08  
gzip SSW_all_biallelic_MAF_02_Miss_08.recode.vcf.gz
vcftools --gzvcf SSW_all_biallelic_MAF_02_Miss_08.recode.vcf.gz --hardy
R
hwe<-read.table("out.hwe",header=TRUE)
head(hwe)
which(hwe$P_HET_DEFICIT<0.01)
#[1] 1001 1021 1023 1300 1302 1320 1407 1409
hwe[which(hwe$P_HET_DEFICIT<0.01),] ## prints the columns of all the rows that satisfy conditions (deficit p value < 0.01)   
hwe[which(hwe$P_HET_EXCESS<0.05),] ## excessive heterozygosity p<0.05
quit()
```
P_HET_DEFICIT - inbreeding   
P_HET_EXCESS - error in mapping/gene duplication (parology)   

### Using Terminal to look at diversity metrics
* Can look at allele frequency difference between sick and healthy!!   
* Make Sick.txt and Healthy.txt that lists samples; up to user to decide - do we put individuals that ever got sick into Sick.txt or divide by time points? 
* We will put SS and HS into Sick.txt and HH into Healthy.txt (leaving out MM)   

Let's grab a pre-made text file (ssw_healthloc.txt) that lists individual, sick type, location, and whether SNP data are available   
We can use >> to append new info to an existing txt file (add HS individuals to SS)
```
cd /data/project_data/snps/reads2snps/
cp ssw_healthloc.txt ~/mydata/
cd ~/mydata/
grep "HH" ssw_healthloc.txt > H_OneSampPerInd.txt
grep "SS" ssw_healthloc.txt > S_OneSampPerInd.txt
grep "HS" ssw_healthloc.txt >> S_OneSampPerInd.txt
```
vcftools just wants first column with sample ID and doesn't care about info, so we want to isolate the first column with cut   
We need to give it another name or nothing will be in the file   
```
cut -f 1 H_OneSampPerInd.txt > H_OneSampPerInd2.txt
cut -f 1 S_OneSampPerInd.txt > S_OneSampPerInd2.txt
```  
Now we want to calculate allele frequencies   
--keep says we want to determine frequencies of the subset we made in txt files   
```
vcftools --gzvcf SSW_all_biallelic_MAF_02_Miss_08.recode.vcf.gz --freq2 --keep H_OneSampPerInd2.txt --out H_AlleleFreqs   
vcftools --gzvcf SSW_all_biallelic_MAF_02_Miss_08.recode.vcf.gz --freq2 --keep S_OneSampPerInd2.txt --out S_AlleleFreqs   
```
Fst between Healthy and sick   
```
vcftools --gzvcf SSW_all_biallelic_MAF_02_Miss_08.recode.vcf.gz --weir-fst-pop H_OneSampPerInd2.txt --weir-fst-pop S_OneSampPerInd2.txt --out HvS_OneSampPerInd
```

Bringing our allele data into R
```
R
Salleles<-read.table("S_AlleleFreqs.frq", header=T)
Halleles<-read.table("H_AlleleFreqs.frq",header=T)
BothAlleles<-merge(Salleles,Halleles,by="CHROM")
Diffs<-BothAlleles$MAJOR.x - BothAlleles$MAJOR.y
```
Following the tutorial to make histogram with Fst data   
```
fst <- read.table("HvS_OneSampPerInd.weir.fst",header=T)
pdf("HvS_Fst.pdf")
hist(fst$WEIR_AND_COCKERHAM_FST, breaks=20, col="red")
dev.off()
```
I brought the pdf to my local computer to look at it and converted it to a jpg.   
[Histogram Output](https://cloud.githubusercontent.com/assets/15003012/23715108/88e319d0-03f9-11e7-849e-815f1e35cbfe.jpg)   


------      
<div id='id-section24'/>   

### Page 24: 2017-03-20. Bill Kilpatrick's Info Update   
   
### Glossary:   
* Global ancestry (GA) - estimated proportion of ancestry contributed by different populations averaged across genome   
* Local ancestry (LA) - each chromosome is a mosaic of segments from different ancestral populations - goal is to identify population of origin each position (i.e. neanderthal and recent human chromosome comparisons)   
* Hidden Markov Model (HMM) - statistical model; assumes Markov processes with unobserved states   
   
**Methods for Global Ancestry:**   
Model based:
* STRUCTURE - Bayesian approach to use model to designate clusters/populations/ancestry and allelic frequencies associated with populations (using H-W equilibrium and linkage equilibrium)   
* AdMIXTURE - maximum likelihood to use same mode as STRUCTURE   

Non-parametric approaches (multivariate analyses):   
* clustering - using pair wise data matrix (distances or similarities, etc); produce phenograms (look like trees) based on overall similarity   
* ordination - PCA, multiscale dimensioning   

**Methods for Local Ancestry:**   
admixed populations - every individual is going to be a combination of genes; goal is to recover haplotypes from each of the ancestral populations; Very accurate if 2 source populations, but lose accuracy if there are 3; 4 or 5 and there is very low reliability   
* Hidden Markov model (HMM) - fit probablistic model to data by modeling joint dependency of alleles and ancestry and uses Bayes' Rule to estimate probability of ancestry by looking at allele configuration   
* STRUCTURE doesn't model linkage equilibrium so major drawback   
* LAMP uses sliding window of genome (uses blocks of genome) and assigns ancestral populations by PCA; fast and doesn't lose accuracy 
* RFMis uses discriminant analysis to take multivariate data and use loading factors for various characters (haplotypes) to maximize separation; very fast, doesn't lose accuracy   
   

**Weaknesses of Methods**    
* Assumes we know k (number of ancestral populations) and their allele frequencies; we usually don't know or they are inaccurate   
* We can do simulations - sig impact on ancestry if you have misinformation about k and allele frequencies (esp closely related ancestral populations; recent admixture)   

**Applications of GA and LA inference**   
* stratification/population structure - sub populations in seemingly homogeneous populations; DNA profiling, forensics - proportion of population that also has DNA profile?    
* GA: evolutionary studies for structuring (subpopulations of endangered species?), objectiveley define what population is, population assignment, assignment of immigrants   
* LA: medicine, mapping genes to diseases by admixture mapping, pharmacogenomics, localize sequences that haven't been determined where they belong in reference so can map with LA; disease-linked genes and variance of those genes   

**Future work and challenges**   
* Genomics will produce denser mapping of SNPs for much larger sample sizes   
* Refinement of current methods and new technologies will follow (more reliable for studies)      
* Improve modeling of linkage disequilibrium to model ancestry   

### Watterson's theta vs pi   
- bottleneck - lose rare alleles to drift but avg heterozygosity stays high (sites with bars higher than points)   
- watterson's theta - similar to species richness   
- pi (heterozygosity) - similar to species evenness    



------    

<div id='id-section25'/>     

### Page 25: 2017-03-20. Population Genomics Part 3 Tutorial      

1) Final VCF data (n=24)-> Filter -> Output to Home Directory      
2) Estimate Healthy and Sick alleles -> f(H) - f(S)   
3) Fst between H vs S -> output to local machine -> plot R -> estimate pi at synonymous sites, nonsynonymous sites, and nonsyn/syn  -> output to local machine -> compare to Romiguier paper    

### Finishing allele frequency and diversity calculations     

**Parsing out data in Terminal from txt file that has individual numbers**   

```UNIX
cd ~/mydata/
grep "HH" ssw_healthloc.txt | cut -f1 >H_SampleIDs.txt

wc H_SampleIDs.txt 
## 8  8 24 H_SampleIDs.txt ##this is the output; gives dimension
```

**To get both versions of sick individuals (HS and SS) we use this code**   

```UNIX  
grep "HS\|SS" ssw_healthloc.txt | cut -f1 >S_SampleIDs.txt
```    

**Download Fetch or Cyber Duck for easy file transfer from Terminal to computer**   

**Can pick out which genes have high allelic differences**      

```UNIX
All_freq[which(abs(All_freq$diff)>0.35),] ### gives which ones have high allele frequency differences (both negative and positive)
```    

------      

<div id='id-section26'/>  

### Page 26: 2017-03-22. Population Genomics Part 4 (Finishing heterozygosity estimates and PCA)   

πs =   0.00585312 [0.005172; 0.006598]   
πn/πs = 0.264041 [0.223914; 0.310575]   


------   <div id='id-section27'/>  

### Page 27: 2017-03-27. Selective sweep info update (Allison)      
**sweep**: pattern whereby a single adaptive allele "sweeps" through populations (goes to fixation or nearly so)   
**hard sweep**: single adaptive allele in common genetic background (sharp decrease of genetic diversity)   
**soft sweep**: more than one adaptive allele in different genetic backgrounds (slight decrease of genetic diversity; shallower slope)  
Ex: for soft sweep; several alleles can be resistant to HIV (phylogenetic tree has different resistant alleles for each monophyletic group)   

Pleuni Pennings - Stanford University; has students create videos on papers published   

Sweeps increase frequency of allele and hitchhiking (closely linked) genes within population   
- can be hard on a local scale and soft on a global scale (i.e. lactose tolerance selected for in two different areas)   

theta - rate at which mutation enters a population   
theta = 2Ne * mu   
- fitness effects and population size affect theta   

alternative hypotheses to selective sweeps:    
- genetic drift is causing allelic differences   
- no functional differences    
- cause and effect? was selection operating before selective event?   



------   

<div id='id-section28'/>   

### Page 28: 2017-03-29. Detecting local adaptation info update (Lauren Ashlock)   

Local adaptation (i.e. sea stars adapted to disease in a particular location)      

Different approaches:   

* genetic - environment association analyse   
* differentiation outlier method (Fst)   

Challenges:   

* Confounding factors   
- demographic history   
- neutral population structure   
- background selection   
* Missing genome   
- reduced representation   
- missing structural variants in reference   
- loss of repetitive regions/paralogs   
* Missing landscape   
- low resolution environmental data   
- scale of local adaptation   
- multi colinearity (i.e. if temperature is related to disease prevalence)      

Solutions:    

* Confounding factors   
- null demographic models   
- relatedness among samples   
* Missing genome   
- exome capture or RNA-seq   
- whole genome sequencing (create de novo)   
- sufficient depth of coverage   
* Missing landscape   
- know system   
* Other considerations   
- sampling strategy   
+ number of individuals   
+ paired sampling   
- multiple comparisons   
+ sliding window (instead of all at once)   
+ establish FDR (false discovery rate)  
- genomic architecture   
* Final notes   
- pair with ecological, functional studies; experimental studies   

Ideal pH study:   
paired populations of low to high pH across latitude     

### Population Genomics Tutorial 4   
dataset of i individuals @ j SNPs   
-> Pr(Genotypes | K, Q, P)      
K = # groups   
Q = ancestry (proportion of an individual's genome)   
P = allele frequencies at each SNP in each K population   
Genotype matrix 24 individuals x 5,317 SNPs   
Divides individuals into chunks, masks one group, uses unmasked individuals as 'train' data, and use masked group as 'test' data (cross validation); best K is lowest cross-validation score   


Admixture does it all within a maximum likelihood model, not bayesian   
Fast, but does not differential support for different models (which number of K is best)   


For our own research, we won't have to change .spid file except defining populations:    
#### Select population definition file:   
VCF_PARSER_POP_FILE_QUESTION=./SSW_tidal.pops     
and making sure file output format is correct:    
#### EIGENSOFT Writer questions   
WRITER_FORMAT=EIGENSOFT   

bash scripts always begin with:   
```   
#!/bin/bash
```   
Changed vcf2geno.sh file to:   
```
java -Xmx512M -jar /data/popgen/PGDSpider_2.0.9.0/PGDSpider2-cli.jar -inputfile ./SSW_all_biallelic.MAF0.02.Miss0.8.recode.vcf -inputformat VCF -outputfile ./SSW_all_biallelic.MAF0.02.Miss0.8.recode.vcf.geno -outputformat EIGENSOFT -spid ./vcf2admixture_SSW.spid
```
**FOR LOOPS** IN TERMINAL LOOK LIKE:   
```
for K in {1..10}

do

admixture -C 0.000001 --cv ./SSW_all_biallelic.MAF0.02.Miss1.0.recode.vcf.geno $K \
| tee log${K}.out

done

# After the for loop finishes, you can use 'grep' to grab the values of the CV from each separate log file and append them into a new summary text file.

grep CV log*.out >chooseK.txt
```
-C in admixture function; at each iteration, climb up to peak of likelihood - which point can you stop?   
--cv applies cross validation   
| sends info to log file

------ <div id='id-section29'/> 

### Page 29: 2017-04-03. Karl Fetter Guest Lecture: Fst; outliers   

Outline      
* Inbreeding produces structured populations   
* Selective sweeps change allele frequencies in populations   
* empirical p-values created from distributions of putatively neutral loci are super useful for finding natural selection   
* methods from Whitlock and Lauterhouse called OutFlank (2015)

Questions:   
* What challenges do outlier detection methods face?   
* How is linkage disequilibrium (LD) our friend and foe for finding loci under selection?   

structured population: change in allele frequency from one population to another   

F-statistics: created by Sewell Wright; 0 to 1 (1=completely inbred; structured)      
H - Heterozygosity
I - individual   
S - subpopulation
T - total 
probability that two alleles sampled from individuals are identical by descent   

F = inbreeding coefficient   
Fst = (Heterozygosity of total - heterozyg of subpopulation) / total heterozyg   
Fis = (expected(Hs) - Obs(Hs))/expected(Hs)   
Fit = (Ht - Hi)/Ht   

Vw (within population genetic variance) - on plot of genetic variation (y) as function of Fst (x) - quadratic curve     
Vb (regional diversity) -   plot almost linear (high genetic variance with F=1; metapopulations are inbred but distinct from each other)   
Vt (Fst) - exponential and then plateaus   

LD shows an adaptive allele present in every individual which helps, but if adaptive allele has neutral 'hitchhikers' can' tell the two apart   

neutral locations - intergenic loci (between genes; noncoding regions; contain promoters and regulatory regions though)   
frequency (y) to chi-squared (x) plot: neutral distribution and non-neutral distribution, look at tail extremes to find loci under spatial heterogeneous selection (diversifying selection on tails; stabilizing selection in center of distribution is what they want), remove extremes, recalculate distribution, plot tail distribution on top of recalculated distribution; in the dist that include extremes, the Fst's that exceed the recalculated distribution with no extremes are deemed significant   

### R script for Fst analysis   

```{r}
### Install packages  
library(devtools)
source("http://bioconductor.org/biocLite.R")
biocLite("qvalue")
install_github("whitlock/OutFLANK") 
library(OutFLANK)
library(vcfR)
library(adegenet)

### Read in your .geno file. OutFlank requires it to be transposed, so we'll do that next 
sswgeno_in<- read.fwf("SSW_all_biallelic.MAF0.02.Miss0.8.recode.vcf.geno", width=rep(1,24))
sswgeno<-t(sswgeno_in)
dim(sswgeno)

## Read in metadata
ssw_meta<-read.table("ssw_healthloc.txt",T) 
ssw_meta<-ssw_meta[order(ssw_meta$Individual),] #reorder meta data by Ind number
ssw_meta$Trajectory[which(ssw_meta$Trajectory == 'MM')] = NA # remove MMs from analysis


### Using OutFLANK

OF_SNPs <- MakeDiploidFSTMat(SNPmat = sswgeno, locusNames = seq(from= 1,to =5317, by=1), popNames = ssw_meta$Trajectory)
head(OF_SNPs)
OF_out <- OutFLANK(FstDataFrame = OF_SNPs, LeftTrimFraction = 0.05, RightTrimFraction = 0.05, Hmin=0.1, NumberOfSamples =  3, qthreshold = 0.1) ## takes Fst data to find outliers using trimmed likelihood approach
OutFLANKResultsPlotter(OFoutput=OF_out, withOutliers = T, NoCorr = T, Hmin=0.1, binwidth = 0.005, titletext = "Scan for local selection")
outliers<-which(OF_out$results$OutlierFlag=="TRUE")   

### We can extract info about the outliers by reading in the vcf file and looking at the annotations   
vcf1<- read.vcfR("SSW_all_biallelic.MAF0.02.Miss0.8.recode.vcf")
dim(vcf1)
vcfann <- as.data.frame(getFIX(vcf1)) #getFIX gets annotations   
vcfann[outliers,]
```

Then go to terminal: 
```{UNIX}
vim /data/project_data/assembly/08-11-35-36_cl20_longest_orfs_gene.cds
```
we can use the gene IDs (i.e. DN46509); match gene ID using (/DN46509), copy sequence into [BlastX](https://blast.ncbi.nlm.nih.gov/Blast.cgi)   




------ <div id='id-section30'/>

### Page 30: 2017-04-04. **Homework 3: Population genomic diversity and structure**  


Original output (done with class):   

```{UNIX}
Parameters as interpreted:
	--gzvcf SSW_by24inds.txt.vcf.gz
	--maf 0.02
	--max-alleles 2
	--min-alleles 2
	--max-missing 0.8
	--out /users/l/v/lvash/SSW_original
	--recode

Using zlib version: 1.2.7
After filtering, kept 24 out of 24 Individuals
Outputting VCF file...
After filtering, kept 5317 out of a possible 7486938 Sites
```
### Changing maf to 0.05 decreases sites retained:   

```
vcftools --gzvcf SSW_by24inds.txt.vcf.gz --min-alleles 2 --max-alleles 2 --maf 0.05 --max-missing 0.8 --recode --out ~/hw2/SSW_maf0.05
Parameters as interpreted:
	--gzvcf SSW_by24inds.txt.vcf.gz
	--maf 0.05
	--max-alleles 2
	--min-alleles 2
	--max-missing 0.8
	--out /users/l/v/lvash/SSW_all_biallelic.MAF0.05.Miss0.8
	--recode

Using zlib version: 1.2.7
After filtering, kept 24 out of 24 Individuals
Outputting VCF file...
After filtering, kept 1899 out of a possible 7486938 Sites
```

### I tried increasing max-missing option to 1 but it drastically reduced sites retained:   

```
vcftools --gzvcf SSW_by24inds.txt.vcf.gz --min-alleles 2 --max-alleles 2 --maf 0.05 --max-missing 1 --recode --out ~/hw2/max-missing1

Parameters as interpreted:
	--gzvcf SSW_by24inds.txt.vcf.gz
	--maf 0.05
	--max-alleles 2
	--min-alleles 2
	--max-missing 1
	--out /users/l/v/lvash/hw2/SSW_exclude_MM
	--recode

Using zlib version: 1.2.7
After filtering, kept 24 out of 24 Individuals
Outputting VCF file...
After filtering, kept 414 out of a possible 7486938 Sites
```

### I am removing MM from the analysis which results in more sites (less than 100 though) being retained :   

```
vcftools --gzvcf SSW_by24inds.txt.vcf.gz --min-alleles 2 --max-alleles 2 --maf 0.05 --max-missing 0.8 --remove MM_SampleIDs.txt --recode --out ~/hw2/SSW_exclude_MM

Parameters as interpreted:
	--gzvcf SSW_by24inds.txt.vcf.gz
	--exclude MM_SampleIDs.txt
	--maf 0.05
	--max-alleles 2
	--min-alleles 2
	--max-missing 0.8
	--out /users/l/v/lvash/hw2/SSW_exclude_MM
	--recode

Using zlib version: 1.2.7
Excluding individuals in 'exclude' list
After filtering, kept 22 out of 24 Individuals
Outputting VCF file...
After filtering, kept 2071 out of a possible 7486938 Sites

```
### Calculating Fst   
For my "maf 0.05" all individuals filter:   
```
vcftools --vcf SSW_maf0.05.recode.vcf --weir-fst-pop H_SampleIDs.txt --weir-fst-pop S_SampleIDs.txt --weir-fst-pop MM_SampleIDs.txt --out HvS_Fst_maf05
Weir and Cockerham mean Fst estimate: -0.00073739
Weir and Cockerham weighted Fst estimate: 0.00065228
```
For my "exclude MM" filter:   
```
vcftools --vcf SSW_exclude_MM.recode.vcf --weir-fst-pop H_SampleIDs.txt --weir-fst-pop S_SampleIDs.txt --out HvS_Fst_exclMM
Weir and Cockerham mean Fst estimate: -0.0022304
Weir and Cockerham weighted Fst estimate: -0.00023857
```

------ <div id='id-section31'/>

### Page 31: 2017-04-05. Melissa's Info update: Annotation/Enrichment      

Processing raw data: file types: .fastq ; programs: Trimmomatic   
transcriptome assembly: file types: .fasta ; programs: Trinity   
annotation (file type: .fasta; program: BLAST) OR map reads (file types: .sam ; program: BWA)   

map reads -> differential gene expression analysis (file: counts table; program: DESeq2) or population genomics (file: .vcf; program: PCA, DAPC, ADMIXTURE)   

Output: Log fold change, pvalue, stats (DGE); Fst, DAPC/PCA loadings (pop genom); **but what is biological function and does it match our predictions?** -> functional enrichment analyses (use results from DGE, Fst, and use program called GO Mann-Whitney U made by Dixon et al. paper using lots of file types)         

#### Annotation   
* BLAST2GO (pay for it) - upload fasta file and spits out gene name and best hits   
* use "Brute Force" where you do everything yourself    
* somewhere in between using pipelines created from other people (Trinotate)   

* Start with .fasta file that has your genes -> databases     
* Use program (BLAST): gives e-value (lower is better like pval; 10^-2 less stringent to 10^-50 more stringent), bit score (bigger is better), % identity and length (bigger better)     
	+ blastp (query/assembly/.fasta: .pep (amino acid AA); subject/database/.db: .pep)    
	+ blastx (query: .csd (nucleotide) ->blasts 6x ; subject: .pep (takes longer, but if unsure about AA, better match)   
* another program named DIAMOND   
	+ UniProt - protein (every protein associated with functional terms: Gene Ontology, Kegg Pathways, Protein domains)   
* databases: NCBIs, NR (non-redundant; protein)   



------ <div id='id-section32'/>   

### Page 32: 2017-04-05. Gene Annotation Tutorial   

Fisher's Exact Test   

| 		| non-DEG 	| DEG 	|   
| ------------- |:-------------:| -----:|
| not in GO:X 	| 1800 		| 200 	|   
| GO:X 		| 50 		| 50	|

10% DEG but not in GO category   
50% DEG in GO category (significant! 5x)    


OR compare distributions of metric (Fst, Fstat, pval) with those in immune response category (for example) to metrics of those not in category   

### [Annotation Tutorial](https://adnguyen.github.io/2017_Ecological_Genomics/Tutorial/2017-04-05_annotation_tutorial3.html)   




------ <div id='id-section33'/>

### Page 33: 2017-04-08. Paper Discussion prep: "Bacterial community dynamics are linked to patterns of coral heat tolerance"   

## Study system:   
*Acropora hyacinthus*   
Ofu Island, American Samoa   
**Two locations**: highly variable (**HV**) pool and moderately variable (**MV**) pool which had different thermal environments      

### What makes it a good system?   
1. Thermally distinct environments allow to expore effects of environment without confounding factor of site   
2. Thermally sensitive, wide-spread species   
3. Previous studies showed difference in algal symbiont communities in different thermal environments; although bleached irrespective of symbiont type         
4. That study showed strong acclimatization after reciprocal transplant so suggested involvement of associated microbes or other symbionts      
5. Recent work has shown strong association of coral colonies with species-specific bacterial communities     

This study **investigated the bacterial community composition and its potential role in contributing to thermal resistance of the coral holobiont.**   

1. Conducted long-term reciprocal transplant (17 months)   
2. Heat-stress experiment   

## Main Results:   

### **Coral microbiomes differ with thermal habitats (Figure 1d)**   
Ex: Rhodospirillaceae accounted for 15% of total family abundance in HV pools but less than 2% in MV pools   

### **Coral microbiomes adapt to thermal habitats**   
1. The microbiomes of non-native corals that were transplanted **could not be distinguished** from the microbiomes of native corals in same pool (Figure 1c; different shapes, same color)      
2. The **cross-transplanted fragments were significantly different from back-transplanted** counterparts (Figure 1c; same shapes, different colors)   
3. Lack of covariance between coral genotype and microbiome composition (argues against heritable microbial component)   

### **Microbiome dynamics are linked to coral heat tolerance**   
Short term bleaching experiment mimicked natural temperature variation in HV pool during summer noon low tides that cause bleaching   
1. MV pools: microbiomes signicantly affected after 20h and significant bleaching   
2. HV pools: microbiome communities remained stable (no sig. response compared to control) and bleached less   

### **Microbial functional profiles change with thermal habitat**   
Used predictive metagenomic analysis: Phylogenetic Investigation of Communities by Reconstruction of Unobserved States (PICRUSt)   
1. 128 functional traits and 28 proteins distinguished microbial communities between HV and MV pools   
2. HV coral microbiomes characterized by enrichment of functions related to metabolism and carbohydrate transport   
3. Only 3 functions enriched in MV coral microbiomes   

**Functional profile Discussion**: enzyme Fucose has been shown to undergo largest increase of carbs in coral mucus under heat stress and was enriched in HV; carb transport and metabolism under strong regulation in *Streptococcus mutans* (bacterium associated with tooth decay) to cope with heat stress; **data support a functional restructuring of the microbial metabolic network in stress-resistant corals**          

### **Bacterial taxa as indicators of coral heat tolerance**   
Analyzed data for the presence of candidate indicator taxa that characterize unchanged microbiome of corals in HV pool   
1. HV pool: characterized by consistent set of microbial taxa across all control/heat treatments; **2/3 belonged to Alphaproteobacteria (rarely present in MV pools)**   
2. 20h heat-stressed samples compared to all other treatment groups revealed HV microbial communities had no distinct bacterial indicator taxa    
3. MV pool had 10 indicator OTUs that were characteristic of heat-induced microbial shift (**Gammaproteobacteria and Saprospirae**)   
4. Functional microbial profiles also encoded by different bacterial classes   

**Indicator taxa Discussion**: 
* unchanged **HV bacteria represent spatially explicit bacteria hypothesized to fulfill functional niches** (may contribute to resilience)   
* **MV heat-associated changes** in microbiome characterized by bacterial taxa previously recorded in **diseased/stressed marine organisms**   
* Alphaproteobacteria were responsible for large fraction of functional enrichment in HV pool; Family Rhodospirillaceae and genus *Inquilinus* most prevalent   
* Gammaproteobacteria associated with more than half of bacterial funtional traits in MV pool; *Glaciecola* - occurrence in polar regions and cold adaptation of genomes; third family Vibrionaceae contributed to functional profile (*Vibrio shilonii* associated with coral bleaching)         


**Experimental replacement of obligate symbionts from HV corals to MV corals with demonstration of acquired heat tolerance would demonstrate effect of host-associated bacteria on host ecology**   



------ <div id='id-section34'/>

### Page 34: 2017-04-08. Microbiome: Steve's info update and Melanie's coding session    

RNA (sea stars)   -- Amplicon-Seq (16S) - what microbes are present? what are they doing? (metagenomics)    
|
RNA-seq: what genes are being expressed (transcriptomics)? Diversity and structure of sample; evidence for selection? (population genomics)?   

### Microbiome vs metagenome   

Microbiome: assemblage of microbial taxa associated with host/environment   
* pathogens   
* symbionts (mutualists; commensalists)   
host and microbiome form holobiont   
(who is there?)

how do you measure microbiome?    
1) Amplicon-Seq: 16S rRNA (DNA gene that codes for RNA)   
single-strand RNA forms hairpin loops; loops are more variable because elsewhere, hydrogen bonds are formed in close quarters   
2) Internal transcribed spacer (ITS)   
subunits of ribosomal RNA: 18S ---- 5.8S ----- 28S (--- are ITS1 and ITS2; non-coding so more variable)   

Metagenomics: genes being expressed by microbiome; combined community level expression of genes   
what are they doing? (function)   

how do you measure metagenomics?   
RNA-Seq or Shot-gun DNA-seq   

Processing:   
* Sample tissue; extract your DNA/RNA   
* PCR target gene - use primers (16S - eukaryotes don't have 16S subunit; target bacteria and Archaea)      
* Barcode amplified fragments, so after sequencing in pool, separate out   
* Assign distance threshold (cluster sequences based on similarity - usually 97%) - OTUs   
* Blast OTUs to database to determine taxonomy   

#### Microbial Revolution    
* Most microbes are culturable; didn't know true diversity until sequencing    

### Big Questions   
Is there a 'core' microbiome shared in common among many organisms?   
How much diversity is unique to individuals, populations, and communities? (is it heritable?)   
Does microbiome evolve under different contexts? -> adaptation of host to environment?!?      
Can knowledge of microbiomes predict a response to env. selection?    


### BIOME TABLE SUMMARY   

Num samples: 176
Num observations: 93033
Total count: 8362869
Table density (fraction of non-zero values): 0.028

```
Counts/sample summary:
 Min: 28412.0
 Max: 77866.0
 Median: 47051.500
 Mean: 47516.301
 Std. dev.: 7637.541
 Sample Metadata Categories: None provided
 Observation Metadata Categories: taxonomy
 ```
 

------ <div id='id-section35'/> 

### Page 35: 2017-04-12. Host genetic associations with the microbiome   

Microbiome is beneficial (digestive, immune, vitamins, disease resistance) and potentially heritable   

heritability (*not inheritance*) - the proportion of variance in a host trait, measured across populations, and explained by genetics (not environmental) directly (ex: twin pairs) or genome wide association studies (GWAS)   

GWAS - studied in humans   
- microbiome ~ "traits"   
- used SNP data from host   
- 16S rRNA from microbiome   
Ex: Hutterites: 15 heritable taxa; seasonal (olfactory receptor genes)   

Cross study comparisons   
- mice: QTL studies; immune functions   
- plants: QTL; genotypic effects of species richness of microbiome and abundance of indiv. taxa   
- flies: GWAS; barrier defense (digestive) and immunity   

Limitations   
- costly   
- small N -> decreases power of results   
- lacking microbial taxa   
- meta analyses did not find signficant results (studies too different)   

To increase power -> increase sample size and unify sample sequencing and analysis   





------ <div id='id-section36'/> 

### Page 36:  2017-04-19. Alex's Info Update

**Rarefying microbiome data is NOT acceptable**   

Rarefying vs rarefaction    

**Glossary**   
rarefaction - estimating species richness based on number of samples from each group (extrapolation)     
rarefying - normalization of data using lowest N (random subsampling without replacement)   
heteroskedasticity - variability of a variable changes along another predictor variable     
power: probability of rejecting a false null hypothesis      
type I error: reject Ho whent it is TRUE   
type II error: failt to reject Ho when FALSE      
   
**Past methods**  
- proportions: of individal OTUs over total observed OTUs found      
	+ high rate of false positives   
	+ heteroskedasticity   
	+ reduced statistical power (lose sample size)      
- rarefying   
	+ steps - find smallest N (N<sub>Lmin</sub>), discard libraries with fewer than N<sub>Lmin</sub>, subsample reads from larger Ns without replacement   
	+ what this does: normalizes data; removes discrepencies in number of reads    
	+ problems: high rate of false positives; requires omission of data; reduces statistical power         

**Mixture models (recommended)**    
- combines two distributions (i.e. binomial with zero-inflated Gaussian/Normal)     
- does not cut down N, so does not decrease power and increase accuracy   
- allows libraries of different lengths and accounts for biological variability   
- edgeR; DESeq; phyloseq for mixture models   


### Trouble with biom package install   
1) Had to download [archived version](https://cran.r-project.org/src/contrib/Archive/biom/)   
2) Installed dependency package: RJSONIO in R
3) Terminal: R CMD INSTALL packagename.tar.gz   

### Then had to convert metagenome_predictions.L3.biom file to json format (used json file in R script)  

```
biom convert -i metagenome_predictions.L3.biom -o metagenome_predictions_json.biom --table-type="OTU table" --to-json
```

------ <div id='id-section37'/>

### Page 37: 2017-05-08 **Final Project R Code**   

```{R}   
###########################################################################################
# Lauren Ash and P. Alexander Burnham
# May 8, 2017
# Ecological Genomics
# Team Sherlock Data Analysis
###########################################################################################

# Preliminaries:
# Clear memory of characters:
ls()
rm(list=ls())

# set working directory: (files are in /RawData)
setwd("/Users/lvash/Desktop/UVM/Courses/Ecological_Genomics")
set.seed(100)
###########################################################################################
# load packages
library(plyr)
library(ggplot2)

###########################################################################################
# Lauren and Alex's DESeq and randomization code:
# subsetting data:

library(DESeq2)

### Subsetting data
conds <- read.delim("cols_data_trim.txt", header=TRUE, stringsAsFactors=TRUE, row.names=1, sep="")
colData1 <- as.data.frame(conds)
colDataDay6<-subset(colData1, colData1$day=="day06")
colDataDay6
colData<-subset(colDataDay6, colDataDay6$indiv != "37")
colData # 7 sick # 11 healthy
# Day 15 H: 10, 24, 27, 31, 33, 34
# Day 15 S: 8, 9, 15, 19, 20, 23
## no 7, 22 (sick) in day 6
#sample log2foldchange of 279 genes with replacement - calculate average 10000 times to generate distribution; which proportion are sig on their own


colDataDay15<-subset(colData1, colData1$day=="day15")
colDataDay15
countsTable <- read.delim('countsdata_trim2.txt', header=TRUE, stringsAsFactors=TRUE, row.names=1)
countData <- as.matrix(countsTable)
countData<-countData[, which(colnames(countData) %in% row.names(colData))]

## DESeq Model: Day 6, no MMs, 18 individuals (7 sick, 11 healthy); model with location and health 
library(DESeq2)
ddsFULL <- DESeqDataSetFromMatrix(countData = countData, colData = colData, design = ~ location + health)

ddsFULL <- ddsFULL[ rowSums(counts(ddsFULL)) > 100, ]

colData(ddsFULL)$health <- factor(colData(ddsFULL)$health, levels=c("H","S"))

ddsFULL <- DESeq(ddsFULL)
resFULL <- results(ddsFULL)
resFULL <- resFULL[order(resFULL$padj),] #sorts according to pvalue
head(resFULL)
summary(resFULL)
names(resFULL)

###########################################################################################
# Reading in Data for each group of genes:


### reading in list of immune related genes (269/final 254)
immuneNames <- read.delim("immune.txt", header=TRUE, stringsAsFactors=FALSE, row.names=1)
row.names(immuneNames) <- immuneNames$trinID
immuneRes<-resFULL[which(row.names(resFULL) %in% row.names(immuneNames)),]
dim(immuneRes) # 254 matched -  less than 321 because of low read counts

#--------------------------------------------------------------------------------------------

### Reading in stress related genes (276/ final 271)
stressNames <- read.delim("Pisaster_stress.txt", header=TRUE, stringsAsFactors=FALSE, row.names=1)
row.names(stressNames) <- stressNames$trinID
stressRes<-resFULL[which(row.names(resFULL) %in% row.names(stressNames)),]
dim(stressRes) 

#--------------------------------------------------------------------------------------------

### Reading in virus related genes (325/final 323)
virusNames <- read.delim("virus.txt", header=TRUE, stringsAsFactors=FALSE, row.names=1)
row.names(virusNames) <- virusNames$trinID
virusRes<-resFULL[which(row.names(resFULL) %in% row.names(virusNames)),]
dim(virusRes) 

#--------------------------------------------------------------------------------------------

### Reading in bacteria related genes (1320/final 1299)
bacteriaNames <- read.delim("bacteria.txt", header=TRUE, stringsAsFactors=FALSE, row.names=1)
row.names(bacteriaNames) <- bacteriaNames$trinID
bacteriaRes<-resFULL[which(row.names(resFULL) %in% row.names(bacteriaNames)),]
dim(bacteriaRes)


###########################################################################################
# Random distribution of full data set 
# set parameters to original
oPar <- par(no.readonly=TRUE)

par(mfrow=c(1,4))
par(mar=c(1,1,1,1))

### IMMUNE

# Immune Random null distribution
logfoldrandoMean0 <- vector(mode="numeric")
for(i in 1:10000){
    logfoldrando0<-vector(mode='numeric')
    logfoldrando0 <- sample(x=resFULL$log2FoldChange, size=dim(immuneRes)[1], replace=T)
    logfoldrandoMean0[i]<-mean(logfoldrando0)
}

## Histogram immune
hist(logfoldrandoMean0, 
     breaks=50, 
     main="IMMUNE GENES",
     xlab=NULL,
     ylim=c(0,800),
     xlim=c(-.3, .15),
     cex.axis=1,
     cex.lab=1.2,
     font.lab=2 
)

Interval0 <- quantile(x=logfoldrandoMean0, probs=c(0.025,0.975))
abline(v = Interval0,col="black",lwd=2,lty="dotted")
abline(v=mean(immuneRes$log2FoldChange), col="red",lwd=2)
t.test(x=logfoldrandoMean0, y=immuneRes$log2FoldChange) #pvalue 0.1403

#--------------------------------------------------------------------------------------------

### STRESS (271)

# Stress Random null distribution
logfoldrandoMean1 <- vector(mode="numeric")
for(i in 1:10000){
    logfoldrando1<-vector(mode='numeric')
    logfoldrando1 <- sample(x=resFULL$log2FoldChange, size=dim(stressRes)[1], replace=T)
    logfoldrandoMean1[i]<-mean(logfoldrando1)
}

## Histogram - stress
hist(logfoldrandoMean1, 
     breaks=70, 
     main="STRESS GENES",
     xlab=NULL,
     ylim=c(0,800),
     xlim=c(-.3, .15),
     cex.axis=1,
     cex.lab=1.2,
     font.lab=2 
)

Interval1 <- quantile(x=logfoldrandoMean1, probs=c(0.025,0.975))
abline(v = Interval1,col="black",lwd=2,lty="dotted")
abline(v=mean(stressRes$log2FoldChange), col="red",lwd=2)
t.test(x=logfoldrandoMean1, y=stressRes$log2FoldChange, alternative="two.sided") #p-value = 0.05001
#--------------------------------------------------------------------------------------------

### VIRUS

# Stress Random null distribution
logfoldrandoMean2 <- vector(mode="numeric")
for(i in 1:10000){
    logfoldrando2<-vector(mode='numeric')
    logfoldrando2 <- sample(x=resFULL$log2FoldChange, size=dim(virusRes)[1], replace=T)
    logfoldrandoMean2[i]<-mean(logfoldrando2)
}

## Histogram - virus
hist(logfoldrandoMean2,
     breaks=50,
     main="VIRUS GENES",
     xlab="log(fold change)",
     ylim=c(0,900),
     xlim=c(-.3, .15),
     cex.axis=1,
     cex.lab=1.2,
     font.lab=2 
)

Interval2 <- quantile(x=logfoldrandoMean2, probs=c(0.025,0.975))
abline(v = Interval2,col="black",lwd=2,lty="dotted")
abline(v=mean(virusRes$log2FoldChange), col="red",lwd=2)
t.test(x=logfoldrandoMean2, y=virusRes$log2FoldChange) #p-value = 0.5967
#--------------------------------------------------------------------------------------------


### BACTERIA

# Stress Random null distribution
logfoldrandoMean3 <- vector(mode="numeric")
for(i in 1:10000){
    logfoldrando3<-vector(mode='numeric')
    logfoldrando3 <- sample(x=resFULL$log2FoldChange, size=dim(bacteriaRes)[1], replace=T)
    logfoldrandoMean3[i]<-mean(logfoldrando3)
}

## Histogram - bacteria
hist(logfoldrandoMean3, 
     breaks=50,
     main="BACTERIA GENES",
     xlab="log(fold change)",
     ylim=c(0,900),
     xlim=c(-.3, .15),
     cex.axis=1,
     cex.lab=1.2,
     font.lab=2) 


Interval3 <- quantile(x=logfoldrandoMean3, probs=c(0.025,0.975))
abline(v = Interval3,col="black",lwd=2,lty="dotted")
abline(v=mean(bacteriaRes$log2FoldChange), col="red",lwd=2)
t.test(x=logfoldrandoMean3, y=bacteriaRes$log2FoldChange, alternative="two.sided") #p-value = 0.03746
#--------------------------------------------------------------------------------------------
# set original par for multipanel plotting downstream
par(oPar)


### Alex's code for p-value function and figures
##############################################################################################
### SET UP FUNCTION FOR DATA ANALYSIS:

##############################################################################################
# Function= pvalue -> takes two DFs and calculates summary stats and pval (z test)
# INPUT: nullDat=nullDF, obsDat = ResDF
# OUTPUT: xbar, mu, n, SD ,SE , z, pval
##############################################################################################
pvalue <- function(nullDat=logfoldrandoMean1, obsDat=stressRes){
    
    obsDat <- obsDat[,2]
    
    xbar <- mean(obsDat)
    mu <- mean(nullDat)
    n <- length(obsDat)
    SD <- sd(obsDat)
    SE <- SD/sqrt(n)
    
    z <- (xbar - mu)/(SE)
    
    pval <- 2*pnorm(-abs(z), lower.tail = TRUE)
    
    out <- list(xbar=xbar, mu=mu, n=n, SD=SD, SE=SE, z=z, pval=pval)
    
    return(out)
}

##############################################################################################
# END FUNCTION

### running test (pvalue) for each of 6 groups

#-------------------------------------------------------------------------------------------
immune <- pvalue(nullDat=logfoldrandoMean0, obsDat=immuneRes)
#-------------------------------------------------------------------------------------------
stress <- pvalue(nullDat=logfoldrandoMean1, obsDat=stressRes)
#-------------------------------------------------------------------------------------------
virus <- pvalue(nullDat=logfoldrandoMean2, obsDat=virusRes)
#-------------------------------------------------------------------------------------------
bacteria <- pvalue(nullDat=logfoldrandoMean3, obsDat=bacteriaRes)
#-------------------------------------------------------------------------------------------

#############################################################################################
# creating data frame for figure: (genegroup, mean, SE etc.)
GeneGroup <- c("immune",
               "stress",
               "virus",
               "bacteria")


xBar <- c(immune$xbar,
          stress$xbar,
          virus$xbar,
          bacteria$xbar)


SE <- c(immune$SE,
        stress$SE,
        virus$SE,
        bacteria$SE)

pVal <- c(immune$pval,
          stress$pval,
          virus$pval,
          bacteria$pval)


DF3 <- data.frame(GeneGroup, xBar, SE, pVal)


###########################################################################################
# calculating confidence interval from null data:
meanCI <- mean(immune$mu,
               stress$mu,
               virus$mu,
               bacteria$mu)

# caclulating quantiles foe each group
IntervalIM <- quantile(x=logfoldrandoMean0, probs=c(0.025,0.975))
IntervalST<- quantile(x=logfoldrandoMean1, probs=c(0.025,0.975))
IntervalVI <- quantile(x=logfoldrandoMean2, probs=c(0.025,0.975))
IntervalBA <- quantile(x=logfoldrandoMean3, probs=c(0.025,0.975))

lower <- mean(IntervalIM[1],IntervalST[1],IntervalVI[1],IntervalBA[1])
upper <- mean(IntervalIM[2],IntervalST[2],IntervalVI[2],IntervalBA[2])


###########################################################################################
# plotting using ggplot

#choosing color pallet
colors <- c(rep("dodgerblue4",4))

#Create a bar graph for with CI and SE bars
plot1 <- ggplot(DF3, aes(x=GeneGroup,
                         y=xBar,
                         fill=GeneGroup)) + 
    geom_bar(stat="identity",
             color = "black",
             position=position_dodge()) + labs(x="Gene Group", y = "log(Fold Change)") + geom_errorbar(aes(ymin=xBar-SE, ymax=xBar+SE), width=.2, position=position_dodge(.9)) 

plot1 + theme_minimal(base_size = 17) + scale_fill_manual(values=colors) + coord_cartesian(ylim = c(-.3, .3)) + annotate("segment", x = .5,xend = 4.5 ,y = meanCI, yend = meanCI, col = "red") + annotate("segment", x = .5, xend = 4.5, y = upper, yend = upper, col = "red", linetype = 2, size = 0.3) + annotate("segment", x = .5, xend = 4.5, y = lower, yend = lower, col = "red", linetype = 2, size = 0.3) + annotate("segment", x = .5, xend = 4.5, y = 0, yend = 0, col = "black", size = 1) + annotate(geom = "text", x = 3, y = .2, label = "*",cex = 8) + theme(legend.position=c(3, 3))

#############################################################################################

### Lauren's immune-related genes ANOVA, volcano plot, and map code

####### Comparing immune-related and random genes' normalized read counts

## Normalizing count data
library(DESeq2)
dds2 <- estimateSizeFactors(ddsFULL)
normcounts<-as.data.frame(counts(dds2, normalized=TRUE))

## Immune-related counts
immuneNormCounts<-normcounts[which(row.names(normcounts) %in% row.names(immuneNames)),]
immuneNorm<-as.data.frame(immuneNormCounts)
hstat<-c("S","S","H","S","H","H","H","H","S","H","S","S","H","H","H","H","H","S")
library(data.table)
immuneNormList<-as.list(immuneNorm)
immNorm<-rbindlist(list(immuneNormList))
timmNorm<-as.data.frame(t(immNorm))
#anovadf<-as.data.frame(rowSums(timmNorm))
#anovadf$healthstatus<-as.factor(hstat)
#names(anovadf)[1]<-"counts"
#summary(aov(counts~healthstatus, data=anovadf))
#boxplot(counts~healthstatus, data=anovadf, col=c("goldenrod","forestgreen"),ylab="Normalized immune-related gene counts")

## Random Normalized Counts
randomNormCounts<-normcounts[sample(row.names(normcounts), 254),]
randNorm<-as.data.frame(randomNormCounts)
hstat<-c("S","S","H","S","H","H","H","H","S","H","S","S","H","H","H","H","H","S")
library(data.table)
randList<-as.list(randNorm)
randNorm2<-rbindlist(list(randList))
tRandNorm<-as.data.frame(t(randNorm2))
#randAOV<-as.data.frame(rowSums(tRandNorm))
# randAOV$healthstatus<-as.factor(hstat)
# names(randAOV)[1]<-"counts"
# summary(aov(counts~healthstatus, data=randAOV))
# boxplot(counts~healthstatus, data=randAOV, col=c("goldenrod","forestgreen"),ylab="Normalized random gene counts")

## ANOVA For Counts: random vs immune
# randAOV2<-randAOV
# immunAOV <- anovadf

random<-as.data.frame(tRandNorm)
randomMeans<-apply(random, 1, mean)

immune<-as.data.frame(timmNorm)
immuneMeans<-apply(immune,1,mean)

genes<-rep(c("Immune","Random"), each=18)
means<-as.data.frame(c(immuneMeans,randomMeans))
means$genes<-genes
names(means)[1]<-"counts"
summary(aov(counts~genes, data=means))
par(mar=c(5,5,5,5))
boxplot(counts~genes, data=means, col=c("goldenrod","forestgreen"),ylab="Normalized read counts", cex=1, cex.axis=2, cex.lab=2)


######### Volcano Plot
par(mfrow=c(1,1))
library(DESeq2)
with(resFULL, plot(log2FoldChange, -log10(padj), pch=20, main="", xlim=c(-6,5),cex.main=1.8, cex.axis=1.5, cex.lab=1.5))
with(subset(resFULL, abs(log2FoldChange)>1.5), points(log2FoldChange, -log10(padj), pch=20, col="orange"))
with(subset(resFULL, padj<.1 ), points(log2FoldChange, -log10(padj), pch=20, col="blue"))
with(subset(resFULL, padj<.05 & abs(log2FoldChange)>1.5), points(log2FoldChange, -log10(padj), pch=20, col="red"))
max(resFULL$log2FoldChange)
library(calibrate)
resFULL$Gene<-substr(row.names(resFULL), 9,21) #Made a new column so I can label genes
with(subset(resFULL, padj<.005 & abs(log2FoldChange)>2), textxy(log2FoldChange, -log10(padj), labs=Gene, cex=0.8))

######## Monterey Bay and California Maps
library(ggmap)
qmap(location="monterey", zoom=9, maptype="satellite")
library(maps)
map(database="state", region='california', interior=T, fill=T, col="forestgreen")

# END SCRIPT

```


------ <div id='id-section38'/>

### Page 38:
------ <div id='id-section39'/>

### Page 39:
------ <div id='id-section40'/>

### Page 40:
------ <div id='id-section41'/>

### Page 41:
------ <div id='id-section42'/>

### Page 42:
------ <div id='id-section43'/>

### Page 43:
------ <div id='id-section44'/>

### Page 44:
------ <div id='id-section45'/>

### Page 45:
------ <div id='id-section46'/>

### Page 46:
------ <div id='id-section47'/>

### Page 47:
------ <div id='id-section48'/>

### Page 48:
------ <div id='id-section49'/>

### Page 49:
------ <div id='id-section50'/>

### Page 50:
------ <div id='id-section51'/>

### Page 51:
------ <div id='id-section52'/>

### Page 52:
------ <div id='id-section53'/>

### Page 53:
------ <div id='id-section54'/>

### Page 54:
------ <div id='id-section55'/>

### Page 55:
------ <div id='id-section56'/>

### Page 56:
------ <div id='id-section57'/>

### Page 57:
------ <div id='id-section58'/>

### Page 58:
------ <div id='id-section59'/>

### Page 59:
------ <div id='id-section60'/>

### Page 60:

------
