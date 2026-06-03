# Selective Multipathology Chest X-Ray Classification via Rejection Mechanisms (R3)

Revised manuscript and reviewer response for the Round-3 revision, published via GitHub Pages.

- **[index.html](index.html)**: the revised manuscript. Tracked-edit highlighting versus the Round-2 version uses green for newly added text and yellow for modified text. It carries 7 figures and 4 tables, evaluated on three public datasets (NIH ChestX-ray14, MIMIC-CXR, PadChest) with bootstrap confidence intervals.
- **[response.html](response.html)**: the point-by-point response to Reviewer 2's three concerns, each with a "Where in the manuscript" pointer to the relevant section, table, figure, or equation, and a Harvard-style reference list. Links to the manuscript and Word version sit in the top-right.
- **manuscript.docx**: the Word version with the same green and yellow tracked-edit highlighting and native (OMML) equations, suitable for track-changes review.

Headline: at a calibrated operating point, per-pathology entropy-based abstention improves balanced accuracy for all four target pathologies on NIH (gains 0.04 to 0.09 at 0.70 coverage, 95% CIs excluding zero), and the benefit replicates on MIMIC-CXR, on PadChest, on an independently trained model, and under leave-one-dataset-out domain shift.

Research code and reproduction pipeline: <https://github.com/ApartsinProjects/cxr-selective-rejection-code>.
