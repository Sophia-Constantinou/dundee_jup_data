# Jpred

(initial) Notebook to get pdb sequence and secondary structure prediction from jpred website


# Alphafold

(iniial) Notebook to convert scop id to pdb, pdb to uniprot id, run url on AF website, download pdb files, run dssp, merge

# ProIntVar

Code from ProIntVar repo (Barton group GitHub) that takes merged files (DSSP, SIFTS, etc) and chooses useful columns

# Pro_AF_JP

merges ProintVar with Alphafold (AF) seq + pred and JPred (JP) seq + pred


# AF_colab_dssp

Notebook to run dssp and merge with ProIntVar -- on some pdb id's that I ran with Af colab and downloaded as pdb files

# Check_merged_lengths

Used this to keep track of number of files after each thing I did -- to make sure that I know where files/data is 'lost'


# conting_tables+stats - ignore

Used it to make contingency tables for AF and Jpred, and calculate some initial metrics (I only had 330 pdb id's)
I don't use this notebook to get the final stuff, but code is useful


# debug_no_files
Used this to keep track of number of files with SIFTS and stuff


# DSSP_code

Code from ProIntVar that runs DSSP and SIFTS (sifts wasn't working when I was trying to run this)





# pdb_merge_shift

Ignore this -- has some of the code I used in the final (I was initially using it to merge JPred with prointvar and shift it correctly)



# stats_morepdb

This is a continuation of conting_tables+stats, just with more pdb id's and some code to ignore rows that don't match



# uni_merge_shift

Ignore this -- has some of the code I used in the final (I was initially using it to merge AF with prointvar and shift it correctly)


# tues
This has alignment and stats + plots that I used in presentations/talks
In the past few days I didn't use this - used other notebooks that gave slightly different results

# aug_align


# checking
Used this to check number of files at each stage of aligning

# confidence
Used this to get confidence score of AF and Jpred -- but didn't have time to use it

# final_stats
Final stats that I calculated + plots
(not really sure what's different from tues stuff, but it has slightly less files and Jp performs slightly worse)


# plot
Used it to plot in some intermediate stages -- can ignore

