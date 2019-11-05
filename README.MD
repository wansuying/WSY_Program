# wsy_program

	usage: wsy_program.pl input.txt output.txt

## Descriptions:

	A fish is swimming in the water.

## Requirements: 

	Perl Modules: water；and air

#HOW-TO

### 1. **user.config**
~~~~~~~~~~~fish~~~~~~~~~~~~~~~~~~~fish~~~~~~~~~~~~~~~~~~~~~~~~~~fish~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
~~~~~~~~~~~~~~~~~~fish~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~fish~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~fish~~

### 2. **synteny.config**

synteny.config specifies the syntonic region between two sequences

>		*Only first 6 column are necessart

>		*END not necessarily larger than start

>		*Could use whole.genome.alignments.pipeline.sh to generate

>		*whole.genome.alignments.pipeline.sh use LAST for pairwise alinment and ChainNet to join close alignments into larger blocks

>		*Final format:	

>			#REF1	START1	END1	REF2	START2	END2	...

### 3. **anntation.config**

anntation.config specifies the gene/feature/repeat locations

>		*Feature ID of non-EXPRESSION tracks must be unique

>		*For EXPRESSION track, note the FEATURE_ID and TISSUE change in col2 and col3, and the STDEV is before the AVERAGE;

>		*check /examples/block4/annotation.config for examples

>		*Curently CDS might not supplorted very vell as can not link the individual CDS box using lines.

### TO-DO list;

+ [ ] 1. Support CDS TRACKs

+ [ ] 2. Make delicate legends.

+ [ ] 3. Avoid Tick marks out of main plot

+ [ ] 4. Regenerate examples

## Citation:

To be published.

## Author:

---------------------------------------------------------------------

>	**Su-Ying Wan**

>	Key laboratory of plant stress biology 

>	E-mail: <2559789920@qq.com>

---------------------------------------------------------------------

## Copyright

Copyright (c) 2016-2018 Su-Ying Wan

