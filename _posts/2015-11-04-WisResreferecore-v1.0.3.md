---
layout: post
title: Wisconsin, Restored Prairie soil metagenome reference core - MEGAHIT v1.0.3
category: GrePraChallenge
---

### Raw Reads

http://genome.jgi.doe.gov/pages/projectStatus.jsf?db=WisResreferecore

### Preprocessing

Trimmomatic v0.33 with configuration:

`LEADING:3 TRAILING:3 MINLEN:33`

### Unassembled Reads Informations

|---:|---:|
| Number of PE reads | 723,451,572 |
| bp in PE reads | 66,103,894,176 |
| Number of SE reads | 25,962,372 |
| bp in SE reads | 1,894,543,692 |

### MEGAHIT version

v1.0.3

### MEGAHIT options

`--kmin-1pass --k-min 27 --k-step 10 --k-max 87`

### Assembly Stats

|---:|---:|
| Contig length cutoff (bp) | 200 |
| Number of contigs | 8,351,312 |
| Total size (bp) | 4,647,190,872 |
| Largest contig (bp) | 160,134 |
| N50 (bp) | 574 |

### Download Link

http://www.bio8.cs.hku.hk/dataset/MEGABOX/WisResreferecore_MEGAHIT-v1.0.3.fa.gz