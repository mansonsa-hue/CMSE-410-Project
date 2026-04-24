**The Tree of Life: Benchmarking Phylogenetic Software**

This project looked at the phylogenetic relationships of 10 members of the ATP-binding cassette transporter genes. Gene sequences are from NCBI and were analyzed using NGPhylogeny.fr-- a web-based method. Trees were constructed using maximum likelihood and neighor joining approaches before being compared in order to see how different phylogeny building methodoliges portray relationships from the same dataset.

**Getting Started**

*Dependencies*
All of this wwas done on Windows 10.

*Installing*
Dataset was located at: https://www.ncbi.nlm.nih.gov/gene/?term=ATP-binding%20cassette
The online software utilized for aligning sequences was MAFFT v7: https://mafft.cbrc.jp/alignment/server/
Phylogenies were built on NGPhylogeny.fr: https://ngphylogeny.fr/

*Executing program*
1. Download 10 genes and compile them (copy/ paste) into a single notebook tab.
2. Copy/ paste all sequences into MAFFT v7.
3. When alignment is obtained, insert the file to NGPhylogeny.fr under "PhyML/ OneClick". Repeat this step, but select "FastME/ OneClick".
4. Record the time each selection takes, checking every hour.
5. View tree in the built-in viewer.
6. Qualitatively compare the differences/ similarities between the resulting phylogenies.

**Help**
MAFFT v7 online may take a long time to align sequences when using a larger dataset, so it is important to routinely check the progress of the job.

**Authors**
Sam Manson (mansonsa@msu.edu)
