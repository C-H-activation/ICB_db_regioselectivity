# db_regioselectivity
A database of real compounds and their regioselective products (inspired by [jensengroup](https://github.com/jensengroup/db-regioselectivity))

# Help
To play with this data is recommended to use [RDKit](www.rdkit.org) and Python.

# Structure
The data is split into three files
- ``compounds_smiles.csv`` contains the compound SMILES and the experimental center of borylation (the atomic order follows the SMILES, the product is given where R indictaes the borone).
	- ``compounds_yield.csv`` contains the yield of the compound and conditions (equivalence B2pin2 or HBpin/mol% cat/mol% ligand/ligand). If multiple references, multiple yields are included.
- ``compounds_doi.csv`` contains the reference to literature in the form of either a DOI or a patent number. If no DOI exists a reference is made and can be found in ``bib/library.bib``. Furthermore, the compound number (educt) from the original publication is added (if possible).

# Reference
tba

