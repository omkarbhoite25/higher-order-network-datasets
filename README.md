# Higher-Order & Real-World Network Datasets

An interactive, source-verified catalog of open datasets and tooling for higher-order
spectral-topology research: the Hodge Laplacian $L_1$, $\mathrm{tr}(L_1^{+})$, Betti
numbers, higher-order Cheeger constants, persistent spectra, and effective resistance
under edge and simplex augmentation.

**Live site:** https://omkarbhoite25.github.io/higher-order-network-datasets/

## What it is

A single self-contained page ([`index.html`](index.html)) cataloging 131 datasets and
9 libraries. Every count, identifier, license, and source link was checked against its
primary source. The page runs offline in any browser, with fonts and math embedded and
no network needed.

## Two-axis model

Each dataset is tagged on two independent axes, so that "real-world" and "higher-order"
can be filtered together rather than as one mutually exclusive category:

- **Structure**: hypergraph, simplicial complex, cell complex, pairwise graph, or toolkit
- **Origin**: real-world, benchmark, synthetic, or repository

A one-click **Real-world higher-order** preset isolates the 29 datasets that are natively
hyperedges or simplices and empirically sourced (the Benson ARB hypergraphs, XGI-DATA,
Hypergraphx, SocioPatterns, the SCoNe ocean-drifter complex, the Ebli and TopoNetX
simplicial complexes, and GUDHI daily-activities). Pairwise real-world graphs are marked
with their lifting route, either a clique complex or a Vietoris-Rips filtration.

A second one-click preset, **MV·temporal on ≥2-cells**, isolates the 35 datasets that
carry a real, multivariate, time-varying signal on cells of order 2 or higher (triangles
or faces, voxels, grains) or on hyperedges of size 3 or more. These come from a
cross-field search beyond the usual topological-ML sources. They include weather radar,
InSAR and satellite grids, areal statistics, experimental mechanics, and tomographic flow
imaging. A 2-cell or 3-cell badge marks the top cell order that carries the signal, and
·MV marks a multivariate signal. Reanalysis, interpolated, and single-scalar sources are
listed for completeness but are not tagged strict.

## Catalog columns

Dataset, Category (its structure and origin), Domain, Size / Scale, Type (temporal or
static), License, and Source. Filter by structure, by origin, by the real-world
higher-order preset, by the multivariate-temporal higher-cell preset, by temporal-only,
or by top picks; search across names, domains, and notes; and sort by name or size. Every
Source link points to the exact page that hosts that dataset.

## Tabs

- **Catalog**: the filterable dataset table
- **Tooling**: a capability matrix of which library computes $L_1$, Betti numbers, and persistent homology
- **Notes**: provenance footnotes and the handful of corrections
- **References**: the primary literature in IEEE style

## Credits

Took help from Claude. Design reference: [paper.design](https://github.com/paper-design/shaders).
