---
layout: post
title: Wisconsin, Native Prairie soil metagenome reference core - MEGAHIT v1.0.3
category: GrePraChallenge
---

### Raw Reads

http://genome.jgi.doe.gov/pages/projectStatus.jsf?db=WisNatreferecore

### Preprocessing

Trimmomatic v0.33 with configuration:

`LEADING:3 TRAILING:3 MINLEN:33`

### Unassembled Reads Informations

|---:|---:|
| Number of PE reads | 1,890,498,882 |
| bp in PE reads | 159,338,658,656 |
| Number of SE reads | 94,785,945 |
| bp in SE reads | 7,068,639,031 |

### MEGAHIT version

v1.0.3

### MEGAHIT options

`--kmin-1pass --k-min 27 --k-step 10 --k-max 87`

### Assembly Stats

|---:|---:|
| Contig length cutoff (bp) | 200 |
| Number of contigs | 10,363,528 |
| Total size (bp) | 6,588,299,156 |
| Largest contig (bp) | 361,667 |
| N50 (bp) | 707 |

### Download Link

http://www.bio8.cs.hku.hk/dataset/MEGABOX/WisNatreferecore_MEGAHIT-v1.0.3.fa.gz