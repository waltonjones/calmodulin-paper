# Methods
## Fly stocks
We maintained our fly stocks at either 18ºC or 25ºC and 60% humidity under a 12h:12h light:dark cycle.
We used standard cornmeal-yeast-corn syrup medium (http://flystocks.bio.indiana.edu/Fly_Work/media-recipes/bloomfood.htm) containing 1.5 g Tegosept per liter of food as an anti-fungal agent.

We received the Orco-GAL4 strain and the Pebbled-GAL4 strains as generous gifts from Bill Hansson (Jena, Germany) and Mattias Alenius (Linköping, Sweden), respectively.
We obtained the following fly strains (Bloomington Stock #) from the Bloomington Stock Center: Orco^1 (23129); 10XUAS-myR::GFP (32198); tub-GAL80ts (7019); tub-GAL80ts (7018); UAS-Dcr2 (24648); UAS-Dcr2 (24650); and Or22a-GAL4 (9952).
We obtained the following fly stocks (Stock #) from the VDRC Stock Center: UAS-CaM-IR (102004).

To generate the UAS-Orco CBS mutants, we designed primers for mutagenizing a pGEMT-easy vector containing an Orco cDNA.
These primers, presented 5' to 3', were as follows: UAS-Orco^W341Δ (GTGCCATCAAGTACGTCGAGCGGCACAAG and CTTGTGCCGCTCGACGTACTTGATGGCAC); UAS-Orco^CBSΔ (GATGATGGTGCGCAAGTACTGGGTC and GACCCAGTACTTGCGCACCATCATC for the SAI deletion, CAAGTACTGGGTCCACAAGCACGTG and CACGTGCTTGTGGACCCAGTACTTG for ER deletion); UAS-Orco^RH344EE(CATCAAGTACTGGGTCGAGGAGGAGAAGCACGTGGTGCGACTG and CAGTCGCACCACGTGCTTCTCCTCCTCGACCCAGTACTTGATG).
After confirming their sequences, we subcloned each mutated cDNA into a modified attB-containing SST13 UAS vector \cite{Suh_2015} downstream of and inframe with the coding sequence for mCherry.
We also subcloned a wild type Orco cDNA into this same vector produce the UAS-Orco^WT control.
We performed this subcloning into the modified SST13 UAS vector using the SLIC protocol \cite{Li_2007, Jeong_2012} and the following primers presented 5' to 3': GCGGCCGCGGCTCGAGAAACAACCTCGATGCAGCCGA and ATATGGTACCCTCGAGTTACTTGAGCTGCACCAGC.

## The Orco snake plot
We used Geneious \cite{Kearse_2012} to align Orco orthologs from 78 different insect species available from NCBI.
We then used Consurf \cite{Ashkenazy_2016} to transform this multiple sequence alignment into conservation scores for each individual amino acid of Orco.
Using transmembrane prediction data produced by the TMHMM algorithm \cite{Krogh_2001}, we created a snake plot for _Drosophila melanogaster_ Orco using the protein visualization tool Viseur (Nancy, France).
Finally, we color-coded each amino acid according to its conservation score using Adobe Illustrator.

## Single-sensillum electrophysiology
We performed single-sensillum recordings from _Drosophila_ ab2A and ab3A sensilla as previously described \cite{Benton_2011}. 
We used paraffin oil (76235, Sigma-Aldrich) for serial dilutions of methyl acetate (45999, Sigma-Aldrich) and ethyl butyrate (E15701, Sigma-Aldrich).
We chose these odors for their selective activation of the ab2A and ab3A neurons \cite{Galizia_2010}.

## Immunostaining of antennal sections
We cut 14 μm frozen sections from fly antennae and prepared and stained them as previously described \cite{Larsson_2004}.
We used the following antibodies: mouse anti-GFP (A11120, ThermoFisher Scientific) at 1:200, Alexa 488-conjugated anti-mouse IgG (ab150117, Abcam) at 1:850, Alexa 594-conjugated anti-rabbit IgG (A11012, ThermoFisher Scientific) at 1:850, and a polyclonal rabbit anti-Orco antibody (raised against the peptide SSIPVEIPRLPIKS by AbFrontier, South Korea) at 1:3000.

## Odorant exposure protocol
After aging each group of flies on normal food for three days post-eclosion, we moved them to new vials containing an odor source that we exchanged daily.
Each odor source consisted of a perforated PCR tube containing 200 μl of odor diluted 1:10 in paraffin oil placed inside a larger, perforated E-tube.
All the odors for this experiment were purchased from Sigma-Aldrich and included the following: methyl acetate (45999), ethyl butyrate (E15701), and methyl hexanoate (259942).

## Statistical analysis
To identify statistically significant differences in olfactory dose-response curves, we compared the experimental genotype to its controls at each odorant concentration using two-way ANOVAs with Bonferroni post-hoc tests for multiple comparisons.
For each odorant concentration on the graph, the higher p-value of the two was shown.
We indicated statistically significant results with asterisks (*** _P_ ≤ 0.001, ** _P_ ≤ 0.01, * _P_ ≤ 0.05) and non-significant results with _ns_.
We performed all data analysis in either Graphpad (San Diego, CA, USA) or using R \cite{R}.