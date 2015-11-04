---
layout: post
title: Wisconsin, Switchgrass soil metagenome reference core - MEGAHIT v1.0.3
category: GrePraChallenge
---

### Raw Reads

http://genome.jgi.doe.gov/pages/projectStatus.jsf?db=WisSwireferecore

### Preprocessing

Trimmomatic v0.33 with configuration:

`LEADING:3 TRAILING:3 MINLEN:33`

### Unassembled Reads Informations

|---:|---:|
| Number of PE reads | 437,295,112 |
| bp in PE reads | 42,382,402,844 |
| Number of SE reads | 36,714,555 |
| bp in SE reads | 2,356,428,121 |

### MEGAHIT version

v1.0.3

### MEGAHIT options

`--kmin-1pass --k-min 27 --k-step 10 --k-max 87`

### Assembly Stats

|---:|---:|
| Contig length cutoff (bp) | 200 |
| Number of contigs | 4,783,921 |
| Total size (bp) | 2,589,776,155 |
| Largest contig (bp) | 65,654 |
| N50 (bp) | 550 |

### Download Link

http://www.bio8.cs.hku.hk/dataset/MEGABOX/WisSwireferecore_MEGAHIT-v1.0.3.fa.gz