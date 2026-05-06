<h1 align="center">Hi, I'm Sai Teja Vaidya 👋</h1>

<p align="center">
  <b>Computer Vision · Deep Learning · Agentic AI · Edge ML</b><br>
  M.Eng. in ICT — Asian Institute of Technology, Thailand
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vaidyasai/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://x.com/vaidyasaiteja"><img src="https://img.shields.io/badge/Twitter-000000?style=flat&logo=x&logoColor=white"/></a>
  <a href="https://sai21112000.github.io"><img src="https://img.shields.io/badge/Blog-FF5722?style=flat&logo=jekyll&logoColor=white"/></a>
  <a href="https://www.youtube.com/@saitejavaidya"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white"/></a>
</p>

---

I work at the intersection of **computer vision and physical systems**—where a model's output has real-world consequence. My thesis detected and measured individual oil palm trees from drone imagery across 8 altitude levels using YOLOv8, YOLOv11, SAM 2.1, and Mask R-CNN. I built an agent-in-the-loop annotation pipeline that reduced labeling time by 80% and a generative tiling algorithm that simulates multi-altitude flights from a single drone pass.

Recent focus: **agentic AI systems** that are auditable and constrained, **edge vision models** under strict latency and power budgets, **efficient training** of LLMs and small models, and **local-first tools** for knowledge work.

Open to AI Engineer, Computer Vision, Remote Sensing ML, and Agentic AI roles in Thailand, India or remote.

---

## 🌱 Currently Learning

- Deep Reinforcement Learning (HuggingFace RL Course)
- Langchain Academy Course
- Kaggle Competetions / Hackathons

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white)
![Jekyll](https://img.shields.io/badge/Jekyll-CC0000?style=flat&logo=jekyll&logoColor=white)

## 🎯 Featured Projects

### Dopamine.Diet 
I built Dopamine.Diet: a local-first productivity system that hijacks your brain's love for checkboxes, streaks, and green squares — and redirects it toward deep work.
- [Live Blog](https://sai21112000.github.io/posts/dopamine-diet-local-first-productivity-system.html)
- Website: [Dopamine.Diet](https://sai21112000.github.io/Dopamine.Diet/)

### AI Thesis Agent Kit
Multi-agent orchestration system with 9 specialized agents, 6 immutable writing laws, and 90% confidence gate for hallucination control. Built during thesis at AIT to automate research documentation and inference.
- Repo: [Thesis-Agent-Kit](https://github.com/Sai21112000/Thesis-Agent-Kit)

### OpenAI Parameter Golf Reproduction
Reproduced OpenAI's Parameter Golf challenge: H100 training on RunPod with torchrun, FineWeb dataset, and continuous val_bpb tracking. Focus on **reproducibility under strict wall-clock constraints**.
- Demonstrates large-scale training orchestration and compute efficiency
- Repo: [OpenAI-Parameter-Golf](https://github.com/Sai21112000/OpenAI-Parameter-Golf)

### Qualcomm AI Hub LPCVC 2026 — Track 1
Image-to-text retrieval on XR2 Gen 2 proxy (edge device). Achieved Recall@10 ≈ 0.73.
- Full pipeline: model selection, ONNX export, hardware profiling, dataset curation, inference optimization
- Demonstrates end-to-end edge ML deployment

### Minimalist Blog
Zero-framework Jekyll blog with dark mode, image lightbox, giscus comments, RSS, keyboard navigation, and reading progress indicator. Built via AI pair programming; **MIT licensed, open source**.
- [Live Blog](https://sai21112000.github.io)
- Repo: [sai21112000.github.io](https://github.com/Sai21112000/sai21112000.github.io)

### Obsidian Plugin: Jekyll Publisher
One-click Obsidian-to-Jekyll converter with automated frontmatter, image copying, and intelligent filename generation. **~8KB, zero dependencies.**
- Bridges knowledge management (Obsidian) and blogging (Jekyll) workflows
- Repo: [obsidian-jekyll-publisher](https://github.com/Sai21112000/obsidian-jekyll-publisher)

### HTML Table Structured Data Scraper
Browser console utility for extracting structured data from HTML tables and forms. Zero external dependencies; designed for rapid prototyping and data collection.
- Repo: [HTML-Table-Structured-Data-Scraper](https://github.com/Sai21112000/HTML-Table-Structured-Data-Scraper)

### Oil Palm Instance Segmentation (Thesis)
Detection, counting, and canopy biometry of individual oil palms from UAV imagery at multiple ground sample distances (0.03–0.20m).
- Multi-model comparison: YOLOv8, YOLOv11, Mask R-CNN, SAM hybrids
- Metrics: precision, recall, F1, IoU, crown geometry errors across 8 altitude levels
- Agent-in-the-loop annotation (80% labeling time reduction) + generative tiling for synthetic multi-altitude data

---

## 🔬 Oil Palm AI Series — Thesis Blog

A technical series documenting the full research and deployment journey:

| # | Post | Companion Repo |
|---|------|----------------|
| B1 | [The Drone That Couldn't See](https://sai21112000.github.io/posts/b1-the-drone-that-couldnt-see.html) | [uav-gsd-scale-invariance](https://github.com/Sai21112000/uav-gsd-scale-invariance) |
| B2 | [Building the Dataset Nobody Had](https://sai21112000.github.io/posts/b2-building-the-dataset-nobody-had.html) | [oil-palm-dataset-pipeline](https://github.com/Sai21112000/oil-palm-dataset-pipeline) |
| B3 | [Six Models Enter, One Problem Wins](https://sai21112000.github.io/posts/b3-six-models-enter.html) | [oil-palm-instance-segmentation](https://github.com/Sai21112000/oil-palm-instance-segmentation) |
| B4 | [The Hybrid Paradox](https://sai21112000.github.io/posts/b4-the-hybrid-paradox.html) | [hybrid-yolo-sam-pipeline](https://github.com/Sai21112000/hybrid-yolo-sam-pipeline) |
| B5 | [From Pixels to Meters](https://sai21112000.github.io/posts/b5-from-pixels-to-meters.html) | [canopy-biometry-calculator](https://github.com/Sai21112000/canopy-biometry-calculator) |
| B6 | [A Framework for Flying Smarter](https://sai21112000.github.io/posts/b6-a-framework-for-flying-smarter.html) | [uav-deployment-guide](https://github.com/Sai21112000/uav-deployment-guide) |

---

## 🚀 What I'm Optimizing For Next

- **Production-grade AI systems**: Converting research prototypes into testable, deployable, and maintainable systems with clear evaluation metrics
- **Edge & on-device vision**: Geospatial ML and vision models that run under strict latency, power, and memory constraints
- **Building Projects**: Building productivity systems utilising OCR/TTS/RAG-Chatbots that keep data local and enable fast context-switching between projects
- **Reliable, auditable agents**: Agentic AI with constraint-based reasoning, explicit control flow, and verifiable outputs (not just creative generation)

---

<p align="center"><i>"The tension you feel is not a problem to solve. It is the process."</i></p>
