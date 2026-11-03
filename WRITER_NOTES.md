# Writer notes

## Files created

- `main.tex`, `main.pdf`, `refs.bib`, `sections/title.tex`, and `sections/00_abstract.tex` through `sections/10_conclusion.tex`.
- The `figures/` assets listed below. The LaTeX build also generates ordinary auxiliary files (`.aux`, `.bbl`, `.blg`, `.fdb_latexmk`, `.fls`, `.log`, `.out`, and `.toc`).
- `refs.bib` selects cited entries from the source bibliographies, deduplicates by key, and adds explicit entries for the candidate's cited work. Its EDA and PER entries say “and others” because the supplied review copy does not establish an authoritative complete author list under the binding authorship decision.

## Reused figures

- `/workspace/thesis/unpublished/FSI-Survey/src/supplement/figures/fig3_taxonomy.pdf` → `figures/fsi.pdf`
- `/workspace/thesis/papers/EG-SpikeFormer/src/pipeline_final.png` → `figures/egspike.png`
- `/workspace/thesis/papers/ViThinker/src/overview.png` → `figures/vithinker.png`
- `/workspace/thesis/unpublished/MedVIGIL_TMI/src/figures/fig1.png` → `figures/medvigil.png`
- `/workspace/thesis/unpublished/MedVIGIL_TMI/src/figs/fig_render.pdf` → `figures/medvigil3d.pdf`
- `/workspace/thesis/unpublished/RAW/src/figures/fig0_teaser.pdf` → `figures/raw.pdf`
- `/workspace/thesis/unpublished/EDA/src/figures/cvpr/trace_per.pdf` → `figures/eda.pdf`
- `/workspace/thesis/unpublished/PER/src/figures/method.pdf` → `figures/per.pdf`

These are source graphics, not LaTeX placeholder boxes. Numbers printed within the graphics belong to the original figures and are preserved as part of the credited source artwork; they are not additional prospectus claims.

## Numerical information outside the facts sheet

- The released MedVIGIL reader-study form has 104 probes: `/workspace/thesis/unpublished/MedVIGIL_TMI/src/medvigil_body.tex:1268`.
- PER liver values 0.89 and 0.85 use the final liver verifier, despite the world model being trained without lesion annotations: `/workspace/thesis/unpublished/PER/src/numbers.tex:128-129`. This qualification is made explicit in the draft.
- RAW answerability threshold 0.5: `/workspace/thesis/unpublished/RAW/src/sections/3_framework.tex:67`; five competing concepts: `/workspace/thesis/unpublished/RAW/src/sections/app_seed_protocol.tex:24`. EDA zoom factor 2: `/workspace/thesis/unpublished/EDA/src/numbers.tex:1159`. Nine alternative composites: `/workspace/thesis/unpublished/MedVIGIL_TMI/src/medvigil_body.tex:649`; model group listing: `medvigil_body.tex:545-551`. Research-question and chapter numbers, calendar milestones, author positions, and study setups follow outline §§B–D. Publication years and author lists follow `/workspace/pubs.txt`; the journal author list follows `/workspace/thesis/unpublished/MedVIGIL_TMI/src/medvigil_submission_body.tex:12`.
- Values embedded in copied graphics are reproduced directly from the source files listed above; the EDA trace in particular contains case-specific pixel coordinates and distances. These are figure annotations, not newly estimated results.

## Open issues

- EDA and PER review manuscripts do not establish complete current author lists under the binding first-author decision; publication entries identify Jiang and collaborators without inventing the remaining list. EDA's older author block conflicts with the binding instructions and is not used as the final list.
- FSI-Survey is described as targeting Neurocomputing; the submission status is not stated in the supplied materials. CVPR and TMI decision dates are unknown.
- EDA and PER results are preliminary, with repeated runs and variance still to be completed. EDA source placeholders require final artwork in the underlying paper; none is reproduced here. A reader study remains proposed.
- Some figures contain small source text and should be inspected in the final defense-format rendering.
- The handbook milestones are transcribed from the requested outline; this draft did not independently verify current university policy.

## Revision round 1

- Switched to article sections, removed duplicate contribution bullets, tightened prose and caveats, and condensed the conclusion to two paragraphs.
- Retained the two MedVIGIL figures and the EDA and PER figures at reduced height, with source credits; removed the other figure blocks.
- Compressed the complete publication list, retaining dissertation author lists, roles and flags, and added the verified 2025 NeurIPS metadata for MINT-CoT.
- The review asks Henry to confirm the MedVIGIL counts 8,476, 4,238, 355,062 and 180 against the current TMI manuscript; these are supported by the supplied catalog.
