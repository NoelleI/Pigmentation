# Pigmentation

This code is a prototype of part a patented process that determines biological properties of the skin from an image and adjusts a topical product formulation based on the user response to an applied dose of product. Here the algorithm tracks progress in eliminating a pigmentation spot when a proprietary formulation is applied. The methodology detects the pixels within the spot (pigmented skin) and those outside the spot (normal skin) and tracks the difference in skin color between the normal and pigmented skin over the application period. The work is in progress, but detection of quantitive improvement is currently possible for the use case in question. See POC Results upon request. Property of Skin Depth Inc. Disseminated for Commercial Purposes. Patent protected.

The ISIC 2018 dataset is used in the research. The following sources are cited:
[1] Noel Codella, Veronica Rotemberg, Philipp Tschandl, M. Emre Celebi, Stephen Dusza, David Gutman, Brian Helba, Aadi Kalloo, Konstantinos Liopyris, Michael Marchetti, Harald Kittler, Allan Halpern: “Skin Lesion Analysis Toward Melanoma Detection 2018: A Challenge Hosted by the International Skin Imaging Collaboration (ISIC)”, 2018; https://arxiv.org/abs/1902.03368

[2] Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).
