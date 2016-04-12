samtools
========

This is a fork of samtools that changes so that

samtools view ... $bam $bed

will query the bam for all regions in bed using the index. 
