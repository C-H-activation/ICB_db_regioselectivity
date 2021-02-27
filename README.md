# db_regioselectivity
A database of real compounds and their regioselective products

# Help
To play with this data it is recommended to use [RDKit](www.rdkit.org) and Python.
You can also use the demo version of [ketcher](https://lifescience.opensource.epam.com/ketcher/demo.html) to visualize SMILES.

# Structure
The data is split into several files
- ``compounds_smiles.csv`` contains the compound SMILES and the experimental center of borylation (the atomic order follows the SMILES, the product is given with R indictating the position of borane).
- ``compounds_yield.csv`` contains the yield of the compound and conditions (equivalence B2pin2 or HBpin/mol% cat/mol% ligand/ligand). If multiple references, multiple yields are included.
- ``compounds_ratio.csv`` contains ratios of the compounds and conditions (delta E in kJ/mol (Eyring's equation)/exp. temperature/equivalence B2pin2 or HBpin/mol% cat/mol% ligand/ligand). Room temperature is given as 298.15 Kelvin.
- ``compounds_doi.csv`` contains the reference to literature in the form of either a DOI or a patent number.  Bibtex entries for each DOI can be found in ``bib/library.bib``. Furthermore, the compound number for the educt from the original publication is added (if possible).

# Reference
tba

