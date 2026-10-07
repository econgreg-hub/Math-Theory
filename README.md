# Conditional Corollaries from the October 2026 OpenAI Mathematics Release

**Author:** John Gregory George, Center for Economic Analysis, Middle Georgia State University.

**AI contribution:** ChatGPT (OpenAI): mathematical synthesis, displayed proof development, source and interface checks, and drafting. **Inspiration:** Jarvis, George's local AI research system. See `CONTRIBUTIONS.txt` and the manuscript's first page for the full attribution.

## Status

**Published release:** [v1.0.0](https://github.com/econgreg-hub/Math-Theory/releases/tag/v1.0.0), published by GitHub on **7 October 2026 at 16:18:40 UTC (12:18:40 p.m. EDT)**. Download the [PDF](https://github.com/econgreg-hub/Math-Theory/releases/download/v1.0.0/conditional-corollaries.pdf) and [LaTeX source archive](https://github.com/econgreg-hub/Math-Theory/releases/download/v1.0.0/arxiv-source-v1.zip). The published PDF was downloaded anonymously and its SHA-256 matched the prepared manuscript. See `PUBLICATION-STATUS.json` for the receipt. The v1.0.0 tag and attached manuscript are retained unchanged; this metadata update records the completed publication.

Version 1.0.0 was prepared on 7 October 2026. This is the public source repository for a research preprint, conditional on the cited upstream manuscripts. It has not undergone external peer review. No claim of established historical priority, independent certification of the upstream proofs, or formal verification is made.

**Archived preprint:** Published on Zenodo on **7 October 2026**, version 1.0.0. Cite this version using DOI [10.5281/zenodo.23219812](https://doi.org/10.5281/zenodo.23219812). The [public record](https://zenodo.org/records/23219812) contains the PDF and LaTeX source archive under CC BY 4.0. The DOI for all versions is [10.5281/zenodo.23219811](https://doi.org/10.5281/zenodo.23219811).

**Read the paper:** [conditional-corollaries.pdf](conditional-corollaries.pdf). **Repository:** https://github.com/econgreg-hub/Math-Theory. No arXiv identifier has been assigned.

Preparation dates and content hashes are not public priority timestamps. The public repository creation/release record and any published archival DOI provide the actual disclosure record. Do not describe a private draft or a reserved DOI as published.

## Results recorded

1. Disjoint arithmetic-progression packings cover a proportion tending to one of the primitive-root primes in each sufficiently large dyadic interval, under the exact cited abundance and quantitative progression-free inputs.
2. A related maximal-matching argument gives pair packings with differences `(q-1)^j`, where `q` is prime and the integer `j >= 2` is fixed.
3. Density-one full BSD for rational signed-squarefree twists over each fixed multiquadratic field; over any fixed biquadratic field, a lower density of at least one third has rank at least two and full BSD.
4. Binary circulants with condition number tending to one, under the ultraflat Littlewood input.
5. Rational Hodge for finite products of smooth complex cubic fourfolds with geometric K3 categories, through the established Fu-Vial correspondence and the released K3-product theorem.
6. Idempotents in a 2-adic completed group ring whose lifts necessarily have infinite support, under the two cited group-ring inputs.

These are transfer arguments and corollaries. The source authors retain credit for the major input theorems, and earlier literature is cited for the established methods. The higher-rank BSD density proof does not require independence of component ranks or the separate all-parameter mean theorem.

## Files

- `conditional-corollaries.pdf`: the manuscript.
- `conditional-corollaries.tex`, `algebra_geometry_sections.tex`, `references.tex`: complete LaTeX source.
- `source-manifest.json`: exact upstream manuscript paths, revision and SHA-256 hashes.
- `CITATION.cff`: citation metadata with the published Zenodo version DOI.
- `.zenodo.json`: metadata for a Zenodo-linked GitHub release.
- `CONTRIBUTIONS.txt`: precise credit and AI disclosure.
- `PUBLICATION-STEPS.txt`: deposit and versioning instructions.
- `SHA256SUMS`: fingerprints of the prepared release files.

## Build

Use a standard TeX Live installation with the packages named in the source. From this directory:

```bash
pdflatex -interaction=nonstopmode -halt-on-error conditional-corollaries.tex
pdflatex -interaction=nonstopmode -halt-on-error conditional-corollaries.tex
```

## Citation and corrections

Cite John Gregory George as the author, with the full title, version and actual public record URL or DOI. The AI contribution and Jarvis acknowledgement are part of the manuscript and should remain with redistributed copies. Do not list OpenAI as an institutional coauthor or imply its endorsement of this downstream note.

George, J. G. (2026). *Conditional Corollaries from the October 2026 OpenAI Mathematics Release* (Version 1.0.0) [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.23219812

Retain version 1.0 after publication. Corrections should be made in a new tagged release and corresponding archival version, with a clear changelog. If an earlier source for a recorded corollary is identified, cite it and correct any priority description.

## License

The note and its original source files are made available under Creative Commons Attribution 4.0 International, to the extent copyright applies. Referenced upstream works retain their own licenses. See `LICENSE.txt`.
