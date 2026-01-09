Test data preparation steps.

Single end read downloaded from NCBI SRA SRR12628255 and saved to data/: https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=SRR12628255&display=download

Initial fastq: 3856340 reads
Extract first 100000 reads for testing: gunzip -c data/SRR12628555.fastq.gz | head -n 400000 | gzip > data/SRR12628255_test.fastq
