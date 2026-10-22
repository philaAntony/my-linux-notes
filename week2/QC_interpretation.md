# FastQC interpretation: SRR5691197 (first 100k reads)

## Dataset
Maize (Zea mays), first 100,000 reads, 51 bp single-end.

## What looks good
Good per base quality with mean about 34 at the start, up to 38 after. Per base sequence quality module was green and the first base N was a minor issue.

## What looks off
Adapter content rises.There is an uneven base pair sequence content (10-40%). There are multiple overrepresented sequences with RNA PCR Primer as the possible source. The 94,206 out of the 100,000 reads contain the adapter sequence

## Conclusion and next steps
ENA metadata shows that RNA-seq/transcriptomic, QC pattern resembles a short-insert library, meaning that the library type is undetermined. Linked paper or protocol is needed for confirmation. I suggest to trim the adapters before use. I would not use this dataset.

