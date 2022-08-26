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

not aligned files - empty

# 4_unmatched

not aligned files - not empty


# match_2

Has files from match_1 + exact matches from 4

# unmatched_2

Files from 4 that don't match



# jp_shifted

Take files from 4_empty and try to shift Jpred sequence (H tag etc) - saved here if they were an exact match (jpred seq == true seq)

# jp_fix
Files that weren't an exact match if Jpred sequence was shifted

# match_3

has files from match_2 + exact matches from jp_shifted

# unmatched_3

files from jp_shifted that don't match


# fix_rem???

Remove some rows from jp_fix

# match_4

files from fix_rem that are complete matches (+files from match_3)
-- matches are cumulative but unmatched files are not

# unmatched_4

files that their sequences didn't match


# extra

some intermediate extra files -- can ignore



