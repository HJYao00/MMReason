<div align="center">

<h1> MMReason: An Open-Ended Multi-Modal Multi-Step Reasoning Benchmark for MLLMs Toward AGI </h1>

<!--
<h5 align="center"> If you find this project useful, please give us a star🌟.

<h5 align="center"> 
-->

<a href='https://arxiv.org/abs/2506.23563'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a>
<!--
<a href='https://huggingface.co/HuanjinYao/Mulberry_llava_8b'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-blue'>
<a href='https://huggingface.co/datasets/HuanjinYao/Mulberry-SFT'><img src='https://img.shields.io/badge/Dataset-Huggingface-yellow'>
-->
<!--<a href='https://huggingface.co/collections/HuanjinYao/denseconnector-66500e173fc8c9f05dc98dea'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-blue'></a>
[![zhihu](https://img.shields.io/badge/-知乎-000000?logo=zhihu&logoColor=0084FF)](https://zhuanlan.zhihu.com/p/700000183)
<a href='https://huggingface.co/spaces/HuanjinYao/DenseConnector-v1.5-8B'><img src='https://img.shields.io/badge/🤗-Open%20In%20Spaces-blue.svg'></a>-->

<!--
[Huanjin Yao](https://scholar.google.com/citations?user=pDtsCBQAAAAJ&hl=zh-CN)<sup>2,3*</sup>,
[Qixiang Yin](https://jxhuang0508.github.io/)<sup>4*</sup>,
[Jingyi Zhang]()<sup>1</sup>,
[Min Yang]()<sup>2</sup>,
[Yibo Wang]()<sup>3</sup>,
[Wenhao Wu]()<sup>5</sup>,

[Fei Su]()<sup>4</sup>,
[Li Shen]()<sup>1</sup>,
[Minghui Qiu]()<sup>2</sup>,
[Dacheng Tao]()<sup>1</sup>
[Jiaxing Huang](https://jxhuang0508.github.io)<sup>1✉️</sup>


<sup>1</sup>[Nanyang Technological University](https://www.ntu.edu.sg/), <sup>2</sup>[ByteDance](), <sup>3</sup>[Tsinghua University](https://www.tsinghua.edu.cn/en/), <sup>4</sup>[BUPT](), <sup>5</sup>[USYD](https://www.sysu.edu.cn/sysuen/)

<sup>*</sup>Equal Contribution,       <sup>✉️</sup>Corresponding Author

-->

</h5>
</div>


## News
- [x] **`July 1, 2025.`** We release our paper in [arxiv](https://arxiv.org/abs/2506.23563).


## Evaluation

MMReason has been integrated into [VLMEvalKit](https://github.com/open-compass/VLMEvalKit), a unified evaluation toolkit for vision-language models.

To evaluate a model on the `MMReason_testmini` split, run:

```bash
git clone https://github.com/open-compass/VLMEvalKit.git
cd VLMEvalKit
python3 run.py --data MMReason_testmini --model Qwen3-VL-4B-Instruct --verbose
```


## Citation
If you find this repository is useful, please star🌟 this repo and cite🖇️ our paper.
```bibtex
@article{yao2025mmreason,
  title={MMReason: An Open-Ended Multi-Modal Multi-Step Reasoning Benchmark for MLLMs Toward AGI},
  author={Yao, Huanjin and Huang, Jiaxing and Qiu, Yawen and Chen, Michael K and Liu, Wenzheng and Zhang, Wei and Zeng, Wenjie and Zhang, Xikun and Zhang, Jingyi and Song, Yuxin and others},
  journal={arXiv preprint arXiv:2506.23563},
  year={2025}
}
