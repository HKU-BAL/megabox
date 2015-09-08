---
layout: post
title: Kansas Cultivated corn soil metagenome reference core - MEGAHIT v1.0.2
category: GrePraChallenge
---

### Raw Reads

http://genome.jgi.doe.gov/pages/projectStatus.jsf?db=KanCulreferecore

### Preprocessing

Trimmomatic v0.33 with configuration:

`LEADING:3 TRAILING:3 MINLEN:33`

### Unassembled Reads Informations

|---:|---:|
| Number of PE reads | 2,439,292,754 |
| bp in PE reads | 200,467,243,504 |
| Number of SE reads | 107,994,559 |
| bp in SE reads | 7,349,836,357 |

### MEGAHIT version

v1.0.2

### MEGAHIT options

`--kmin-1pass --k-min 27 --k-step 10 --k-max 87`

### Assembly Stats

|---:|---:|
| Contig length cutoff (bp) | 200 |
| Number of contigs | 11,658,121 |
| Total size (bp) | 6,901,519,639 |
| Largest contig (bp) | 279,160 |
| N50 (bp) | 616 |

### Download Link

http://www.bio8.cs.hku.hk/dataset/MEGABOX/KansasCultivatedCornSoilMetagenomeReferenceCore_MEGAHIT-v1.0.2.fa.gz