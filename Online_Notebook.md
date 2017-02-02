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




<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.


###Table of contents for 60 entries         
* [Page 1: 2017-01-19](#id-section1). First journal article: Ellegren 2014 
* [Page 2: 2017-01-23](#id-section2). Class notes [MISSED]
* [Page 3: 2017-01-24](#id-section3). Articles: Rockman 2012 and Lee et al. 2014
* [Page 4: 2017-01-25](#id-section4). Class notes [QTNs and SSWD info] 
* [Page 5: 2017-01-30](#id-section5). Choosing SSWD questions
* [Page 6: 2017-02-01](#id-section6). Info Update Blitz
* [Page 7:](#id-section7).
* [Page 8:](#id-section8).
* [Page 9:](#id-section9).
* [Page 10:](#id-section10).
* [Page 11:](#id-section11).
* [Page 12:](#id-section12).
* [Page 13:](#id-section13).
* [Page 14:](#id-section14).
* [Page 15:](#id-section15).
* [Page 16:](#id-section16).
* [Page 17:](#id-section17).
* [Page 18:](#id-section18).
* [Page 19:](#id-section19).
* [Page 20:](#id-section20).
* [Page 21:](#id-section21).
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
   
**Genetic architecture:** the genetic background to phenotypic traits, including their number, effect sizes, and dominance.   
   
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

[Link to Handout and Notes](QTNHandout.pdf) 

Things to do:   
**Pick an info update paper and discussion paper by Monday**   
Sign up to audit the class   
    
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
    
[Sea Star Wasting Disease Data](SSWD_data.pdf)   
   
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

RNA seq  | Micro array   
-------- |:----------:|
Wide range of expression value| N/A |   
N/A| Saturation of analog-type (flourescent) signal |  
Info on splicing events| ?? |        
    
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
    
[Amplicon Sequencing Handout](https://github.com/lvash/Online-Notebook/files/748269/AmpSeqHandout.pdf)    
    
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
* [Library prep video](https://www.youtube.com/watch?v=yC0Bzw3WbQ) on handout   

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
1 | 2 | 3 | 4    
--- |:---:|:---:|---:|   
| + | - | + | + |   
| - | - | + | - |  
   
  

**Fragments/Loci on y axis**

Limitations   
* Individuals that vary in methylation will vary in fragments that are produced (restriction enzymes sensitive to epigenetic modifications - may skip over)   
* Reduced representation   

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


Link to [Andrew's Ecological Genomics Webpage](https://adnguyen.github.io/2017_Ecological_Genomics/)   
[Unix Cheat Sheet](https://files.fosswire.com/2007/08/fwunixref.pdf)

------ <div id='id-section7'/>
###Page 7:
------ <div id='id-section8'/>
###Page 8:
------ <div id='id-section9'/>
###Page 9:
------ <div id='id-section10'/>
###Page 10:
------ <div id='id-section11'/>
###Page 11:
------ <div id='id-section12'/>
###Page 12:
------ <div id='id-section13'/>
###Page 13:
------ <div id='id-section14'/>
###Page 14:
------ <div id='id-section15'/>
###Page 15:
------ <div id='id-section16'/>
###Page 16:
------ <div id='id-section17'/>
###Page 17:
------ <div id='id-section18'/>
###Page 18:
------ <div id='id-section19'/>
###Page 19:
------ <div id='id-section20'/>
###Page 20:
------ <div id='id-section21'/>
###Page 21:
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
