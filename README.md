### Harim Choi

Production ML engineer in Seoul. 6+ years end-to-end across CV, NLP, predictive.
Self-taught, non-traditional path.

**Portfolio:** https://harimxchoi.github.io

Production ML + OSS + research.

**Recent**

- **bidNLP**: Korean public-procurement notice classification. RoBERTa-large + LoRA Teacher-Student, hybrid weak labels (SBERT + finetuned-RoBERTa max-sim ensemble), static INT8 ONNX (AVX512-VNNI). FastAPI service, 1+ year in production. F1 96.4%, 50 ms CPU, weekly 7,000 notices: 40 hr manual to 2 min automated.
- **R2CCP custom**: tender bid rate prediction. Identified interval collapse in the public implementation, fixed via per-bin threshold + entropy regularization. +25 to 40% win rate, 1+ year deployed.
- **wsss-refined-pseudolabels**: weakly-supervised semantic segmentation. Frozen CLIP (ViT-B/16) + DINOv2, Multi-Signal Reliability Estimation. 56.2% mIoU on COCO-Val (+4.3pp over WeCLIP+ 80K baseline). SOTA at release. 3-month contracted research.
- **monogram**: PKM agent system. 5-stage LLM pipeline + atomic Git Tree commits + 13-tool MCP server. PyPI as `mono-gram`.
- **google-surf-mcp**: vendor-agnostic Google search MCP server. SSRF-hardened, 11 test cases, npm-published. 209 stars, 27 forks.

**Working on**

- **DSSP**: 12-branch decision-science taxonomy for LLM agents. 14 agent audits. arXiv preprint coming.
- **E-AT**: entropy-based adversarial calibration. LAPC loss family v1-v7. Active research.

**Contact**

- Portfolio: https://harimxchoi.github.io
- LinkedIn: https://linkedin.com/in/harimxchoi
- Email: 2.harim.choi@gmail.com
