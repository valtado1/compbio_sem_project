Here is the folder with all of my data.

1. fig_4_data_on_relevant_genes_in_29_tissues is from the original paper, accessed February 2022, and has the top 20 relevant genes in 29 tissues in the body. There are 323 total genes, but 624 data points as there is overlap between the tissues.

2. similarity_between_29_tissues_data_for_fig_4 contains the results from my process of using data set 1 and finding the Jaccard similarity between the tissues.

<<<<<<< HEAD
3. fig_3_data_fugue_scores_for_six_tissues.csv is also from the original paper and contains data values necessary for recreating Figure 3. There are six tissues represented, each with around 100 genes and different scores, including ZScore, NeighborMEanBreadth, and probability (ranking by FUGUE algorithm created in paper) for determining how relevant each gene was in each tissue. The raw values in the probability column were rank transformed and underwent a bootstrapping technique to recreate Figure 3. 
=======
3. fig_3_data_fugue_scores_for_six_tissues.csv is also from the original paper and contains data values necessary for recreating Figure 3. There are six tissues represented, each with around 100 genes and different scores, including ZScore, NeighborMEanBreadth, and probability (ranking by FUGUE algorithm created in paper) for determining how relevant each gene was in each tissue. The raw values in the probability column were rank transformed and underwent a bootstrapping technique to recreate Figure 3.
>>>>>>> bf68988d39ca0fbff9326fabe050a6835866d1d6

4. new_copy.csv is simply a copy of fig_3_data_fugue_scores_for_six_tissues.csv with only Heart rows present.

5. red_tissues_fig_4.csv is a list of tissues from fig_4_data_on_relevant_genes_in_29_tissues, but only the tissues present in Figure 4.

All other datasets in my results notebooks are versions of these, whether I cleaned the dataset or removed/added columns (percent rank, mean percent rank).
