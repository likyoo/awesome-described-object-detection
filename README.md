# awesome-described-object-detection
A curated list of papers and resources related to Described Object Detection, Open-Vocabulary/Open-World Object Detection and Referring Expression Comprehension.

## Table of Contents

- [Described Object Detection](#described-object-detection)
    * [Methods with Potential for DOD](#methods-with-potential-for-dod)
- [Open-Vocabulary Object Detection](#open-vocabulary-object-detection)
- [Referring Expression Comprehension](#referring-expression-comprehension)
- [Related Surveys and Resources](#related-surveys-and-resources)

## Described Object Detection

- Exposing the Troublemakers in Described Object Detection (NeurIPS 2023) [[paper]](https://arxiv.org/abs/2307.12813) [[dataset]](https://github.com/shikras/d-cube/) [[code]](https://github.com/shikras/d-cube/)

### Methods with Potential for DOD

These methods are usually capable of tasks like both OVD and REC, though they are not directly handling DOD and not evaluated on DOD benchmarks in their original papers.

- Contextual Object Detection with Multimodal Large Language Models (arxiv 2023) [[paper]](https://arxiv.org/abs/2305.18279) [[code]](https://github.com/yuhangzang/ContextDET) [[demo]](https://huggingface.co/spaces/yuhangzang/ContextDet-Demo)

- Kosmos-2: Grounding Multimodal Large Language Models to the World (arxiv 2023) [[paper]](https://arxiv.org/abs/2306.14824) [[code]](https://github.com/microsoft/unilm/tree/master/kosmos-2) [[demo]](https://huggingface.co/spaces/ydshieh/Kosmos-2)

- Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond (arxiv 2023) [[paper]](https://arxiv.org/abs/2308.12966) [[code]](https://github.com/QwenLM/Qwen-VL) [[demo]](https://modelscope.cn/studios/qwen/Qwen-VL-Chat-Demo/summary)

- Shikra: Unleashing Multimodal LLM’s Referential Dialogue Magic (arxiv 2023) [[paper]](https://arxiv.org/abs/2306.15195) [[code]](https://github.com/shikras/shikra) [[demo]](http://demo.zhaozhang.net:7860/)

- Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection (arxiv 2023) [[paper]](https://arxiv.org/abs/2303.05499) [[code (eval)]](https://github.com/IDEA-Research/GroundingDINO) (REC, OD, etc.)

- Universal Instance Perception as Object Discovery and Retrieval (CVPR 2023) [[paper]](https://arxiv.org/abs/2303.06674v2) [[code]](https://github.com/MasterBin-IIAU/UNINEXT) (REC, OVD, etc.)

- FindIt: Generalized Localization with Natural Language Queries (ECCV 2022) [[paper]](https://arxiv.org/abs/2203.17273) [[code]](https://github.com/google-research/google-research/tree/master/findit) (REC, OD, etc.)

- MDETR -- Modulated Detection for End-to-End Multi-Modal Understanding (ICCV 2021) [[paper]](https://arxiv.org/abs/2104.12763) [[code]](https://github.com/ashkamath/mdetr) [[website]](https://ashkamath.github.io/mdetr_page/)

- GRiT: A Generative Region-to-text Transformer for Object Understanding (arxiv 2022) [[paper]](https://arxiv.org/abs/2212.00280) [[code]](https://github.com/JialianW/GRiT) [[demo (colab)]](https://colab.research.google.com/github/taskswithcode/GriT/blob/master/TWCGRiT.ipynb)


## Open-Vocabulary Object Detection

- Open-Vocabulary Object Detection With an Open Corpus (ICCV 2023) [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Open-Vocabulary_Object_Detection_With_an_Open_Corpus_ICCV_2023_paper.pdf)

- Distilling DETR with Visual-Linguistic Knowledge for Open-Vocabulary Object Detection (ICCV 2023) [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Distilling_DETR_with_Visual-Linguistic_Knowledge_for_Open-Vocabulary_Object_Detection_ICCV_2023_paper.pdf) [[code (not released)]](https://github.com/hikvision-research/opera)

- Exploring Multi-Modal Contextual Knowledge for Open-Vocabulary Object Detection (arxiv 2023) [[paper]](https://arxiv.org/abs/2308.15846)

- How to Evaluate the Generalization of Detection? A Benchmark for Comprehensive Open-Vocabulary Detection (arxiv 2023) [[paper]](https://arxiv.org/abs/2308.13177) [[dataset]](https://github.com/om-ai-lab/OVDEval)

- Improving Pseudo Labels for Open-Vocabulary Object Detection (arxiv 2023) [[paper]](https://arxiv.org/abs/2308.06412)

- Scaling Open-Vocabulary Object Detection (arxiv 2023) [[paper]](https://arxiv.org/abs/2306.09683) [[code (jax)]](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit)

- Unified Open-Vocabulary Dense Visual Prediction (arxiv 2023) [[paper]](https://arxiv.org/abs/2307.08238)

- Open-Vocabulary Object Detection via Scene Graph Discovery (arxiv 2023) [[paper]](https://arxiv.org/abs/2307.03339)

- A Simple Framework for Open-Vocabulary Segmentation and Detection (arXiv 2023) [[paper]](https://arxiv.org/abs/2303.08131) [[code]](https://github.com/IDEA-Research/OpenSeeD)

- Three Ways to Improve Feature Alignment for Open Vocabulary Detection (arXiv 2023) [[paper]](https://arxiv.org/abs/2303.13518)

- Prompt-Guided Transformers for End-to-End Open-Vocabulary Object Detection (arXiv 2023) [[paper]](https://arxiv.org/abs/2303.14386)

- Open-Vocabulary Object Detection using Pseudo Caption Labels (arXiv 2023) [[paper]](https://arxiv.org/abs/2303.13040)

- What Makes Good Open-Vocabulary Detector: A Disassembling Perspective (KDD Workshop) [[paper]](https://arxiv.org/abs/2309.00227)

- EdaDet: Open-Vocabulary Object Detection Using Early Dense Alignment (ICCV 2023) [[paper]](https://arxiv.org/abs/2309.01151) [[website]](https://chengshiest.github.io/edadet/)

- Contrastive Feature Masking Open-Vocabulary Vision Transformer (ICCV 2023) [[paper]](https://arxiv.org/abs/2309.00775)

- Multi-Modal Classifiers for Open-Vocabulary Object Detection (ICML 2023) [[paper]](http://arxiv.org/abs/2306.05493) [[code (eval)]](https://github.com/prannaykaul/mm-ovod)

- CORA: Adapting CLIP for Open-Vocabulary Detection with Region Prompting and Anchor Pre-Matching (CVPR 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_CORA_Adapting_CLIP_for_Open-Vocabulary_Detection_With_Region_Prompting_and_CVPR_2023_paper.pdf) [[code]](https://github.com/tgxs002/CORA)

- Object-Aware Distillation Pyramid for Open-Vocabulary Object Detection (CVPR 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Object-Aware_Distillation_Pyramid_for_Open-Vocabulary_Object_Detection_CVPR_2023_paper.pdf) [[code]](https://github.com/LutingWang/OADP)

- Aligning Bag of Regions for Open-Vocabulary Object Detection (CVPR 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Aligning_Bag_of_Regions_for_Open-Vocabulary_Object_Detection_CVPR_2023_paper.pdf) [[code]](https://github.com/wusize/ovdet)

- Region-Aware Pretraining for Open-Vocabulary Object Detection with Vision Transformers (CVPR 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Kim_Region-Aware_Pretraining_for_Open-Vocabulary_Object_Detection_With_Vision_Transformers_CVPR_2023_paper.pdf) [[code]](https://github.com/google-research/google-research/tree/master/fvlm/rovit)

- DetCLIPv2: Scalable Open-Vocabulary Object Detection Pre-training via Word-Region Alignment (CVPR 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Yao_DetCLIPv2_Scalable_Open-Vocabulary_Object_Detection_Pre-Training_via_Word-Region_Alignment_CVPR_2023_paper.pdf)

- Learning to Detect and Segment for Open Vocabulary Object Detection (CVPR 2023) [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Learning_To_Detect_and_Segment_for_Open_Vocabulary_Object_Detection_CVPR_2023_paper.pdf)

- F-VLM: Open-Vocabulary Object Detection upon Frozen Vision and Language Models (ICLR 2023) [[paper]](https://openreview.net/pdf?id=MIMwy4kh9lf) [[code]] (https://github.com/google-research/google-research/tree/master/fvlm) [[website]](https://sites.google.com/view/f-vlm/home)

- Learning Object-Language Alignments for Open-Vocabulary Object Detection (ICLR 2023) [[paper]](https://openreview.net/pdf?id=mjHlitXvReu) [[code]](https://github.com/clin1223/VLDet)

- Simple Open-Vocabulary Object Detection with Vision Transformers (ECCV 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136700714.pdf) [[code (jax)]](https://github.com/google-research/scenic/tree/main/scenic/projects/owl_vit) [[code (huggingface)]](https://huggingface.co/docs/transformers/model_doc/owlvit)

## Referring Expression Comprehension

- ONE-PEACE: Exploring One General Representation Model Toward Unlimited Modalities [[paper]](https://arxiv.org/abs/2305.11172) [[code]](https://github.com/OFA-Sys/ONE-PEACE)

- OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework (ICML 2022) [[paper]](https://arxiv.org/abs/2202.03052) [[code]](https://github.com/OFA-Sys/OFA)

- PolyFormer: Referring Image Segmentation as Sequential Polygon Generation (CVPR 2023) [[paper]](https://arxiv.org/abs/2302.07387) [[website]](https://polyformer.github.io/) [[code]](https://github.com/amazon-science/polygon-transformer) [[demo]](https://huggingface.co/spaces/koajoel/PolyFormer)

- DQ-DETR: Dual Query Detection Transformer for Phrase Extraction and Grounding (AAAI 2023) [[paper]](https://arxiv.org/abs/2211.15516) [[code]](https://github.com/IDEA-Research/DQ-DETR)

- Referring Transformer: A One-step Approach to Multi-task Visual Grounding (NeurIPS 2021) [[paper]](https://arxiv.org/abs/2106.03089) [[code]](https://github.com/ubc-vision/RefTR)

- Large-Scale Adversarial Training for Vision-and-Language Representation Learning (NIPS 2023 Spotlight) [[paper]](https://arxiv.org/abs/2006.06195) [[code]](https://github.com/zhegan27/VILLA) [[poster]](https://zhegan27.github.io/Papers/villa_poster.pdf)

- UNITER: UNiversal Image-TExt Representation Learning (ECCV 2020) [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750103.pdf) [[code]](https://github.com/ChenRocks/UNITER)

- Multi-task Collaborative Network for Joint Referring Expression Comprehension and Segmentation (CVPR 2020) [[paper]](https://arxiv.org/abs/2003.08813) [[code]](https://github.com/luogen1996/MCN)

- MAttNet: Modular Attention Network for Referring Expression Comprehension (CVPR 2018) [[paper]](https://arxiv.org/abs/1801.08186) [[code]](https://github.com/lichengunc/MAttNet)


## Related Surveys and Resources

Some survey papers regarding relevant tasks (open-vocabulary learning, etc.)

- Towards Open Vocabulary Learning: A Survey (arxiv 2023) [[paper]](https://arxiv.org/abs/2306.15880) [[repo]](https://github.com/jianzongwu/Awesome-Open-Vocabulary)
- A Survey on Open-Vocabulary Detection and Segmentation: Past, Present, and Future (arxiv 2023) [[paper]](https://arxiv.org/abs/2307.09220)

Some similar github repos like awesome lists:

- [daqingliu/awesome-rec](https://github.com/daqingliu/awesome-rec): A curated list of REC papers. Not maintained in recent years.
- [qy-feng/awesome-visual-grounding](https://github.com/qy-feng/awesome-visual-grounding): A curated list of visual grounding papers. Not maintained in recent years.
- [MarkMoHR/Awesome-Referring-Image-Segmentation](https://github.com/MarkMoHR/Awesome-Referring-Image-Segmentation): A list of Referring Expression Segmentation (RES) papers and resources.
- [TheShadow29/awesome-grounding](https://github.com/TheShadow29/awesome-grounding): A list of visual grounding (REC) paper roadmaps and datasets.
