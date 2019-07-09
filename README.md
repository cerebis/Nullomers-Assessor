# Nullomers Assessor
<b>Nullomers Assessor:</b> a computational method for the statistical evaluation of Nullomers (a.k.a. Minimal Absent Words)

<b>Description:</b> Nullomers Assessor is a computational method for the evaluation and classification of a list of Nullomers as 'significantly absent' or not, depending on the distribution of residues in the specified genome/proteome. The underlying method is based on 4 different transition probabilities (orders) of the Markov chain stohastic model. The method is able to assess either nucleotide sequences or amino acid oligomers. Three different statictical correction method have been implemented and are provided with this version.

<b>Usage:</b> Simply download and execute the <b>nullomers_assessor.py</b> script by giving the following arguments.

```
--absolute-path-of-fasta-file       <str>     The file should be one line fasta file
--absolute-path-of-nullomers-file   <str>     The file should include a list of nullomers

```

    
