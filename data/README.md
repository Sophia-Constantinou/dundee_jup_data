# AF
All the files from Alphafold

# Jpred
All the files from Jpred

# ProIntVar
All the files from prointvar

# AF_Pro
ProIntVar merged with AF sequence + prediction

# Pro_final
ProIntVar merged with AF seq+ pred and Jpred seq + pred

# aligned
I used these files up to the final days (data from here is in my slides), but in the last 1-2 days
i got slightly different results so I put the previous here
Here you can find everything - stats, plots, alignment etc


# wed
Stuff I did the past few days - has a few files about AF and jpred confidence, but I didn't have
time to do anything with them (so can ignore)


# check_scop
Sequences that don't need aligning (SCOPe --> PDB)

# jp_align
Sequences that I need to find start and end points of SCOP in PDB sequence

# match_1
Take check_scop files and find exact matches of AF/JP sequences to true

# unmatched_1
Remaining files (match_1 + unmatched_1 = check_scop)

# 4
Take jp_align files and try to align - All the files aligned

# 4_empty

files that are not aligned - empty

# 4_unmatched 

Not aligned files - not empty

# match_2
Has files tha are exact matches from 4

# unmatched_2
Files from 4 that don't match


# jp_shifted
Take files from 4_empty and try to shift Jpred sequence (H tag etc) - saved here if they were an
exact match (jpred seq == true seq)

# jp_fix
Files that weren't an exact match if Jpred sequence was shifted

# match_3
has files hat are exact matches from jp_shifted

# unmatched_3
files from jp_shifted that don't match


# fix_rem
remove some rows that don't match from jp_fix


# match_4
files from fix_rem that are complete matches
-- matches are cumulative but unmatched files are not

# unmatched_4
files that their sequences didn't match


# match_final
Has all the files that are matches







