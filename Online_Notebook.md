#Ecological Genomics Spring 2017    

## Author: Lauren Ash      

##Overall Description of notebook      

This is my online notebook for the Ecological Genomics course. I will update with new techniques I learn, questions that I come up with, and general notes. 


##Date started: 2017-01-19 
##Date end:  -   

##Philosophy   
Science should be reproducible and one of the best ways to achieve this is by logging research activities in a notebook. Because science/biology has increasingly become computational, it is easier to document computational projects in an electronic form, which can be shared online through Github.

###Helpful Resources   
[Andrew's Ecological Genomics Webpage](https://adnguyen.github.io/2017_Ecological_Genomics/)   
[Unix Cheat Sheet](https://files.fosswire.com/2007/08/fwunixref.pdf)   
[RNA-seq exercise RMD](./RNASeqPowerActivity.Rmd)        





<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


###Table of contents for 60 entries         
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
* [Page 22:](#id-section22).
* [Page 23:](#id-section23).
* [Page 24:](#id-section24).
* [Page 25:](#id-section25).
* [Page 26:](#id-section26).
* [Page 27:](#id-section27).
* [Page 28:](#id-section28).
* [Page 29:](#id-section29).
* [Page 30:](#id-section30).
* [Page 31:](#id-section31).
* [Page 32:](#id-section32).
* [Page 33:](#id-section33).
* [Page 34:](#id-section34).
* [Page 35:](#id-section35).
* [Page 36:](#id-section36).
* [Page 37:](#id-section37).
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

------ <div id='id-section1'/>
###Page 1: 2017-01-19. First journal article: Ellegren 2014

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


------ <div id='id-section2'/>
###Page 2: 2017-01-23 Course notes [MISSED]

Andrew posted notes of the class and Melissa's info update that I missed [here](https://github.com/adnguyen/2017_Ecological_Genomics/blob/master/ANBE_notebook.md#page-3-2017-01-23-day-2-course-notes).   

Info I looked up after reading Andrew's notes:   

Sanger sequencing: "The first method of sequencing the genetic code was devised by Fred Sanger. To sequence the DNA, it must first be separated into two strands. The strand to be sequenced is copied using chemically altered bases. These altered bases cause the copying process to stop each time one particular letter is incorporated into the growing DNA chain. This process is carried out for all four bases, and then the fragments are put together like a jigsaw to reveal the sequence of the original piece of DNA." [Reference](https://www.dnalc.org/view/15479-Sanger-method-of-DNA-sequencing-3D-animation-with-narration.html)   

Illumina: Illumina next-generation sequencing utilizes a fundamentally different approach from the classic Sanger chain-termination method. It leverages sequencing by synthesis (SBS) technology – tracking the addition of labeled nucleotides as the DNA chain is copied – in a massively parallel fashion. [Reference](https://www.illumina.com/technology/next-generation-sequencing.html)      

------ <div id='id-section3'/>
###Page 3: 2017-01-24 Articles: Rockman 2012 and Lee et al. 2014

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
###Page 4: 2017-01-25 Class notes [QTNs and SSWD info]   

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
###Page 5: 2017-01-30 Choosing SSWD questions   

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
###Page 6: 2017-02-01 Info Update Blitz

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
###Page 7: 2017-02-01 Unix Tutorial and Tips   

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
###Page 8: 2017-02-03 Article: Dunning et al. 2014   
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
###Page 9: 2017-02-06 Info update for RNA seq and article discussion   

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
###Page 10: 2017-02-06 RNA-seq Coding   

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
###Page 11: 2017-02-08 Transcriptomics info update   

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
###Page 12: 2017-02-10 Prepping for Todd et al. info update      

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
###Page 13: 2017-02-15. SNPs and Population Genomics Info Update

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
###Page 14: 2017-02-15. Article discussion: Zhao et al. 2016

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
###Page 15: 2017-02-15 Sequence alignment (SAM) files and Read Count Extraction Coding  

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
###Page 16: 2017-02-22 DESeq2 in R

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
###Page 17: 2017-02-27 Scott Edwards paper    

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
###Page 18: 2017-03-01 Homework Assignment info and WGCNA

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
###Page 19: 2017-03-06 Population Genomics: Steve's Info Update and Alex's Discussion   

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
###Page 20:2017-03-06 Population Genomics Tutorial 
[Link to Tutorial](https://adnguyen.github.io/2017_Ecological_Genomics/Tutorial/2017-03-06_Tutorials_PopGenomics1.html)   

```:set nowrap``` in vim does not wrap text and makes it easier to read

```vcftools --vcf SSW_bamlist.txt.vcf``` summarizes data     
   
Did it detect the correct number of individuals? kept 24 out of 24 Individuals   
How many SNPs do we have? 7472775   

```grep "unres" SSW_bamlist.txt.vcf | wc ``` this searches for SNPs deemed unresolved ("unres") and pipes it to a wordcount (wc) function   
Output: ```5631864 185851488 1028494934
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
###Page 21: 2017-03-07 Homework 2: RNA sequencing for gene expression analyses

I found a [website](http://www.gettinggeneticsdone.com/2014/05/r-volcano-plots-to-visualize-rnaseq-microarray.html) that shows how to create volcano plots with count data, which I was able to apply to this data set.

------ <div id='id-section22'/>
###Page 22:
------ <div id='id-section23'/>
###Page 23:
------ <div id='id-section24'/>
###Page 24:
------ <div id='id-section25'/>
###Page 25:
------ <div id='id-section26'/>
###Page 26:
------ <div id='id-section27'/>
###Page 27:
------ <div id='id-section28'/>
###Page 28:
------ <div id='id-section29'/>
###Page 29:
------ <div id='id-section30'/>
###Page 30:
------ <div id='id-section31'/>
###Page 31:
------ <div id='id-section32'/>
###Page 32:
------ <div id='id-section33'/>
###Page 33:
------ <div id='id-section34'/>
###Page 34:
------ <div id='id-section35'/>
###Page 35:
------ <div id='id-section36'/>
###Page 36:
------ <div id='id-section37'/>
###Page 37:
------ <div id='id-section38'/>
###Page 38:
------ <div id='id-section39'/>
###Page 39:
------ <div id='id-section40'/>
###Page 40:
------ <div id='id-section41'/>
###Page 41:
------ <div id='id-section42'/>
###Page 42:
------ <div id='id-section43'/>
###Page 43:
------ <div id='id-section44'/>
###Page 44:
------ <div id='id-section45'/>
###Page 45:
------ <div id='id-section46'/>
###Page 46:
------ <div id='id-section47'/>
###Page 47:
------ <div id='id-section48'/>
###Page 48:
------ <div id='id-section49'/>
###Page 49:
------ <div id='id-section50'/>
###Page 50:
------ <div id='id-section51'/>
###Page 51:
------ <div id='id-section52'/>
###Page 52:
------ <div id='id-section53'/>
###Page 53:
------ <div id='id-section54'/>
###Page 54:
------ <div id='id-section55'/>
###Page 55:
------ <div id='id-section56'/>
###Page 56:
------ <div id='id-section57'/>
###Page 57:
------ <div id='id-section58'/>
###Page 58:
------ <div id='id-section59'/>
###Page 59:
------ <div id='id-section60'/>
###Page 60:

------
