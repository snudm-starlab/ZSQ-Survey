# ZSQ Survey

This repository contains a comprehensive paper list of **Zero-shot Quantization** (ZSQ).
If you find this content helpful, please consider to star [this repository](https://github.com/snudm-starlab/ZSQ-Survey) and cite our [survey paper]().

**[Update: May, 2025]** [The repository](https://github.com/snudm-starlab/ZSQ-Survey) has been released to the public!

**[Update: Apr., 2025]** Our [survey paper]() on zero-shot quantization has been accepted to [IJCAI 2025](https://2025.ijcai.org/) Survey Track!

### Reference
```bibtex
@inproceedings{KimCLCK25,
    title={Zero-shot Quantization: A Comprehensive Survey},
    author={Kim, Minjun and Choi, Jaehyeon and Lee, Jongkeun and Cho, Wonjin and Kang, U},
    booktitle={The 34th International Joint Conference on Artificial Intelligence},
    year={2025}
}
```

---

## Table of Contents

- [ZSQ Survey](#zsq-survey)
  - [Reference](#reference)
- [Zero-shot Quantization](#zero-shot-quantization)
  - [Synthesis-free ZSQ](#synthesis-free-zsq)
  - [Generator-based ZSQ](#generator-based-zsq)
  - [Noise-optimization-based ZSQ](#noise-optimization-based-zsq)

---

## Zero-shot Quantization

**Keywords** 
- **Training Requirement**: **`PTQ`**: Post-training Quantization / **`QAT`**: Quantization-aware Training
- **Scope of Contribution**: **`Syn`**: Data Synthesis / **`Quant`**: Network Quantization / **`S+Q`** Both
- **Target Architecture**: **`CNN`**: Convolutional Neural Networks / **`ViT`**: Vision Transformers / **`C+V`** Both


### Synthesis-free ZSQ
- **[ICCV 2023]** Unified Data-Free Compression: Pruning and Quantization without Fine-Tuning [**`PTQ`, `Quant`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2308.07209-b31b1b.svg)](https://arxiv.org/abs/2308.07209) [![Invalid Link Code](https://img.shields.io/badge/code-invalid-purple.svg)](https://github.com/Dtudy/UDFC) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/ICCV2023/papers/Bai_Unified_Data-Free_Compression_Pruning_and_Quantization_without_Fine-Tuning_ICCV_2023_paper.pdf)
  
- **[ICLR 2022]** SQuant: On-the-Fly Data-Free Quantization via Diagonal Hessian Approximation [**`PTQ`, `Quant`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2202.07471-b31b1b.svg)](https://arxiv.org/abs/2202.07471) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/clevercool/SQuant) [![ICLR](https://img.shields.io/badge/pdf-iclr-A5D54C.svg)](https://openreview.net/pdf?id=JXhROKNZzOc) 

- **[ICCV 2019]** Data-Free Quantization Through Weight Equalization and Bias Correction [**`PTQ`, `Quant`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-1906.04721-b31b1b.svg)](https://arxiv.org/abs/1906.04721) [![Unofficial Code](https://img.shields.io/badge/code-unofficial-FFFF00.svg)](https://github.com/jakc4103/DFQ) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nagel_Data-Free_Quantization_Through_Weight_Equalization_and_Bias_Correction_ICCV_2019_paper.pdf) 

### Generator-based ZSQ
- **[ECCV 2024]** GenQ: Quantization in Low Data Regimes with Generative Synthetic [**`QAT`, `Syn`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2312.05272-b31b1b.svg)](https://arxiv.org/abs/2312.05272) [![Invalid Link Code](https://img.shields.io/badge/code-invalid-purple.svg)](https://github.com/Intelligent-Computing-Lab-Yale/GenQ) [![ecva](https://img.shields.io/badge/pdf-ecva-7395C5.svg)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02058.pdf)
  
- **[AAAI 2024]** Robustness-Guided Image Synthesis for Data-Free Quantization [**`QAT`, `Syn`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2310.03661-b31b1b.svg)](https://arxiv.org/abs/2310.03661) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![AAAI](https://img.shields.io/badge/pdf-aaai-003973.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/28972)
  
- **[ICCV 2023]** Causal-DFQ: Causality Guided Data-free Network Quantization [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2309.13682-b31b1b.svg)](https://arxiv.org/abs/2309.13682) [![Invalid Link Code](https://img.shields.io/badge/code-invalid-purple.svg)](https://github.com/42Shawn/Causal-DFQ?tab=readme-ov-file) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/ICCV2023/papers/Shang_Causal-DFQ_Causality_Guided_Data-Free_Network_Quantization_ICCV_2023_paper.pdf)
  
- **[CVPR 2023]** Adaptive Data-Free Quantization [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2303.06869-b31b1b.svg)](https://arxiv.org/abs/2303.06869) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/hfutqian/AdaDFQ) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Qian_Adaptive_Data-Free_Quantization_CVPR_2023_paper.pdf)
  
- **[AAAI 2023]** Rethinking Data-Free Quantization as a Zero-Sum Game [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2302.09572-b31b1b.svg)](https://arxiv.org/abs/2302.09572) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/hfutqian/AdaSG) [![AAAI](https://img.shields.io/badge/pdf-aaai-003973.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/26136)
  
- **[CVPR 2022]** It’s All In the Teacher: Zero-Shot Quantization Brought Closer to the Teacher [**`QAT`, `Quant`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2203.17008-b31b1b.svg)](https://arxiv.org/abs/2203.17008) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/iamkanghyunchoi/ait) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2022/papers/Choi_Its_All_in_the_Teacher_Zero-Shot_Quantization_Brought_Closer_to_CVPR_2022_paper.pdf)
  
- **[NeurIPS 2021]** Qimera: Data-free Quantization with Synthetic Boundary Supporting Samples [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2111.02625-b31b1b.svg)](https://arxiv.org/abs/2111.02625) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/iamkanghyunchoi/qimera) [![NeurIPS](https://img.shields.io/badge/pdf-neurips-8D689F.svg)](https://proceedings.neurips.cc/paper/2021/file/7cc234202e98d2722580858573fd0817-Paper.pdf)

- **[IJCAI 2021]** AutoReCon: Neural Architecture Search-based Reconstruction for Data-free Compression	[**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2105.12151-b31b1b.svg)](https://arxiv.org/abs/2105.12151) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![IJCAI](https://img.shields.io/badge/pdf-ijcai-053AC2.svg)](https://www.ijcai.org/proceedings/2021/0478.pdf)
  
- **[CVPR 2021]** Zero-shot Adversarial Quantization [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2103.15263-b31b1b.svg)](https://arxiv.org/abs/2103.15263) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/FLHonker/ZAQ-code) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Zero-Shot_Adversarial_Quantization_CVPR_2021_paper.pdf)
  
- **[ECCV 2020]** Generative Low-bitwidth Data Free Quantization [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2003.03603-b31b1b.svg)](https://arxiv.org/abs/2003.03603) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/xushoukai/GDFQ) [![ecva](https://img.shields.io/badge/pdf-ecva-7395C5.svg)](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570001.pdf)
  
- **[CVPRW 2020]** Data-Free Network Quantization With Adversarial Knowledge Distillation	DFQ-AKD	[**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2005.04136-b31b1b.svg)](https://arxiv.org/abs/2005.04136) [![Unofficial Code](https://img.shields.io/badge/code-unofficial-FFFF00.svg)](https://github.com/da2so/Data-Free_Network_Quantization_With_Adversarial_Knowledge_Distillation) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w40/Choi_Data-Free_Network_Quantization_With_Adversarial_Knowledge_Distillation_CVPRW_2020_paper.pdf) 


### Noise-optimization-based ZSQ

- **[ICLR 2025]** SynQ: Accurate Zero-shot Quantization by Synthesis-aware Fine-tuning [**`QAT`, `Quant`, `CNN`**] <br>
    [![No arXiv](https://img.shields.io/badge/arXiv-no_link-BBBBBB.svg)]() [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/snudm-starlab/SynQ) [![ICLR](https://img.shields.io/badge/pdf-iclr-A5D54C.svg)](https://openreview.net/pdf?id=2rnOgyFQgb) 

- **[ECCV 2024]** CLAMP-ViT: Contrastive Data-Free Learning for Adaptive Post-Training Quantization of ViTs [**`PTQ`, `S+Q`, `ViT`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2407.05266-b31b1b.svg)](https://arxiv.org/abs/2407.05266) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/georgia-tech-synergy-lab/CLAMP-ViT) [![ecva](https://img.shields.io/badge/pdf-ecva-7395C5.svg)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08434.pdf)
  
- **[ICML 2024]** Sharpness-Aware Data Generation for Zero-shot Quantization [**`PTQ`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2310.13315-b31b1b.svg)](https://arxiv.org/abs/2310.13315) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![ICML](https://img.shields.io/badge/pdf-icml-000000.svg)](https://icml.cc/virtual/2024/poster/34833)
  
- **[ICML 2024]** Sparse Model Inversion: Efficient Inversion of Vision Transformers for Data-Free Applications [**`PTQ`, `Syn`, `ViT`**] <br>
    [![No arXiv](https://img.shields.io/badge/arXiv-no_link-BBBBBB.svg)]() [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/Egg-Hu/SMI) [![ICML](https://img.shields.io/badge/pdf-icml-000000.svg)](https://icml.cc/virtual/2024/poster/33981)
  
- **[CVPR 2024]** Data-Free Quantization via Pseudo-label Filtering [**`QAT`, `Quant`, `CNN`**] <br>
    [![No arXiv](https://img.shields.io/badge/arXiv-no_link-BBBBBB.svg)]() [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2024/papers/Fan_Data-Free_Quantization_via_Pseudo-label_Filtering_CVPR_2024_paper.pdf)
  
- **[NeurIPS 2023]** TexQ: Zero-shot Network Quantization with Texture Feature Distribution Calibration [**`QAT`, `S+Q`, `CNN`**] <br>
    [![No arXiv](https://img.shields.io/badge/arXiv-no_link-BBBBBB.svg)]() [![Invalid Link Code](https://img.shields.io/badge/code-invalid-purple.svg)](https://github.com/dangsingrue/TexQ) [![NeurIPS](https://img.shields.io/badge/pdf-neurips-8D689F.svg)](https://proceedings.neurips.cc/paper_files/paper/2023/file/0113ef4642264adc2e6924a3cbbdf532-Paper-Conference.pdf)
  
- **[TNNLS 2023]** PSAQ-ViT V2: Towards Accurate and General Data-Free Quantization for Vision Transformers [**`PTQ`, `Syn`, `ViT`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2209.05687-b31b1b.svg)](https://arxiv.org/abs/2209.05687) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/zkkli/PSAQ-ViT) [![IEEE_Xplore](https://img.shields.io/badge/pdf-ieeexplore-0A70A3.svg)]()
  
- **[CVPR 2023]** Hard Sample Matters a Lot in Zero-Shot Quantization	[**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2303.13826-b31b1b.svg)](https://arxiv.org/abs/2303.13826) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/lihuantong/HAST) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Hard_Sample_Matters_a_Lot_in_Zero-Shot_Quantization_CVPR_2023_paper.pdf)
  
- **[CVPR 2023]** GENIE: Show Me the Data for Quantization [**`PTQ`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2212.04780-b31b1b.svg)](https://arxiv.org/abs/2212.04780) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/SamsungLabs/Genie) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Jeon_Genie_Show_Me_the_Data_for_Quantization_CVPR_2023_paper.pdf)
  
- **[ECCV 2022]** Patch Similarity Aware Data-Free Quantization for Vision Transformers [**`PTQ`, `Syn`, `ViT`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2203.02250-b31b1b.svg)](https://arxiv.org/abs/2203.02250) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/zkkli/PSAQ-ViT) [![ecva](https://img.shields.io/badge/pdf-ecva-7395C5.svg)](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136710154.pdf)
  
- **[CVPR 2022]** IntraQ: Learning Synthetic Images with Intra-Class Heterogeneity for Zero-Shot Network Quantization [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2111.09136-b31b1b.svg)](https://arxiv.org/abs/2111.09136) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/zysxmu/IntraQ) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhong_IntraQ_Learning_Synthetic_Images_With_Intra-Class_Heterogeneity_for_Zero-Shot_Network_CVPR_2022_paper.pdf)
  
- **[ICCV 2021]** MixMix: All You Need for Data-Free Compression Are Feature and Data Mixing [**`PTQ`, `Syn`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2011.09899-b31b1b.svg)](https://arxiv.org/abs/2011.09899) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_MixMix_All_You_Need_for_Data-Free_Compression_Are_Feature_and_ICCV_2021_paper.pdf)
  
- **[CVPRW 2021]** Generative Zero-shot Network Quantization [**`QAT`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2101.08430-b31b1b.svg)](https://arxiv.org/abs/2101.08430) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2021W/ECV/papers/He_Generative_Zero-Shot_Network_Quantization_CVPRW_2021_paper.pdf)
  
- **[CVPR 2021]** Diversifying Sample Generation for Accurate Data-Free Quantization [**`PTQ`, `Syn`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2103.01049-b31b1b.svg)](https://arxiv.org/abs/2103.01049) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Diversifying_Sample_Generation_for_Accurate_Data-Free_Quantization_CVPR_2021_paper.pdf)
  
- **[CVPR 2020]** Dreaming to distill: Data-free knowledge transfer via deepinversion [**`QAT`, `Syn`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-1912.08795-b31b1b.svg)](https://arxiv.org/abs/1912.08795) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/NVlabs/DeepInversion) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yin_Dreaming_to_Distill_Data-Free_Knowledge_Transfer_via_DeepInversion_CVPR_2020_paper.pdf)
  
- **[CVPR 2020]** ZeroQ: A Novel Zero Shot Quantization Framework [**`PTQ`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-2001.00281-b31b1b.svg)](https://arxiv.org/abs/2001.00281) [![Code](https://img.shields.io/badge/code-github-A7594E.svg)](https://github.com/amirgholami/ZeroQ) [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_ZeroQ_A_Novel_Zero_Shot_Quantization_Framework_CVPR_2020_paper.pdf)
  
- **[CVPR 2020]** The Knowledge Within: Methods for Data-Free Model Compression [**`PTQ`, `S+Q`, `CNN`**] <br>
    [![arXiv](https://img.shields.io/badge/arXiv-1912.01274-b31b1b.svg)](https://arxiv.org/abs/1912.01274) [![No Link Code](https://img.shields.io/badge/code-no_link-FF0000.svg)]() [![thecvf](https://img.shields.io/badge/pdf-thecvf-7395C5.svg)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Haroush_The_Knowledge_Within_Methods_for_Data-Free_Model_Compression_CVPR_2020_paper.pdf)
