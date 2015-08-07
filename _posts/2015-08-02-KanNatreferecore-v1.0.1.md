---
layout: post
title: Kansas Native Prairie soil metagenome reference core - MEGAHIT v1.0.1
category: GrePraChallenge
---

### Raw Reads

http://genome.jgi-psf.org/KanNatreferecore/KanNatreferecore.info.html

### Preprocessing

Trimmomatic v0.33 with configuration:

`ILLUMINACLIP:ADAPTOR.fa:2:30:10:1:true LEADING:3 TRAILING:3 MINLEN:33`

where `ADAPTOR` is `TruSeq2-PE` for Hiseq2000 reads, and `TruSeq3-PE` for GAII reads.

### Unassembled Reads Informations

|---:|---:|
| Number of PE reads | 2,422,029,272 |
| bp in PE reads | 471,662,120,427 |
| Number of SE reads | 130,278,957 |
| bp in SE reads | 10,699,172,210 |

### MEGAHIT version

v1.0.1

### MEGAHIT options

`--kmin-1pass --k-min 27 --k-step 10 --k-max 87`

### Assembly Stats

|---:|---:|
| Contig length cutoff (bp) | 200 |
| Number of contigs | 47,985,585 |
| Total size (bp) | 27,878,228,835 |
| Largest contig (bp) | 246,919 |
| N50 (bp) | 629 |

### Download Link

http://www.bio8.cs.hku.hk/dataset/MEGABOX/KansasNativePrairieSoilMetagenomeReferenceCore_MEGAHIT-v1.0.1.fa.gz