samtools
========

This is a fork of samtools that changes so that

samtools view ... $bam $bed

will query the bam for all regions in bed using the index. 

Normally, using -L $bed, samtools will iterate over every alignment
in the bam and check each one to see if it falls in the bed regions.
