# Selective Multipathology Chest X-Ray Classification via Rejection Mechanisms (R3)

**Live paper (GitHub Pages): <https://apartsinprojects.github.io/cxr-selective-rejection/>**

Revised manuscript and reviewer response for the Round-3 revision.

- **[index.html](https://apartsinprojects.github.io/cxr-selective-rejection/)**: the revised manuscript. Tracked-edit highlighting versus the Round-2 version uses green for newly added content and yellow for modified content (prose, captions, and table cells). It carries 8 figures and 5 tables, evaluated on three public datasets (NIH ChestX-ray14 n=11,212, MIMIC-CXR n=8,185, PadChest n=5,000) with bootstrap confidence intervals, including a random-rejection control and confidence-score comparison (Table 5).
- **[response.html](https://apartsinprojects.github.io/cxr-selective-rejection/response.html)**: the point-by-point response to Reviewer 2's three concerns, each with a "Where in the manuscript" pointer to the relevant section, table, figure, or equation, and a Harvard-style reference list.
- **[manuscript.docx](https://apartsinprojects.github.io/cxr-selective-rejection/manuscript.docx)** / **[manuscript_2col.docx](https://apartsinprojects.github.io/cxr-selective-rejection/manuscript_2col.docx)**: single-column and two-column Word versions with the same green/yellow tracked-edit highlighting and native (OMML) equations, suitable for track-changes review.

Headline: at a calibrated operating point, per-pathology entropy-based abstention improves balanced accuracy for all four target pathologies on NIH (gains 0.04 to 0.09 at 0.70 coverage, 95% CIs excluding zero), and the benefit replicates on MIMIC-CXR, on PadChest, on an independently trained model (including cross-dataset on MIMIC), and under leave-one-dataset-out domain shift.

Research code and reproduction pipeline: <https://github.com/ApartsinProjects/cxr-selective-rejection-code>.
