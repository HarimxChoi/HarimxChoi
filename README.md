# Harim Choi

Machine Learning Engineer · Seoul

I am an ML engineer with SOTA results in weakly supervised semantic segmentation (WSSS) and INT2/INT3 post-training quantization (PTQ). I have delivered prediction models, vision systems, and AI agents, combining tabular foundation modeling with Monte Carlo simulation and uncertainty quantification. My work spans training methods and CUDA kernels, automatic ontology construction, and agent improvement through evaluation and feedback.

[Portfolio](https://harimxchoi.com) · [Full CV](https://harimxchoi.com/cv/) · [LinkedIn](https://www.linkedin.com/in/harimxchoi) · [Email](mailto:2.harim.choi@gmail.com)

## Selected work

- **[WarpQuant](https://github.com/HarimxChoi/WarpQuant)**: INT2/INT3 PTQ SOTA. Developed quantization and recovery methods and custom CUDA kernels, integrated into llama.cpp. A separate kernel benchmark delivered **7.36× GPTQ W3 decoding throughput** (14.0 → 103.4 tok/s). INT3 achieved better model quality than Microsoft Research VPTQ.
- **[Weakly supervised semantic segmentation](https://github.com/HarimxChoi/wsss-refined-pseudolabels)**: Developed CLIP/DINOv2 disagreement-pixel refinement and reached **COCO-Val mIoU 53.31%**.
- **[Google Surf MCP](https://github.com/HarimxChoi/google-surf-mcp)**: Web, paper, and code retrieval with automatic ontology-linked knowledge graph construction and evidence lineage.
- **MyShot**: Trained a model to reconstruct golf motion in 3D from phone video and built a human-pose analysis system. GolfPose 17-joint 2D-to-3D evaluation: **35.6 mm MPJPE** and **3.1° X-Factor MAE**.
- **E-AT**: Calibration training using existing CNN/Transformer architectures. Paired ISIC CNN validation metrics at epoch 9: **ECE 1.03%**, **Macro-F1 0.8291**.
- **AI agents**: Evaluation and approved-example feedback loops, MCP tools, computer use, and a LangGraph workflow delivered to a US travel agency.

## Production experience

- Prediction and decision systems using tabular foundation models, Monte Carlo simulation, and uncertainty quantification.
- NLP fine-tuning with weak supervision, INT8 ONNX optimization, and FastAPI CPU serving.
- Data preparation, model evaluation, batch inference, and AWS/Airflow operations.
