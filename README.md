# Worm-Connectome-Polarity

Code related to the following manuscript:

INFO COMING SOON

## ACh degree analysis

- Correlated receptor expression with the number of incoming and outgoing synspases in a neuron class
- Plot correlations
- Plot heatmaps of receptor expression in neuron classes

Code: ACh_degree_v1.ipynb

Input file: expression_allgroups_thr4_correct_nmj.csv

Data origin: 

Synapse numbers from: 
(Includes gap junctions)

Expression: DOI: 10.1016/j.cell.2021.06.023 using threshold 4
link: http://www.cengen.org

## Excitatory & Inhibitory Receptor Analysis

- Do Neurons ever express Excit & Inhib receptors for the same ligand?
- Predict sign of a connection based upon relative expresison of excitatory & inhibitory receptor expression
- Calculate the ratios of excitatory & inhibitory connections per transmitter and total

Code: polarity_v1.ipynb

Input files:

wormweb_synapselist.csv
lgc_ligands_git.xlsx
connectome.xlsx
NT_list.csv

made during analysis:

wormweb_connectome_classes_gap_correct.csv
wormweb_connectome_classes_correct.csv

Data origin:

LGC ligands: variety of published and unpublished sources, see manuscript for detailed references

Synapse numbers: wormweb http://wormweb.org/details.html 

Neurotransmitter IDs: https://elifesciences.org/articles/12432 

Expression: DOI: 10.1016/j.cell.2021.06.023 using threshold 4 link: http://www.cengen.org
