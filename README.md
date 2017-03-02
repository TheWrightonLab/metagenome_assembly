# metagenome_assembly
This script assembles quality trimmed, joined reads. We use sickle to quality trim our reads. https://github.com/najoshi/sickle

Dependencies

IDBA-ud https://github.com/loneknightpy/idba

AMPHORA2 https://github.com/martinwu/AMPHORA2

python

Run this command as follows:

python idba_ud_wrapper.py -r R1R2_trimmed.fastq -o idba_ud_assembled/
