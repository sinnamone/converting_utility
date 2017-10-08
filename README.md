# converting_utility
converter raw sequence files 

Usage: python utility.py -i [ input file with path ] -o [ output ID ] -p [ output path ] -t [ selection between 'fastq2fasta','fasta2tab','seqrename','tab2fasta' ] -r [ 1 or 2 ]

Options:
  --version   show program's version number and exit
  -h, --help  show this help message and exit
  -i INPUT    input fasta,fastq,tabular file included path
  -o OUTPUT   Output Id
  -p PATHOUT  Output Pathway
  -t T        Insert fastq2fasta for conversion fastq to fasta;
              Insert fasta2tab per conversion to Fasta to Tabular;
              Insert seqrename for change read name with generic seq+line num;
              Insert tab2fasta to convert tabular file (2 columns, firt with reads name without '>' and second with sequence.)
  -r R        1=forward;2=reverse
