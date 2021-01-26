
```bash
samtools sort -@ 16 S09.bwa.bacteria.basic.sam >S09.bwa.bacteria.basic.sort.sam 
samtools idxstats -@ 16 S09.bwa.sort.bam > data.txt
```


`data.txt` :
```
Taxid:134821,GCF_000006625.1	751719	1	0
Taxid:1309,GCF_000007465.2	2032925	106	0
Taxid:1396,GCF_000008005.1	5432662	1449	0
Taxid:33959,GCF_000008065.1	1992676	1716	0
Taxid:1392,GCF_000008445.1	5503946	864	0
Taxid:1624,GCF_000008925.1	2134007	1132	0
Taxid:456327,GCF_000009165.1	5420192	131	0
Taxid:294,GCF_000009225.2	6722539	174	0
Taxid:95486,GCF_000009485.1	8055812	1411	0
Taxid:1283,GCF_000009865.1	2697891	3730	0

    .
    .
    .

Taxid:871203,GCF_902833575.1	7018291	451	0
Taxid:984307,GCF_902833705.1	7536587	361	0
Taxid:159450,GCF_902833715.1	7273566	670	0
Taxid:1287735,GCF_902859645.1	6824043	421	0
Taxid:1287735,GCF_902860075.1	6877483	524	0
Taxid:173362,GCF_904418905.1	3390111	17	0
*	0	0	12517707


```

Column|Description
-|-
1|Reference sequence identifier
2|Reference sequence length
3|Number of mapped reads
4|Number of placed but unmapped reads (typically unmapped partners of mapped reads)






