# Neurocomputing submission instructions

## Main manuscript and Overleaf
- Compile root: `neurocomputing_submission.tex` (NOT `AnonymousSubmission2027.tex`).
- Compiler: pdfLaTeX; bibliography: BibTeX; class: `elsarticle`; style: `elsarticle-num`.
- The full appendix now precedes the bibliography in the same PDF.
- The GitHub repository is source-of-truth. In an Overleaf project linked to this GitHub repository, import/pull the latest `main` changes (Overleaf does not necessarily auto-sync remote changes), then choose the main document above from Menu > Main document and recompile.
- If the Overleaf Git integration treats GitHub as an editable mirror, check for unsynced changes and resolve conflicts before pulling. This update does not change Overleaf directly.
- Prior AAAI sources remain present as archival material; they must not be selected for the Neurocomputing submission.

## Files for submission
- `neurocomputing_submission.tex`: main paper + appendices + declarations + bibliography.
- `references.bib`: bibliography with seven new context-appropriate citations.
- `Highlights.txt`: five suggested highlights (all <=85 characters) for upload as a separate Highlights item if requested by the Neurocomputing portal.
- `Figures/`: source artwork; verify graphics in Overleaf's compiled PDF.

## Mandatory author verification before actual submission
1. The nine author names are copied from arXiv:2610.12977. Confirm the FINAL author order, each affiliation, the corresponding author's email, and authors' approval; add `\\address` / `\\affiliation` and `\\ead` to the frontmatter.
2. Funding and competing-interest declarations require factual statements by the authors. Do NOT declare 'none' without checking. Supply requested forms/sections in the submission portal.
3. Confirm the wording of the Data and code availability statement and whether all reproduction code and datasets can be accessed as promised.
4. The AI-assistance declaration describes editorial help; verify it and edit it to reflect your actual use before submission.
5. Verify the specific article type, any length/graphics/highlights constraints, and any reviewer-anonymity requirements in Neurocomputing's current journal-specific Guide for Authors.
6. Compile successfully, inspect all figures/tables for overflow and citations for '?' warnings; compile BibTeX and twice more with pdfLaTeX.
7. Inspect final manuscript for remaining editing comments, publication claims and funding disclosures. Source retains some historical comments from prior drafts that are not typeset.
8. For Editorial Manager, prepare a flattened archive with the TeX/BibTeX source and figures at one level when required by its LaTeX submission rules; nested `Figures/` may fail in its source-processing workflow. Overleaf compilation can continue to use existing paths.

## Bibliographic correction
The requested Cheng et al. citation listed 2024, but the Elsevier Neurocomputing record shows 22 October **2026** online publication, article 135448, DOI: 10.1016/j.neucom.2026.135448. Its corrected BibTeX key is `cheng2026sustainable`.

## Important scope note
Several of the seven added papers address adjacent multimodal, adaptation, time-series, and systems problems rather than generative recommendation. The manuscript identifies them explicitly as contextual research, not direct baselines or supporting evidence for CQG metrics.

## Official instructions
- https://www.elsevier.com/researcher/author/policies-and-guidelines/latex-instructions
- https://www.elsevier.support/publishing/answer/how-do-i-include-highlights-with-my-manuscript
- https://www.elsevier.support/publishing/answer/how-do-i-prepare-my-files-for-submission-in-editorial-manager
- https://www.sciencedirect.com/journal/neurocomputing
