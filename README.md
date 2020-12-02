# Weekly Updates

## 1/12/2020
---------
Cloning using plasmids: came across the term 'plasmid' while listening to video on Shitgun sequencing using Sanger method. So, I looked for the meaning of 'plasmid' and came across a few sites whose contents on cloning interested me

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
     
