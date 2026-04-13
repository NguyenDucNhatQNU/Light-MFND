 
# Light-MFND: Efficient Multimodal Fake News Detection via Fine-Tuned Small Vision-Language Models
 
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)

[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)

[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/docs/transformers/index)

[![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)](https://github.com/huggingface/peft)
 
---

## Abstract

Multimodal fake news on social media often couples manipulated imagery with deceptive text to mislead audiences. While large Vision-Language Models (LVLMs) offer robust reasoning capabilities, their immense computational requirements hinder deployment in resource-constrained environments. That is why we propose Light-MFND, a framework utilising fine-tuned Small Vision-Language Models (SVLMs) for efficient fake news detection. Our proposed approach is designed to implement a lightweight dual-encoder architecture and a dedicated fusion module for detecting semantic inconsistencies between modalities. Efficiency is achieved through Parameter-Efficient Fine-Tuning (PEFT) by employing Low-Rank Adaptation (LoRA) and selective layer freezing. Moreover, we integrate multimodal alignment that explicitly models cross-modal coherence, which facilitates the identification of subtle discrepancies. Benchmark evaluations demonstrate that Light-MFND achieves competitive accuracy while significantly reducing model size and inference latency by utilising LoRA, yielding F1 scores of 99.8\% and 70.8\% on in-domain and out-of-domain test sets, respectively. These results suggest that compact SVLMs provide a scalable and practical solution for real-time detection in limited-resource settings.
 
## Citation

If you use this code or our results in your research, please cite our paper:
 
```bibtex

@article{Nguyen2026,

  title={Light-MFND: Efficient Multimodal Fake News Detection via Fine-Tuned Small Vision-Language Models},

  author={Nguyen, Duc-Nhat and Phan, Khac-Lap and Le, Quang-Hung},

  year={2026}

}
 
