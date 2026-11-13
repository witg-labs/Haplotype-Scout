# Haplotype Scout

**Your uniparental lines, read carefully: mtDNA from your mother, Y-DNA from your father.**

Most ancestry tools treat haplogroups as a label to print. Haplotype Scout treats them as evidence to weigh: which defining markers your file actually tested, which it never covered, and how strong the call really is before a name gets attached to it.

## What it is built to do

- **mtDNA and Y-DNA haplogroup calling** from the markers present in a consumer raw file
- **Match quality beside every call**, computed from expected variants on the lineage path: found, contradicted, and off-path markers all counted honestly
- **Sparse-data refusal**: when a file tests too few informative positions to support a call, Haplotype Scout says so instead of guessing. A chip file is a keyhole view of the mitochondrion, and the tool treats it that way
- **Lessons carried over from Genotype Scout**, whose haplogroup engine was rebuilt around the same evidence accounting and verified against real kits

Haplotype Scout is in development as a companion to Genotype Scout, where this engine already runs live today.

## Privacy, same rule as everything I build

All processing runs on your device. Raw files are never uploaded or stored on a server.

## About this repository

This is the public showcase for Haplotype Scout, part of the Written In The Genome suite alongside [Genotype Scout](https://github.com/witg-labs/Genotype-Scout). The source code is private and is not published here.

- Genotype Scout, live: [scout.writteninthegenome.blog](https://scout.writteninthegenome.blog)
- Blog: [writteninthegenome.blog](https://writteninthegenome.blog)
- Builder: [Jequan Davis](https://github.com/witg-labs), Written In The Genome
- Contact: writteninthegenome@gmail.com
