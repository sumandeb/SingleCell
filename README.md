# Weekly Updates

## 1/12/2020
=============  
Following are the things I have read about or done:  

### Assay
---------
https://en.wikipedia.org/wiki/Assay
### Microarray
--------------
https://en.wikipedia.org/wiki/Microarray  
https://en.wikipedia.org/wiki/DNA_microarray
### Gene Expression Profiling
-----------------------------
https://en.wikipedia.org/wiki/Gene_expression_profiling  
> Expression profiling is a logical next step after sequencing a genome: the sequence tells us what the cell could possibly do, while the expression profile tells us what it is actually doing at a point in time. Genes contain the instructions for making messenger RNA (mRNA), but at any moment each cell makes mRNA from only a fraction of the genes it carries. If a gene is used to produce mRNA, it is considered "on", otherwise "off". Many factors determine whether a gene is on or off, such as the time of day, whether or not the cell is actively dividing, its local environment, and chemical signals from other cells. For instance, skin cells, liver cells and nerve cells turn on (express) somewhat different genes and that is in large part what makes them different. Therefore, an expression profile allows one to deduce a cell's type, state, environment, and so forth.
> 
> Expression profiling experiments often involve measuring the relative amount of mRNA expressed in two or more experimental conditions. This is because altered levels of a specific sequence of mRNA suggest a changed need for the protein coded by the mRNA, perhaps indicating a homeostatic response or a pathological condition. For example, higher levels of mRNA coding for alcohol dehydrogenase suggest that the cells or tissues under study are responding to increased levels of ethanol in their environment. Similarly, if breast cancer cells express higher levels of mRNA associated with a particular transmembrane receptor than normal cells do, it might be that this receptor plays a role in breast cancer. A drug that interferes with this receptor may prevent or treat breast cancer. In developing a drug, one may perform gene expression profiling experiments to help assess the drug's toxicity, perhaps by looking for changing levels in the expression of cytochrome P450 genes, which may be a biomarker of drug metabolism.[2] Gene expression profiling may become an important diagnostic test.
>
>In an mRNA or gene expression profiling experiment the expression levels of thousands of genes are simultaneously monitored to study the effects of certain treatments, diseases, and developmental stages on gene expression. For example, microarray-based gene expression profiling can be used to identify genes whose expression is changed in response to pathogens or other organisms by comparing gene expression in infected to that in uninfected cells or tissues.
>
> Expression profiling provides new information about what genes do under various conditions. 

### Allele:
-----------
https://www.nature.com/scitable/definition/allele-48/  
> An allele is a variant form of a gene. Some genes have a variety of different forms, which are located at the same position, or genetic locus, on a chromosome. Humans are called diploid organisms because they have two alleles at each genetic locus, with one allele inherited from each parent. Each pair of alleles represents the genotype of a specific gene. Genotypes are described as homozygous if there are two identical alleles at a particular locus and as heterozygous if the two alleles differ. Alleles contribute to the organism's phenotype, which is the outward appearance of the organism.
>
> Some alleles are dominant or recessive. When an organism is heterozygous at a specific locus and carries one dominant and one recessive allele, the organism will express the dominant phenotype. Alleles can also refer to minor DNA sequence variations between alleles that do not necessarily influence the gene's phenotype.

### Sequencing Techniques
-------------------------
#### Sanger Sequencing
----------------------
1. https://www.khanacademy.org/science/high-school-biology/hs-molecular-genetics/hs-biotechnology/a/dna-sequencing  

Sanger sequencing is still in wide use for the sequencing of individual pieces of DNA, such as fragments used in DNA cloning or generated through polymerase chain reaction (PCR). The pieces produced by PCR need to be verified through sequencing.  

Sanger Sequencing works for small sequences. So, the DNA is first splitted into smaller parts. Because of the following reason, a large number of copies of each of these parts are produced. These copies can be produced using PCR or cloning.
> "This process is repeated in a number of cycles. By the time the cycling is complete, it’s virtually guaranteed that a dideoxy nucleotide will have been incorporated at every single position of the target DNA in at least one reaction. That is, the tube will contain fragments of different lengths, ending at each of the nucleotide positions in the original DNA (see figure below). The ends of the fragments will be labeled with dyes that indicate their final nucleotide."

Note:  
>"It's a matter of chance whether a dideoxy nucleotide gets incorporated in a particular polymerization reaction. Some newly synthesized pieces of DNA will consist only of normal, unlabeled nucleotides, and will simply end when the polymerase falls of the template, not due to the addition of a chain-terminating nucleotide. These unlabeled DNA molecules do not interfere with the sequencing reaction, as they are "invisible" in the detection step due to their lack of a dye label."


The polymerase stops when it attaches a ddNTP. Then the polymerase falls away.

**How is the primer-sequence known at the very beginning of Sanger sequencing? (Seems like a chicken-and-egg problem)**  
**What if the primer gets attached to both the complementary strands of the target DNA?**  

#### Shotgun Sequencing
-----------------------

Craig Venter invented this technique  

https://www.csus.edu/indiv/r/rogersa/Bio181/SeqShotgun.pdf  
> "Note that it is important to sequence both strands. While this may seem a waste of effort given the rules of
Watson-Crick base pairing, the fact is that certain areas on one strand may be difficult to sequence
accurately (for example, because of local secondary structure formation). The complementary strand,
however, may sequence well. Using primers from opposite ends will give you sequence for both
strands."  

##### Human Genome Project
-------------------------
https://bio.libretexts.org/Bookshelves/Biotechnology/Bio-OER_(CUNY)/08%3A_Analyzing_DNA/8.10%3A_Sanger_Sequencing_of_DNA  
Human cell contains two copies of the human genome -- one from mom, another from dad. Shotgun sequencing which is based on Sanger sequencing was used for Human Genome Sequencing. The Human Genome Project divided the chromosomes among different genome centers. Because a chromosome is also quite long, the genome centers divided the chromosome into smaller pieces (done using restriction enzymes or mechanically by shearing) and then cloned each piece into multiple copies. Each such colony of copies were used for Sanger sequencing. Then, the sequences of different parts of the DNA-piece were combined using computational algorithms. 

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3068906/  

#### Next Generation Sequencing
-------------------------------
> "Conceptually, next-generation sequencing is kind of like running a very large number of tiny Sanger sequencing reactions in parallel. Thanks to this parallelization and small scale, large quantities of DNA can be sequenced much more quickly and cheaply with next-generation methods than with Sanger sequencing."

### Cloning using Plasmids
--------------------------
Came across the term 'plasmid' while listening to video on Shitgun sequencing using Sanger method. So, I looked for the meaning of 'plasmid' and came across a few sites whose contents on cloning interested me

1. https://www.khanacademy.org/science/ap-biology/gene-expression-and-regulation/biotechnology/v/dna-cloning-and-recombinant-dna
   https://www.khanacademy.org/science/ap-biology/gene-expression-and-regulation/biotechnology/a/overview-dna-cloning

These links talk about DNA cloning in a simplified manner. Using restriction enzymes (2 - one for each end), the gene (to be cloned) is cut from the DNA and then inserted into a plasmid (which is a circular genetic material outside the DNA) with the help of DNA ligase (forms phospho-diester bond between the 3′-hydroxyl end of one restriction-fragment strand and the 5′-phosphate end of another restriction-fragment strand; previously, the sticky ends were just transiently base-paired using H-bonds). The plasmid (recombinant DNA: DNA assembled out of fragments from multiple sources) is then inserted into another bacteria, usually of E. Coli, by applying heat shock. Some E.Coli cells accept the plasmid wheareas others don't. The E. Coli bacteria are then allowed to multiply in a cell-culture dish by providing nutrients and favourable temperature. The E.Coli which didnt accept the plasmids are prevented from growing by: i) injecting antibiotic-resistance gene into the plasmid prior to heat shock. The plasmid contains antibiotic-resistance gene. ii) providing anti-biotics along with nutrients in the cell-culture dish. E. Coli which didn't accept the plasmid perish in the presence of antibiotics. Bacteria without a plasmid will die, while bacteria carrying a plasmid can live and reproduce. The E.Coli which accepted the plasmid grow and reproduce. The plasmids containing the gene-to-be-cloned get replicated along with them. 

Not all colonies will necessarily contain the right plasmid. That’s because, during a ligation, DNA fragments don’t always get “pasted” in exactly the way we intend. Instead, we must collect DNA from several colonies and see whether each one contain the right plasmid. Methods like restriction enzyme digestion and PCR are commonly used to check the plasmids.

Once we have found a bacterial colony with the right plasmid, we can grow a large culture of plasmid-bearing bacteria. Then, we give the bacteria a chemical signal that instructs them to make the target protein.

Once the protein has been produced, the bacterial cells can be split open to release it. There are many other proteins and macromolecules floating around in bacteria besides the target protein (e.g., insulin). Because of this, the target protein must be purified, or separated from the other contents of the cells by biochemical techniques. The purified protein can be used for experiments or, in the case of insulin, administered to patients.

2. https://www.ncbi.nlm.nih.gov/books/NBK21498/

   "When DNA ligase and ATP are added to a solution containing restriction fragments with sticky ends, the restriction fragments are covalently ligated together through the standard 3′ → 5′ phosphodiester bonds of DNA" : why is ATP needed?
   
   The recombinant plasmid in a transformed E. Coli replicates (due to the presence of replication origin) independent of the mother cell-division. Then, the daughter plasmids get distributed within the cell -- at the two ends which finally become two daughter-cells.
   
3. https://bio.libretexts.org/Bookshelves/Genetics/Book%3A_Online_Open_Genetics_(Nickle_and_Barrette-Ng)/08%3A_Techniques_of_Molecular_Genetics/8.05%3A_Cloning_DNA_-_Plasmid_Vectors

   Purified insulin protein is critical to the treatment of diabetes. Prior to ~1980, insulin for clinical use was isolated from human cadavers or from slaughtered animals such as pigs. Human-derived insulin generally had better pharmacological properties, but was in limited supply and carried risks of disease transmission. By cloning the human insulin gene and expressing it in E. coli, large quantities of insulin identical to the human hormone could be produced in fermenters, safely and efficiently. Today, essentially all insulin is produced from recombinant sources (Figure   8.5.2 ), i.e. human genes and their derivatives expressed in bacteria or yeast.
 4. Transgene: The gene that is inserted into the vector here.

    In vivo: Inside the actual organism

    In vitro: Inside a simulated organism but not the actual organism
    
    Oligonucleotide: Oligonucleotides are short DNA or RNA molecules. Oligomers are short polymers. The oligomer concept contrasted to that of a polymer which is usually             understood to have a large number of units, possibly thousands or millions. However, there is no sharp distinction between these two concepts.
    
 5. https://blog.addgene.org/plasmids-101-what-is-a-plasmid
 6. http://wolfson.huji.ac.il/expression/vector/MCS.html

    Multiple cloning sites allow us the freedom to use any of multiple restriction enzymes for cloning.
    
 7. “Recombinant vector molecule cannot be created unless the vector and source DNA is cut with the same restriction enzyme”
 8. https://www.youtube.com/watch?v=I87FjjhdcMU&ab_channel=subratadas
    
    **Why is amplification needed prior to Sanger sequencing/cloning?**
    
    **What are primers?**  
    **Ans:** A primer is a strand of RNA. It is a short nucleic acid sequences (generally about 10 base pairs) that serves as a starting point for DNA synthesis. It is required for DNA                    replication because the enzymes that catalyze this process, DNA polymerases, can only add new nucleotides to an existing strand of DNA (it needs a 3' OH to attach to).          The polymerase starts replication at the 3'-end of the primer, and copies the opposite strand.
   
 9. Polymerase Chain Reaction (PCR): https://www.khanacademy.org/science/ap-biology/gene-expression-and-regulation/biotechnology/v/the-polymerase-chain-reaction-pcr
    
    **Why do we need PCR?**  
    **Ans:** To have enough DNA to clone or see on a gel you typically need billions of individual strands! For example, in general you will need around 10 ng (a nanogram is              10⁻⁹ grams) of DNA to reliably see a band. To convert grams to numbers of molecules you can use the average mass of a single nucleotide (remember to double this for              double stranded DNA):      309 g/mol.
         So, for a 100 bp fragment of double stranded DNA I get ~9.7 x 10¹⁰ molecules. Similarly, for a 1 kb fragment you would need ~9.7 x 10⁹ molecules.
         Thus, if you don't use PCR to amplify the fragment, then you would need to extract DNA from billions of cells. This is possible, but then you would also need to                  separate the fragment you cared about from the millions or billions of other fragments that came from cutting up all the DNA in a cell.
         With PCR you can instead make billions of copies of the piece of DNA you care about while the DNA you don't care about remains unamplified.
         
     **How do people know what sequence to pick for their primer when ordering from a company?**  
     **Ans:** They have to do an experiment to find the exact primer to use.
     
     **Are the PCR primers and the Taq Polymerase originally in the solution when denaturation is occurring, or are the primers added during annealing and the Taq polymerase added during extension?**  
     **Ans:** Primers and Taq polymerise are added at the beginning. Everything is in the same solution but the temperature of PCR machine controls which step is proceeding at a time.  
     **You wound need to do DNA sequencing to know what kind of primer to buy based on where you would like the DNA to be started from.**    
     
     **Two primers are used in PCR -- for marking the start and end of the area of interest**  
     
     **Usually when we do PCR we know the sequence , so we design the primers to bind the ends of the sequence we want to amplify.**  
     **Why do we need to do PCR before cloning? Both cloning and PCR are methods of amplifying. If a gene can be amplified by PCR, then why do we need to go for cloning?**
     **What is the difference between PCR and DNA cloning? I know the procedure is different, but both make copies of DNA. Why would you need to do PCR and then use a vector instead of just PCR?**  
     **Ans:** There are a number of reasons why you might want to clone into a vector rather than just doing PCR:

       * Vectors can be used to do different things with the DNA. A common example of this would be an expression vector — this causes the DNA to be transcribed and translated and would allow you to examine the protein encoded in the cloned DNA.  
       * PCR is somewhat error prone, so if you need a lot of DNA having a bacterium make copies of it for you is much less likely to introduce mutations.  
       * PCR is also more expensive if you want to make large amounts of DNA.  
       * DNA is more stable as a circular plasmid, rather than a linear piece of DNA — this means to store DNA for any length of time you probably want to clone it into a vector anyway.  
       * Long term storage — you can make a frozen (-80°C) stock of the bacteria containing the plasmid bearing the piece of DNA and you or someone else who wants to reuse that DNA can access it decades later by simply adding the bacteria to media and growing up as much as you want.

       In fact, we will often use PCR to create enough of a specific fragment to put into a vector, which then gets transformed into Escherichia coli (often abbreviated to E.    coli). We will then often sequence the cloned fragment to make sure we got what we really wanted and that it doesn't have any mutations. This cloned DNA can now be stored and manipulated in whatever ways are necessary for our experiments.

     **The DNA polymerase molecules are very stable and get reused in each cycle of the PCR. Polymerases can fall off — this can happen at random due to the thermal motion of the molecules; you could think of the polymerase as someone riding a bucking horse — sometimes they get thrown off. Damaged DNA can also cause a polymerase to stall, which increases the chance of it falling off.By the way, replinishing DNA polymerase in each cycle will be expensive**  
     
     **The fact that the primer concentration is much higher than DNA concentration, so statistically a primer is much more likely to bind to the DNA strand than a complementary strand.**  
     
     **In PCR, what happens to the DNA before the forward primer and beyond the reverse primer i.e. outside the region of interest?**  
     **Why do we need to amplify before cloning?**    
#### Cloning of Dinosaur
------------------------
https://www.khanacademy.org/science/high-school-biology/hs-molecular-genetics/hs-biotechnology/v/clone-dinosaurs  
   
> Cloning is possible. Dolly the sheep was the first animal to be cloned, and there are many other examples. However, it would be incredibly difficult--if not nearly impossible--to clone a dinosaur. 
>
> For one, you need the complete genome of the animal you want to clone. In order to completely code for a dinosaur, you need all of the blueprints for it; otherwise, it may have missing or altered functions. Worse yet, DNA degrades over time. Even if you found a way to slow decomposition, DNA will still fall apart. For example, take the mammoth. In comparison to dinosaurs, mammoths recently went extinct. However, scientists are still considering other ways to clone the mammoth because no intact genome has been found. Frozen mammoths are relatively "new"--however, their genome has been partially destroyed. Now imagine trying to sequence a dinosaur.
>
> Two, for certain processes, you need a compatible mother. For these processes, DNA from the clone would be introduced into a mother, which would then develop into a hybrid clone. If the mother and the clone are too different, the baby is unable to survive (this is why you do not see crazy tiger-gorilla creatures out in the wild, for instance). Looking at the mammoth again, scientists can use modern elephants for mothers. However, as the modern relatives of dinosaurs are birds (this was found through DNA sequencing), it would be extremely difficult to produce a living clone of a dinosaur.
>
> Three, should a dinosaur be successfully cloned, it may not live for too long. Defects and other medical problems are known issues among cloning. Dolly the sheep had a lifespan that was only half the lifespan of a sheep. Mammoth DNA injected into mouse cells briefly functioned, but could not divide. Worse yet, the climate may not be suitable for the dinosaurs to live in. Because of global warming, the climate has significantly changed, which will further harm clones that were adapted to a certain climate.
>
> For better or for worse, dinosaurs probably cannot be cloned. For these reasons and more, a dinosaur clone is both extremely difficult to obtain and extremely difficult to maintain. I am not saying that it is downright impossible; it's just that it is extremely difficult to obtain the materials needed for a successful clone.  

**Suppose the entire DNA of a dinosaur has been cloned, then what would be the next steps for it to be fully born as a baby dino?**
   
