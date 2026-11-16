# Harim Choi

Machine Learning Engineer · Seoul

I develop training methods, inference kernels and the systems needed to put models to work. My research includes SOTA results in weakly supervised semantic segmentation (WSSS) and INT2/INT3 post-training quantization (PTQ). In public procurement, I connected tabular foundation models, Monte Carlo simulation and uncertainty estimates to bid recommendations. I also build research search tools and AI agents.

Since September 2026, I have been doing remote AI evaluation work through Mercor on a freelance basis.

[Portfolio](https://harimxchoi.com) · [Full CV](https://harimxchoi.com/cv/) · [LinkedIn](https://www.linkedin.com/in/harimxchoi) · [Email](mailto:2.harim.choi@gmail.com)

## Selected work

- **[WarpQuant](https://github.com/HarimxChoi/WarpQuant)**: INT2/INT3 PTQ SOTA. Developed quantization and recovery methods and custom CUDA kernels, integrated into llama.cpp. A separate kernel benchmark delivered **7.36× GPTQ W3 decoding throughput** (14.0 → 103.4 tok/s). INT3 achieved better model quality than Microsoft Research VPTQ.
- **[Weakly supervised semantic segmentation](https://github.com/HarimxChoi/wsss-refined-pseudolabels)**: Developed CLIP/DINOv2 disagreement-pixel refinement and reached **COCO-Val mIoU 53.31%**.
- **[Google Surf MCP](https://github.com/HarimxChoi/google-surf-mcp)**: Built research search and automatic ontology tools for agents to retrieve web pages, papers and code, then reuse evidence through source-linked knowledge graphs.
- **[Monogram](https://github.com/HarimxChoi/monogram)**: Built personal knowledge-management automation that turns shared links, papers and videos into searchable notes. Added replay tests and a feedback process that reuses reviewed examples.
- **MyShot**: Trained a model to reconstruct golf motion in 3D from phone video and built a human-pose analysis system. GolfPose 17-joint 2D-to-3D evaluation: **35.6 mm MPJPE** and **3.1° X-Factor MAE**.
- **E-AT**: Calibration training using existing CNN/Transformer architectures. Paired ISIC CNN validation metrics at epoch 9: **ECE 1.03%**, **Macro-F1 0.8291**.
- **AI agents**: Evaluation and approved-example feedback loops, MCP tools, computer use, and a LangGraph workflow delivered to a US travel agency.

## Production experience

- Prediction and decision systems using tabular foundation models, Monte Carlo simulation, and uncertainty quantification.
- NLP fine-tuning with weak supervision, INT8 ONNX optimization, and FastAPI CPU serving.
- Data preparation, model evaluation, batch inference, and AWS/Airflow operations.
