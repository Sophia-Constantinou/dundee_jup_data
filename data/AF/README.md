# AF_initial

1348_scope.csv - has 1348 scop id's taken from jpred training data
1348_pdbid - converts scop to pdb
1348_pdbid+scop.csv - add pdb id's to scop
1348_pdb+scop_depr.csv - switch out some deprecated pdb id's

1514_AF_url.csv - has Alphafold url's

uniprot-pdb_aug.csv - this was created manually -- use Uniprot website to map pdb id's to uniprot and download

dssp_run_extra_pdbs.csv - pdb's that gave an error when running DSSP
dssp_read_extra_pdb.csv - pdb's that gave an error when reading DSSP


# AF_pdb_files - 1515 files

Download pdb files from Alphafold website

# AF_dssp_files - 1151 files

Run DSSP on pdb files (output)AF_

# AF_csv_predictions - 1151 files

Read DSSP - all columns

# AF_aa_ss - 1151 files

Choose only structure and prediction from AF_csv_predictions


# AF_m

final AF file that has pdbid, structure and prediction for all


# AF_final

same as AF_m but also has uniprot id










