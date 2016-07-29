# giab

Python script to convert the output of ARCS into a format that LINKS can use.

Usage: `python makeTSVfile.py <input ARCS _original.gv file> <output LINKS file> <sequences to scaffold.fa>`

The LINKS output file must be named XXX.tigpair_checkpoint.tsv, where XXX is the base name (-b) in LINKS.

Ex. 
`python makeTSVfile.py hsapiens-scaffolds.fa.scaff_s98_c5_original.gv human_c5.tigpair_checkpoint.tsv hsapiens-scaffolds.fa; LINKS -f hsapiens-scaffolds.fa -s empty.fof -b human_c5 -l 5 -a 0.3`
