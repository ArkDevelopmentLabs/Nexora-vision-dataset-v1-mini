# Nexora Vision Dataset v1 mini

A compact preview version of the Nexora Vision Dataset, containing 100–500 curated multi-genre AI-generated images for research, experimentation, and model evaluation.  
Developed and curated by **ArkDevelopmentLabs / ArkAiLab (ADL)**.

---

## Overview
Nexora Vision Dataset v1 Mini includes a small subset of cinematic, realistic, anime, sci-fi, and artistic images from the full Nexora Vision Dataset.  
This mini release is intended to provide an early accessible version to test dataset pipelines, metadata structure, and training workflows before the full-scale release.

Suitable for:
- Initial testing of LoRA / DreamBooth / SDXL training
- Fine-tuning sample models with lightweight datasets
- Research, benchmarking, and dataset evaluation
- Demonstrating workflow and structure for v1 full release

---

## Key Features
- Contains 100–500 curated images
- Multiple categories and visual styles
- Simple and clean metadata format (`prompts.json`)
- Lightweight size for rapid download and training
- Released under MIT license for open usage
- Designed as a preview for the full Nexora Vision Dataset v1

---

## Dataset Structure
```
Nexora-vision-dataset-v1/
├─ images/
│ ├─ anime/
│ ├─ cinematic/
│ ├─ realistic/
│ ├─ sci-fi/
│ └─ artistic/
├─ metadata/
│ ├─ prompts.json
│ ├─ prompts.parquet
├─ previews/
├─ LICENSE
└─ README.md
```
prompt.json structure
```json
{
  "id": "00001",
  "file_name": "anime/00001.png",
  "prompt": "anime girl cherry blossoms, soft lighting, 4k highly detailed",
  "negative_prompt": "blurry, watermark, distorted face",
}
```
## License

Released under the MIT License, permitting academic, research, and commercial usage.

We appreciate attribution. If you use this dataset in research, training, or publications,
please consider crediting: Aniruddha (JackMa) — ArkDevelopmentLab / ArkAiLab (ADL)

## How to Use (Hugging Face Example)
```python
from datasets import load_dataset

dataset = load_dataset("ArkAiLab-Adl/Nexora-vision-dataset-v1")
print(dataset)
```
## Download

**Hugging Face**
https://huggingface.co/datasets/ArkAiLab-Adl/Nexora-vision-dataset-v1-mini

**GitHub**
https://github.com/ArkDevelopmentLabs/Nexora-vision-dataset-v1-mini

## Credits

Developed by **ArkDevelopmentLabs (ADL)**
Dataset creator: **JackMa and Ari (ArkDevelopmentLab / ArkAiLab)**

If you build a model using this dataset, citing **Nexora Vision Dataset v1 mini** is appreciated.

