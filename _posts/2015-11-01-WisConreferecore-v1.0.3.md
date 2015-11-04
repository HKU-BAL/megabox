---
layout: post
title: Wisconsin, Continuous corn soil metagenome reference core - MEGAHIT v1.0.3
category: GrePraChallenge
---

### Raw Reads

http://genome.jgi.doe.gov/pages/projectStatus.jsf?db=WisConreferecore

### Preprocessing

Trimmomatic v0.33 with configuration:

`LEADING:3 TRAILING:3 MINLEN:33`

### Unassembled Reads Informations

|---:|---:|
| Number of PE reads |  |
| bp in PE reads |  |
| Number of SE reads | 46,409,601 |
| bp in SE reads | 3,352,320,384 |

### MEGAHIT version

v1.0.3

### MEGAHIT options

`--kmin-1pass --k-min 27 --k-step 10 --k-max 87`

### Assembly Stats

|---:|---:|
| Contig length cutoff (bp) | 200 |
| Number of contigs | 12,491,837 |
| Total size (bp) | 7,904,212,921 |
| Largest contig (bp) | 144,712 |
| N50 (bp) | 689 |

### Download Link

http://www.bio8.cs.hku.hk/dataset/MEGABOX/WisConreferecore_MEGAHIT-v1.0.3.fa.gz