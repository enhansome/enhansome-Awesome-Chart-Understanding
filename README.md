# Awesome Chart Understanding with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 499,649 | 🐛 106 | 📅 2026-08-21
[![PRWelcome](https://img.shields.io/badge/PRs-Welcome-red)](https://img.shields.io/badge/PRs-Welcome-red)
[![arXiv](https://img.shields.io/badge/arXiv-2403.12027-b31b1b.svg?style=flat)](https://arxiv.org/abs/2403.12027)

**🔥🔥 Our survey paper has been accepted by IEEE TKDE! 🔥🔥**

A curated list of recent and past chart understanding work based on our IEEE TKDE survey paper: [From Pixels to Insights: A Survey on Automatic Chart Understanding in the Era of Large Foundation Models](https://arxiv.org/abs/2403.12027).

**The repository will be continuously updated 📝. Don't forget to hit the ⭐️ and stay tuned!**

**If you find this resource beneficial for your research, please do not hesitate to cite the paper referenced in the [Citation](#citation) section. Thank you!**

## Table of Contents

* [Tasks and Datasets](#tasks-and-datasets)
  * [Chart Question Answering](#chart-question-answering)
  * [Chart Captioning (Summarization)](#chart-captioning-summarization)
  * [Factual Inconsistency Detection for Chart Captioning](#factual-inconsistency-detection-for-chart-captioning)
  * [Chart Fact-checking](#chart-fact-checking)
  * [Chart Caption Factual Error Correction](#chart-caption-factual-error-correction)
  * [Chart to Code](#chart-to-code)
* [Methods](#methods)
  * [Classification-based Methods](#classification-based-methods)
  * [Generation-based Methods](#generation-based-methods)
  * [Tool Augmentation](#tool-augmentation)
* [Evaluation](#evaluation)
* [Analysis](#analysis)
* [Citation](#citation)

## Tasks and Datasets

### Chart Question Answering

**Factoid Questions**

* **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning.**

  *Ahmed Masry, Xuan Long Do, Jia Qing Tan, Shafiq Joty, Enamul Hoque.* <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/vis-nlp/ChartQA) ⭐ 261 | 🐛 9 | 🌐 Python | 📅 2025-04-18

* **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning.**

  *Fuxiao Liu, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, Dong Yu.* <img src='https://img.shields.io/badge/NAACL-2024-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/FuxiaoLiu/MMC) ⭐ 95 | 🐛 1 | 🌐 Python | 📅 2025-01-07

* **PlotQA: Reasoning over Scientific Plots.**

  *Nitesh Methani, Pritha Ganguly, Mitesh M. Khapra, Pratyush Kumar.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://arxiv.org/abs/1909.00997'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/NiteshMethani/PlotQA) ⭐ 83 | 🐛 5 | 📅 2023-06-20

* **SciGraphQA: A Large-Scale Synthetic Multi-Turn Question-Answering Dataset for Scientific Graphs.**

  *Shengzhi Li, Nima Tajbakhsh.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2308.03349'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/findalexli/SciGraphQA) ⭐ 43 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-10-25

* **DVQA: Understanding Data Visualizations via Question Answering.**

  *Kushal Kafle, Brian Price, Scott Cohen, Christopher Kanan.* <img src='https://img.shields.io/badge/CVPR-2018-yellow'> <a href='https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/kushalkafle/DVQA_dataset) ⭐ 37 | 🐛 1 | 📅 2019-06-24

* **MapQA: A Dataset for Question Answering on Choropleth Maps.**

  *Shuaichen Chang, David Palzer, Jialin Li, Eric Fosler-Lussier, Ningchuan Xiao.* <img src='https://img.shields.io/badge/Arxiv-2022-yellow'> <a href='https://arxiv.org/abs/2211.08545'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/OSU-slatelab/MapQA) ⭐ 15 | 🐛 2 | 📅 2026-01-09

* **FigureQA: An Annotated Figure Dataset for Visual Reasoning.**

  *Samira Ebrahimi Kahou, Vincent Michalski, Adam Atkinson, Akos Kadar, Adam Trischler, Yoshua Bengio.* <img src='https://img.shields.io/badge/ICLR_Workshop-2018-yellow'> <a href='https://arxiv.org/abs/1710.07300'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://www.microsoft.com/en-us/research/project/figureqa-dataset/'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **LEAF-QA: Locate, Encode & Attend for Figure Question Answering.**

  *Ritwick Chaudhry, Sumit Shekhar, Utkarsh Gupta, Pranav Maneriker, Prann Bansal, Ajay Joshi.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **STL-CQA: Structure-based Transformers with Localization and Encoding for Chart Question Answering.**

  *Hrituraj Singh, Sumit Shekhar.* <img src='https://img.shields.io/badge/EMNLP-2020-yellow'> <a href='https://aclanthology.org/2020.emnlp-main.264/'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models.**

  *Pan Lu, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, Jianfeng Gao.* <img src='https://img.shields.io/badge/ICLR-2024-yellow'> <a href='https://arxiv.org/abs/2310.02255'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/AI4Math/MathVista'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **ChartBench: A Benchmark for Complex Visual Reasoning in Charts.**

  *Zhengzhuo Xu, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, Jian Guo.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.15915'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/SincereX/ChartBench'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **Multimodal ArXiv: A Dataset for Improving Scientific Comprehension of Large Vision-Language Models.**

  *Lei Li, Yuqi Wang, Runxin Xu, Peiyi Wang, Xiachong Feng, Lingpeng Kong, Qi Liu.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2403.00231'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/MMInstruction/ArxivQA'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **Evaluating Task-based Effectiveness of MLLMs on Charts.**

  *Yifan Wu, Lutao Yan, Yuyu Luo, Yunhai Wang, Nan Tang.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2405.07001'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://anonymous.4open.science/r/ChartInsights-D43E'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs.**

  *Zirui Wang, Mengzhou Xia, Luxi He, Howard Chen, Yitao Liu, Richard Zhu, Kaiqu Liang, Xindi Wu, Haotian Liu, Sadhika Malladi, Alexis Chevalier, Sanjeev Arora, Danqi Chen.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/pdf/2406.18521'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/princeton-nlp/CharXiv'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **ChartMoE: Mixture of Expert Connector for Advanced Chart Understanding.**

  *Zhengzhuo Xu⁺, Bowen Qu⁺, Yiyan Qi⁺, Sinan Du, Chengjin Xu, Chun Yuan, Jian Guo.* <img src='https://img.shields.io/badge/ICLR-2025-yellow'> <a href='https://arxiv.org/abs/2409.03277'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/IDEA-FinAI/chartmoe'><img src='https://img.shields.io/badge/Model-red'></a>

**Long-form Questions**

* **OpenCQA: Open-ended Question Answering with Charts.**

  *Shankar Kantharaj, Xuan Long Do, Rixie Tiffany Leong, Jia Qing Tan, Enamul Hoque, Shafiq Joty.* <img src='https://img.shields.io/badge/EMNLP-2022-yellow'> <a href='https://aclanthology.org/2022.emnlp-main.811/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/vis-nlp/OpenCQA) ⭐ 14 | 🐛 2 | 🌐 OpenEdge ABL | 📅 2023-06-20

### Chart Captioning (Summarization)

* **Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model.**

  *Jason Obeid, Enamul Hoque.* <img src='https://img.shields.io/badge/INLG-2020-yellow'> <a href='https://aclanthology.org/2020.inlg-1.20/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/JasonObeid/Chart2Text) ⭐ 160 | 🐛 25 | 🌐 Python | 📅 2023-07-23

* **Chart-to-Text: A Large-Scale Benchmark for Chart Summarization.**

  *Shankar Kantharaj, Rixie Tiffany Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, Shafiq Joty.* <img src='https://img.shields.io/badge/ACL-2022-yellow'> <a href='https://aclanthology.org/2022.acl-long.277/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/vis-nlp/Chart-to-text) ⭐ 129 | 🐛 13 | 🌐 OpenEdge ABL | 📅 2024-07-14

* **VisText: A Benchmark for Semantically Rich Chart Captioning.**

  *Benny Tang, Angie Boggust, Arvind Satyanarayan.* <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.401/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/mitvis/vistext) ⭐ 96 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2025-08-10

* **SciCap: Generating Captions for Scientific Figures.**

  *Ting-Yao Hsu, C Lee Giles, Ting-Hao Huang.* <img src='https://img.shields.io/badge/EMNLP-2021-yellow'> <a href='https://aclanthology.org/2021.findings-emnlp.277/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/tingyaohsu/SciCap) ⭐ 59 | 🐛 2 | 📅 2021-11-05

* **ChartSumm: A Comprehensive Benchmark for Automatic Chart Summarization of Long and Short Summaries.**

  *Raian Rahman, Rizvi Hasan, Abdullah Al Farhad, Md Tahmid Rahman Laskar, Md. Hamjajul Ashmafee, Abu Raihan Mostofa Kamal.* <img src='https://img.shields.io/badge/Canadian_AI-2023-yellow'> <a href='https://arxiv.org/abs/2304.13620'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/pranonrahman/ChartSumm) ⭐ 11 | 🐛 2 | 📅 2023-07-20

* **LineCap: Line Charts for Data Visualization Captioning Models.**

  *Anita Mahinpei, Zona Kostic, Chris Tanner.* <img src='https://img.shields.io/badge/IEEE_VIS-2022-yellow'> <a href='https://ieeexplore.ieee.org/abstract/document/9973197'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/anita76/LineCapDataset) ⭐ 2 | 🐛 0 | 📅 2022-07-18

* **Neural Data-Driven Captioning of Time-Series Line Charts.**

  *Andrea Spreafico, Giuseppe Carenini.* <img src='https://img.shields.io/badge/AVI-2020-yellow'> <a href='https://dl.acm.org/doi/abs/10.1145/3399715.3399829'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **Figure Captioning with Relation Maps for Reasoning.**

  *Charles Chen, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, Ryan Rossi.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **What Will You Tell Me About the Chart? – Automated Description of Charts.**

  *Karolina Seweryn, Katarzyna Lorenc, Anna Wróblewska, Sylwia Sysko-Romańczuk.* <img src='https://img.shields.io/badge/ICONIP-2021-yellow'> <a href='https://link.springer.com/chapter/10.1007/978-3-030-92307-5_2'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **FigCaps-HF: A Figure-to-Caption Generative Framework and Benchmark with Human Feedback.**

  *Ashish Singh, Prateek Agarwal, Zixuan Huang, Arpita Singh, Tong Yu, Sungchul Kim, Victor Bursztyn, Nikos Vlassis, Ryan A. Rossi.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2307.10867'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://figcapshf.github.io/'><img src='https://img.shields.io/badge/Dataset-red'></a>

* **Multimodal ArXiv: A Dataset for Improving Scientific Comprehension of Large Vision-Language Models.**

  *Lei Li, Yuqi Wang, Runxin Xu, Peiyi Wang, Xiachong Feng, Lingpeng Kong, Qi Liu.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2403.00231'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/MMInstruction/ArxivCap'><img src='https://img.shields.io/badge/Dataset-red'></a>

### Factual Inconsistency Detection for Chart Captioning

* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.**

  *Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji.* <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/khhuang/CHOCOLATE'><img src='https://img.shields.io/badge/Dataset-red'></a>

### Chart Fact-checking

* **Reading and Reasoning over Chart Images for Evidence-based Automated Fact-Checking.**

  *Mubasharar Akhtar, Oana Cocarascu, Elena Simperl.* <img src='https://img.shields.io/badge/EACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-eacl.30/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/mubasharaak/ChartFC_chartBERT) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-06-18

* **ChartCheck: An Evidence-Based Fact-Checking Dataset over Real-World Chart Images.**

  *Mubashara Akhtar, Nikesh Subedi, Vivek Gupta, Sahar Tahmasebi, Oana Cocarascu, Elena Simperl.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.07453'><img src='https://img.shields.io/badge/PDF-blue'></a>

### Chart Caption Factual Error Correction

* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.**

  *Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji.* <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/khhuang/CHOCOLATE'><img src='https://img.shields.io/badge/Dataset-red'></a>

### Chart to Code

* **ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation.**

  *Chufan Shi, Cheng Yang, Yaxin Liu, Bo Shui, Junjie Wang, Mohan Jing, Linran Xu, Xinyu Zhu, Siheng Li, Yuxiang Zhang, Gongye Liu, Xiaomei Nie, Deng Cai, Yujiu Yang* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2406.09961'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/ChartMimic/ChartMimic) ⭐ 134 | 🐛 0 | 🌐 Python | 📅 2025-12-19

* **Text2Chart31: Instruction Tuning for Chart Generation with Automatic Feedback.** <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://arxiv.org/abs/2410.04064'><img src='https://img.shields.io/badge/PDF-blue'></a> [<img src='https://img.shields.io/badge/Dataset-red'>](https://github.com/fatemehpesaran310/Text2Chart31) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2024-10-15

  *Fatemeh Pesaran Zadeh, Juyeon Kim, Jin-Hwa Kim, Gunhee Kim.*

* **ChartMoE: Mixture of Expert Connector for Advanced Chart Understanding.**

  *Zhengzhuo Xu⁺, Bowen Qu⁺, Yiyan Qi⁺, Sinan Du, Chengjin Xu, Chun Yuan, Jian Guo.* <img src='https://img.shields.io/badge/ICLR-2025-yellow'> <a href='https://arxiv.org/abs/2409.03277'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/IDEA-FinAI/chartmoe'><img src='https://img.shields.io/badge/Model-red'></a>

## Methods

### Classification-based Methods

#### Fixed Output Vocab

* **A Simple Neural Network Module for Relational Reasoning.**

  *Adam Santoro, David Raposo, David G.T. Barrett, Mateusz Malinowski, Razvan Pascanu, Peter Battaglia, Timothy Lillicrap.* <img src='https://img.shields.io/badge/NeurIPS-2017-yellow'> <a href='https://papers.nips.cc/paper_files/paper/2017/hash/e6acf4b0f69f6f6e60e9a815938aa1ff-Abstract.html'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/kimhc6028/relational-networks) ⭐ 816 | 🐛 9 | 🌐 Python | 📅 2022-12-06

* **DVQA: Understanding Data Visualizations via Question Answering.**

  *Kushal Kafle, Brian Price, Scott Cohen, Christopher Kanan.* <img src='https://img.shields.io/badge/CVPR-2018-yellow'> <a href='https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/kushalkafle/DVQA_dataset) ⭐ 37 | 🐛 1 | 📅 2019-06-24

* **MapQA: A Dataset for Question Answering on Choropleth Maps.**

  *Shuaichen Chang, David Palzer, Jialin Li, Eric Fosler-Lussier, Ningchuan Xiao.* <img src='https://img.shields.io/badge/Arxiv-2022-yellow'> <a href='https://arxiv.org/abs/2211.08545'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/OSU-slatelab/MapQA) ⭐ 15 | 🐛 2 | 📅 2026-01-09

#### Dynamic Encoding

* **PlotQA: Reasoning over Scientific Plots.**

  *Nitesh Methani, Pritha Ganguly, Mitesh M. Khapra, Pratyush Kumar.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://arxiv.org/abs/1909.00997'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/NiteshMethani/PlotQA) ⭐ 83 | 🐛 5 | 📅 2023-06-20

* **DVQA: Understanding Data Visualizations via Question Answering.**

  *Kushal Kafle, Brian Price, Scott Cohen, Christopher Kanan.* <img src='https://img.shields.io/badge/CVPR-2018-yellow'> <a href='https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/kushalkafle/DVQA_dataset) ⭐ 37 | 🐛 1 | 📅 2019-06-24

* **Answering Questions about Data Visualizations using Efficient Bimodal Fusion.**

  *Kushal Kafle, Robik Shrestha, Brian Price, Scott Cohen, Christopher Kanan.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Kafle_Answering_Questions_about_Data_Visualizations_using_Efficient_Bimodal_Fusion_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>\
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/kushalkafle/PReFIL) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2021-06-22

* **LEAF-QA: Locate, Encode & Attend for Figure Question Answering.**

  *Ritwick Chaudhry, Sumit Shekhar, Utkarsh Gupta, Pranav Maneriker, Prann Bansal, Ajay Joshi.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

#### Pre-trained

* **TaPas: Weakly Supervised Table Parsing via Pre-training.**

  *Jonathan Herzig, Pawel Krzysztof Nowak, Thomas Müller, Francesco Piccinno, Julian Eisenschlos.* <img src='https://img.shields.io/badge/ACL-2020-yellow'> <a href='https://aclanthology.org/2020.acl-main.398/'><img src='https://img.shields.io/badge/PDF-blue'></a>\
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/google-research/tapas) ⚠️ Archived

* **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning.**

  *Ahmed Masry, Xuan Long Do, Jia Qing Tan, Shafiq Joty, Enamul Hoque.* <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/vis-nlp/ChartQA) ⭐ 261 | 🐛 9 | 🌐 Python | 📅 2025-04-18

* **STL-CQA: Structure-based Transformers with Localization and Encoding for Chart Question Answering.**

  *Hrituraj Singh, Sumit Shekhar.* <img src='https://img.shields.io/badge/EMNLP-2020-yellow'> <a href='https://aclanthology.org/2020.emnlp-main.264/'><img src='https://img.shields.io/badge/PDF-blue'></a>

### Generation-based Methods

#### Without Pre-training

* **Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model.**

  *Jason Obeid, Enamul Hoque.* <img src='https://img.shields.io/badge/INLG-2020-yellow'> <a href='https://aclanthology.org/2020.inlg-1.20/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/JasonObeid/Chart2Text) ⭐ 160 | 🐛 25 | 🌐 Python | 📅 2023-07-23

* **SciCap: Generating Captions for Scientific Figures.**

  *Ting-Yao Hsu, C Lee Giles, Ting-Hao Huang.* <img src='https://img.shields.io/badge/EMNLP-2021-yellow'> <a href='https://aclanthology.org/2021.findings-emnlp.277/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/tingyaohsu/SciCap) ⭐ 59 | 🐛 2 | 📅 2021-11-05

* **Figure Captioning with Relation Maps for Reasoning.**

  *Charles Chen, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, Ryan Rossi.* <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **Tackling Hallucinations in Neural Chart Summarization.**

*Saad Obaid ul Islam, Iza Škrjanec, Ondřej Dušek, Vera Demberg* <img src='https://img.shields.io/badge/INLG-2023-yellow'> <a href='https://aclanthology.org/2023.inlg-main.30/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='[https://github.com/JasonObeid/Chart2Text](https://github.com/WorldHellow/Hallucinations-C2T)'><img src='https://img.shields.io/badge/Model-green'></a>

#### Pre-trained

* **UniChart: A Universal Vision-language Pretrained Model for Chart Comprehension and Reasoning.**

  *Ahmed Masry, Parsa Kavehzadeh, Xuan Long Do, Enamul Hoque, Shafiq Joty.* <img src='https://img.shields.io/badge/EMNLP-2023-yellow'> <a href='https://aclanthology.org/2023.emnlp-main.906/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/vis-nlp/UniChart) ⭐ 89 | 🐛 5 | 🌐 Python | 📅 2024-08-18

* **Enhanced Chart Understanding via Visual Language Pre-training on Plot Table Pairs.**

  *Mingyang Zhou, Yi Fung, Long Chen, Christopher Thomas, Heng Ji, Shih-Fu Chang.* <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.85/'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/zmykevin/ACL2023_ChartT5) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2023-07-16

* **MatCha: Enhancing Visual Language Pretraining with Math Reasoning and Chart Derendering.**

  *Fangyu Liu, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Yasemin Altun, Nigel Collier, Julian Eisenschlos.* <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.714/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='google/matcha-base'><img src='https://img.shields.io/badge/Model-green'></a>

* **Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding.**

  *Kenton Lee, Mandar Joshi, Iulia Raluca Turc, Hexiang Hu, Fangyu Liu, Julian Martin Eisenschlos, Urvashi Khandelwal, Peter Shaw, Ming-Wei Chang, Kristina Toutanova.* <img src='https://img.shields.io/badge/ICML-2023-yellow'> <a href='https://proceedings.mlr.press/v202/lee23g/lee23g.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/google/pix2struct-base'><img src='https://img.shields.io/badge/Model-green'></a>

* **Synthesize Step-by-Step: Tools, Templates and LLMs as Data Generators for Reasoning-Based Chart VQA.**

  *Zhuowan Li, Bhavan Jasani, Peng Tang, Shabnam Ghadar.* <img src='https://img.shields.io/badge/CVPR-2024-yellow'> <a href='https://arxiv.org/abs/2403.16385'><img src='https://img.shields.io/badge/PDF-blue'></a>

### Tool Augmentation

* **DOMINO: A Dual-System for Multi-step Visual Language Reasoning.**

  *Peifeng Wang, Olga Golovneva, Armen Aghajanyan, Xiang Ren, Muhao Chen, Asli Celikyilmaz, Maryam Fazel-Zarandi.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2310.02804'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/facebookresearch/dual-system-for-visual-language-reasoning) ⚠️ Archived

* **DePlot: One-shot visual language reasoning by plot-to-table translation.**

  *Fangyu Liu, Julian Eisenschlos, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Wenhu Chen, Nigel Collier, Yasemin Altun.* <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.660/'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/google/deplot'><img src='https://img.shields.io/badge/Model-green'></a>

* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.**

  *Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji.* <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/khhuang/chart-to-table'><img src='https://img.shields.io/badge/Model-green'></a>

* **Do LLMs Work on Charts? Designing Few-Shot Prompts for Chart Question Answering and Summarization.**

  *Xuan Long Do, Mohammad Hassanpour, Ahmed Masry, Parsa Kavehzadeh, Enamul Hoque, Shafiq Joty.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.10610'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **StructChart: Perception, Structuring, Reasoning for Visual Chart Understanding.**

  *Renqiu Xia, Bo Zhang, Haoyang Peng, Hancheng Ye, Xiangchao Yan, Peng Ye, Botian Shi, Yu Qiao, Junchi Yan.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2309.11268'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **SIMPLOT: Enhancing Chart Question Answering by Distilling Essentials.**

  *Wonjoong Kim, Sangwu Park, Yeonjun In, Seokwon Han, Chanyoung Park.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2405.00021'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **OneChart: Purify the Chart Structural Extraction via One Auxiliary Token
  .**

  *Jinyue Chen, Lingyu Kong, Haoran Wei, Chenglong Liu, Zheng Ge, Liang Zhao, Jianjian Sun, Chunrui Han, Xiangyu Zhang.* <img src='https://img.shields.io/badge/ACM_MM-2024-yellow'> <a href='https://arxiv.org/abs/2404.09987'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/kppkkp/OneChart/tree/main'><img src='https://img.shields.io/badge/Model-green'></a> <a href='https://drive.google.com/drive/folders/1YmOvxq0DfOA9YKoyCZDjpnTIkPNoyegQ?usp=sharing'><img src='https://img.shields.io/badge/Dataset-red'></a>

### Large Vision-language Models

**Tailored for Chart Understanding**

* **TinyChart: Efficient Chart Understanding with Visual Token Merging and Program-of-Thoughts Learning.**

  *Liang Zhang, Anwen Hu, Haiyang Xu, Ming Yan, Yichen Xu, Qin Jin, Ji Zhang, Fei Huang.* <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://arxiv.org/abs/2404.16635'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/TinyChart) ⭐ 2,410 | 🐛 73 | 🌐 Python | 📅 2025-05-30

* **ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning.**

  *Renqiu Xia, Bo Zhang, Hancheng Ye, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Min Dou, Botian Shi, Junchi Yan, Yu Qiao.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2402.12185'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/UniModal4Reasoning/ChartVLM) ⭐ 260 | 🐛 10 | 🌐 Python | 📅 2024-09-26

* **ChartLlama: A Multimodal LLM for Chart Understanding and Generation.**

  *Yucheng Han, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.16483'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/tingxueronghua/ChartLlama-code) ⭐ 257 | 🐛 7 | 🌐 Python | 📅 2023-12-07

* **ChartAssistant: A Universal Chart Multimodal Language Model via Chart-to-Table Pre-training and Multitask Instruction Tuning.**

  *Fanqing Meng, Wenqi Shao, Quanfeng Lu, Peng Gao, Kaipeng Zhang, Yu Qiao, Ping Luo.* <img src='https://img.shields.io/badge/ACL Findings-2024-yellow'> <a href='https://arxiv.org/abs/2401.02384'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/OpenGVLab/ChartAst) ⭐ 136 | 🐛 9 | 🌐 Python | 📅 2024-09-07

* **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning.**

  *Fuxiao Liu, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, Dong Yu.* <img src='https://img.shields.io/badge/NAACL-2024-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/FuxiaoLiu/MMC) ⭐ 95 | 🐛 1 | 🌐 Python | 📅 2025-01-07

* **Multimodal Self-Instruct: Synthetic Abstract Image and Visual Reasoning Instruction Using Language Model**

  *Wenqi Zhang, Zhenglin Cheng, Yuanyu He, Mengna Wang, Yongliang Shen, Zeqi Tan, Guiyang Hou, Mingqian He, Yanna Ma, Weiming Lu, Yueting Zhuang.* <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://arxiv.org/abs/2407.07053'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/zwq2018/Multi-modal-Self-instruct) ⭐ 85 | 🐛 2 | 🌐 Python | 📅 2025-01-27

* **ChartGemma: Visual Instruction-tuning for Chart Reasoning in the Wild.**

  *Ahmed Masry, Megh Thakkar, Aayush Bajaj, Aaryaman Kartha, Enamul Hoque, Shafiq Joty.* <img src='https://img.shields.io/badge/COLING Industry-2025-yellow'> <a href='https://arxiv.org/abs/2407.04172v1'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/vis-nlp/ChartGemma) ⭐ 78 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2024-07-14

* **Distill Visual Chart Reasoning Ability from LLMs to MLLMs**

  *Wei He, Zhiheng Xi, Wanxu Zhao, Xiaoran Fan, Yiwen Ding, Zifei Shan, Tao Gui, Qi Zhang, Xuanjing Huang.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2410.18798'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/hewei2001/ReachQA) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2025-08-25

* **ChartInstruct: Instruction Tuning for Chart Comprehension and Reasoning.**

  *Ahmed Masry, Mehrad Shahmohammadi, Md Rizwan Parvez, Enamul Hoque, Shafiq Joty.* <img src='https://img.shields.io/badge/ACL Findings-2024-yellow'> <a href='https://arxiv.org/abs/2403.09028'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/vis-nlp/ChartInstruct) ⭐ 29 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2024-07-06

* **FigurA11y: AI Assistance for Writing Scientific Alt Text.**

  *Nikhil Singh, Andrew Head, Lucy Lu Wang, Jonathan Bragg.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://www.llwang.net/assets/pdf/2024_singh_figura11y_iui.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/allenai/figura11y) ⭐ 14 | 🐛 2 | 🌐 TypeScript | 📅 2024-02-07

* **START: Spatial and Textual Learning for Chart Understanding.**

  *Zhuoming Liu, Xiaofeng Gao, Feiyang Niu, Qiaozi Gao, Liu Liu, Robinson Piramuthu.* <img src='https://img.shields.io/badge/WACV-2026-yellow'> <a href='https://arxiv.org/abs/2512.07186'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Code-green'>](https://github.com/dragonlzm/START?tab=readme-ov-file) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-12-13

* **Chart-based Reasoning: Transferring Capabilities from LLMs to VLMs.**

  *Victor Carbune, Hassan Mansoor, Fangyu Liu, Rahul Aralikatte, Gilles Baechler, Jindong Chen, Abhanshu Sharma.* <img src='https://img.shields.io/badge/NAACL Findings-2024-yellow'> <a href='https://arxiv.org/abs/2403.12596'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **Why Vision Language Models Struggle with Visual Arithmetic? Towards Enhanced Chart and Geometry Understanding**

  *Kung-Hsiang Huang, Can Qin, Haoyi Qiu, Philippe Laban, Shafiq Joty, Caiming Xiong, Chien-Sheng Wu.* <img src='https://img.shields.io/badge/ACL_Findings-2025-yellow'> <a href='https://arxiv.org/abs/2502.11492'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Salesforce/CogAlign'><img src='https://img.shields.io/badge/Dataset-red'></a> <a href='https://huggingface.co/Salesforce/cogalign-internvl2_5-mpo-4b'><img src='https://img.shields.io/badge/Model-green'></a>

**General-purpose**

* **Visual Instruction Tuning.**

  *Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee.* <img src='https://img.shields.io/badge/NeurIPS-2023-yellow'> <a href='https://arxiv.org/abs/2304.08485'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/haotian-liu/LLaVA) ⭐ 25,002 | 🐛 1,139 | 🌐 Python | 📅 2024-08-12

* **SPHINX: The Joint Mixing of Weights, Tasks, and Visual Embeddings for Multi-modal Large Language Models.**

  *Ziyi Lin, Chris Liu, Renrui Zhang, Peng Gao, Longtian Qiu, Han Xiao, Han Qiu, Chen Lin, Wenqi Shao, Keqin Chen, Jiaming Han, Siyuan Huang, Yichi Zhang, Xuming He, Hongsheng Li, Yu Qiao.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.07575'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) ⭐ 2,801 | 🐛 57 | 🌐 Python | 📅 2025-01-13

* **mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality.**

  *Qinghao Ye, Haiyang Xu, Guohai Xu, Jiabo Ye, Ming Yan, Yiyang Zhou, Junyang Wang, Anwen Hu, Pengcheng Shi, Yaya Shi, Chenliang Li, Yuanhong Xu, Hehong Chen, Junfeng Tian, Qian Qi, Ji Zhang, Fei Huang.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2304.14178'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/X-PLUG/mPLUG-Owl) ⭐ 2,539 | 🐛 100 | 🌐 Python | 📅 2025-04-02

* **mPLUG-Owl2: Revolutionizing Multi-modal Large Language Model with Modality Collaboration.**

  *Qinghao Ye, Haiyang Xu, Jiabo Ye, Ming Yan, Anwen Hu, Haowei Liu, Qi Qian, Ji Zhang, Fei Huang, Jingren Zhou.* <img src='https://img.shields.io/badge/CVPR-2024-yellow'> <a href='https://arxiv.org/abs/2311.04257'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/X-PLUG/mPLUG-Owl) ⭐ 2,539 | 🐛 100 | 🌐 Python | 📅 2025-04-02

* **mPLUG-DocOwl 1.5: Unified Structure Learning for OCR-free Document Understanding**

  *Anwen Hu, Haiyang Xu, Jiabo Ye, Ming Yan, Liang Zhang, Bo Zhang, Chen Li, Ji Zhang, Qin Jin, Fei Huang, Jingren Zhou.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2403.12895'><img src='https://img.shields.io/badge/PDF-blue'></a>
  [<img src='https://img.shields.io/badge/Model-green'>](https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl1.5) ⭐ 2,410 | 🐛 73 | 🌐 Python | 📅 2025-05-30

* **Gemini: A Family of Highly Capable Multimodal Models.**

  *Gemini Team Google.* <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.11805'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://gemini.google.com/'><img src='https://img.shields.io/badge/Interface-darkgreen'></a>

* **GPT-4V.**

  *OpenAI.* <img src='https://img.shields.io/badge/Year-2023-yellow'> <a href='https://openai.com/research/gpt-4v-system-card'><img src='https://img.shields.io/badge/Website-blue'></a> <a href='https://chat.openai.com/'><img src='https://img.shields.io/badge/Interface-darkgreen'></a>

* **Introducing the next generation of Claude (Claude 3).**

  *Antropic.* <img src='https://img.shields.io/badge/Year-2023-yellow'> <a href='https://www.anthropic.com/news/claude-3-family'><img src='https://img.shields.io/badge/Website-blue'></a> <a href='https://claude.ai/'><img src='https://img.shields.io/badge/Interface-darkgreen'></a>

* **Why Vision Language Models Struggle with Visual Arithmetic? Towards Enhanced Chart and Geometry Understanding**

  *Kung-Hsiang Huang, Can Qin, Haoyi Qiu, Philippe Laban, Shafiq Joty, Caiming Xiong, Chien-Sheng Wu.* <img src='https://img.shields.io/badge/ACL_Findings-2025-yellow'> <a href='https://arxiv.org/abs/2502.11492'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/datasets/Salesforce/CogAlign'><img src='https://img.shields.io/badge/Dataset-red'></a> <a href='https://huggingface.co/Salesforce/cogalign-internvl2_5-mpo-4b'><img src='https://img.shields.io/badge/Model-green'></a>

## Evaluation

### Faithfulness/ Factuality

* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.**

  *Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji.* <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a> <a href='https://huggingface.co/khhuang/chartve'><img src='https://img.shields.io/badge/Model-green'></a>

## Analysis

* **Are Large Vision Language Models up to the Challenge of Chart Comprehension and Reasoning? An Extensive Investigation into the Capabilities and Limitations of LVLMs.**

  *Mohammed Saidul Islam, Raian Rahman, Ahmed Masry, Md Tahmid Rahman Laskar, Mir Tafseer Nayeem, Enamul Hoque.* <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2406.00257'><img src='https://img.shields.io/badge/PDF-blue'></a>

* **On the Perception Bottleneck of VLMs for Chart Understanding.**

  *Junteng Liu, Weihao Zeng, Xiwen Zhang, Yijun Wang, Zifei Shan, Junxian He.* <img src='https://img.shields.io/badge/Arxiv-2025-yellow'> <a href='https://arxiv.org/abs/2503.18435'><img src='https://img.shields.io/badge/PDF-blue'></a>

## Citation

```bibtex
@article{huang-etal-2024-chart,
    title = "From Pixels to Insights: A Survey on Automatic Chart Understanding in the Era of Large Foundation Models",
    author = "Huang, Kung-Hsiang and Chan, Hou Pong and Fung, Yi R. and Qiu, Haoyi and Zhou, Mingyang and Joty, Shafiq and Chang, Shih-Fu and Ji, Heng",
    year={2024},
    journal={IEEE Transactions on Knowledge and Data Engineering (TKDE)},
}
```

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
