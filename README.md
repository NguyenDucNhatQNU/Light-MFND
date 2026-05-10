# Light-MFND: Efficient Multimodal Fake News Detection via Fine-Tuned Small Vision-Language Models

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange)](https://pytorch.org/)
[![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/docs/transformers/index)
[![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)](https://github.com/huggingface/peft)

---

## Abstract

This paper addresses the problem of multimodal fake news detection in achieving a balance between performance and computational efficiency. We propose Light-MFND, a novel framework based on fine-tuning small vision-language model for detecting multimodal fake news. The proposed framework employs a lightweight dual-encoder architecture to extract semantic representations and a cross-modal fusion module to capture inter-modal interactions and detects semantic inconsistencies. We leverage parameter-efficient fine-tuning techniques such as adapters, prompt tuning, and low-rank adaptation to reduce the computational cost. Our experiments on the two benchmark datasets demonstrate the effectiveness and efficiency of the proposed method compared with baselines. Particularly, Light-MFND achieves competitive performance to larger vision-language model-based baseline, while requiring significantly fewer trainable parameters, shorter inference times, and lower hardware cost. These results show the potential of fine-tuned small vision-language models for detecting multimodal fake news in real-world environments, especially in edge computing and low-resource settings.

## Citation

If you use this code or our results in your research, please cite our paper:

```bibtex
@article{Nguyen2026,
  title={Light-MFND: Efficient Multimodal Fake News Detection via Fine-Tuned Small Vision-Language Models},
  author={Nguyen, Duc-Nhat and Phan, Khac-Lap and Le, Quang-Hung},
  year={2026}
}
```
