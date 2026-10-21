# Yixiao Tao

I work on spatial intelligence, and the part of robotics where large models meet geometry.

> Large models are very good at telling you *what* something is, and surprisingly bad at telling you *where*. Most of my work lives in that gap.

**Now:** joining a spatial-intelligence / 4D world model team in Hangzhou · MSc Robotics & AI, UCL (2026)

---

## Selected work

### SAV-SLAM — evidence-graded audio-visual sound attribution
*MSc thesis, UCL · supervised by Simon Julier & Sajad Saeedi*

An iPhone, a $60 four-mic array, and no task-specific training. Every sound the system discovers is either bound to a visible object in a VGGT-SLAM map, or explicitly reported as **ambiguous / unattributed** — because a confident wrong answer is worse than an honest abstention.

- Association in reprojection space: acoustic bearings → pixel columns, with whole-array SRP-PHAT on Wiener-masked raw channels (spatial phase preserved)
- 13 scored streams: **6 correct, 4 abstentions, 1 wrong** — against 2 bindings for a semantic-only baseline
- Re-grounded a HomePod that YOLO had confidently labelled "sports ball", via audio label → SAM3 → bearing election
- A 14-entry findings ledger of what broke and why — e.g. generative separators silently destroy inter-channel phase

[Code](LINK) · [Thesis](LINK)

### [loop-lens](https://github.com/PchT4129/loop-lens) — visual place recognition for loop closure
<!-- TODO: one line — backbone / dataset / headline Recall@1 -->

### Industrial vehicle detection *(internship)*
Detection in cluttered port footage under real deployment constraints.

---

## Toolbox
Python · PyTorch · OpenCV · ROS 2 · Docker · Linux

## Elsewhere
[yixiao-tao.com](https://yixiao-tao.com) · i@yixiao-tao.com · [LinkedIn](https://www.linkedin.com/in/yixiao-tao-44935b260/)
