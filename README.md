# M.perniciosa-LAGIP
Genome assembly and gene identification of Moniliophthora perniciosa genomes at ESALQ, USP. 

# Registro del montaje del genoma MDSP6 - Isolado CP02, genoma de referencia. 

El tipo de secuenciación fue: SANGER - ABI prism 3700
Tengo 2 tipos de secuencias: Pair end y Mate pair. 
El genoma de referencia del NCBI para Moniliophthora perniciosa tiene un tamaño de: 26.7 Mb 

Estadísticas del genoma de referencia:
Size: 26.7 Mb 		Scaffolds: 25,056
Scaf N50: 1.3 Kb		Scaf L50: 6,658
Contigs: 25,176		Cont N50: 1.3 Kb
Cont L50: 6,654		%GC: 47.5 
Genes: 16,443			Protein-coding: 13,560		Non-coding: 114

El genoma de referencia del NCBI se montó a partir de la muestra de M.perniciosa FA553, pertenece al biotipo C.

Pipeline para el montaje: 
Fastqc - Trimmomatic - Fastqc - SPAdes.

Datos iniciales: 
2 sets de datos: Paired-end / Mate-pair (Forward & Reverse)

Primer montaje: Paired-end - SPAdes.

# RESULTADOS: 

Per base sequence quality (Forward read)
![image](https://user-images.githubusercontent.com/88630062/222264002-20a41876-ee5a-471a-b634-98c1947baad1.png)

Per base sequence quality (Forward)
![image](https://user-images.githubusercontent.com/88630062/222264002-20a41876-ee5a-471a-b634-98c1947baad1.png)

Per base sequence quality (Reverse)
![image](https://user-images.githubusercontent.com/88630062/222264927-3dd6c09d-f97b-4501-a5f4-1056044c6d6f.png)

QUAST & BUSCO results (contigs.fasta)
![2023-03-01](https://user-images.githubusercontent.com/88630062/222269201-0e3ccebe-58d2-4dce-9fe5-dc7176497bb4.png)

QUAST & BUSCO results (scaffolds.fasta)
