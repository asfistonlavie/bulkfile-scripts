# bulkfile-scripts

Scripts useful for working with bulk FlyBase data locally.


## Scripts

### FASTA
**[extract_seq_from_fasta.pl](fasta/extract_seq_from_fasta.pl) -**
Extract longest, unique, and specific IDs from the FlyBase FASTA files.

### GFF

**[problem_case_filter.pl](gff/problem_case_filter.pl) -**
Script for removing complicated biological corner cases from GFF files that can
sometimes cause issues with various analysis tools.

### Assembly
**[dmel_r5_to_r6_converter.pl](dmel_r5_to_r6/dmel_r5_to_r6_converter.pl) -**
Convert D. melanogaster coordinates from genome assembly release 5 to
release 6.

### Symbols

**[symbol_to_id_lookup.py](symbols/symbol_to_id_lookup.py) -**
Script for converting symbols (current or old) into their current FlyBase IDs.
This script currently only handles Dmel genes and transcripts but could be easily modified
to handle other species or data types.

