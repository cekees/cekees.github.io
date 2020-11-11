---
title: "Hashdist"
excerpt: "HashDist is a tool for building software stacks in a reproducible manner."
header:
  image: /assets/images/roams.png
  teaser: /assets/images/roams.png
share: false
---

HashDist is a deprecated Python package for managing reproducible
source-based installations of large software stacks. The core idea is
based on the cryptographic hashing approach developed more fully in
[Nix](https://nixos.org). HashDist was developed quickly to make the
approach feasible on platforms in the [DoD High Performance Computing
Modernization Program](https://hpc.mil). HashDist can still be used to
build the software stack for [Proteus](https://proteustoolkit.org) but
interested users should look to similar community-supported tools such
as [spack](https://spack.io) and
[conda-build](https://docs.conda.io/projects/conda-build), which
incorporate many of the ideas in HashDist.

[Github](https://github.com/erdc/hashdist)
