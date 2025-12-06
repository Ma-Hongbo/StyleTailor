<p align="center">
    <!-- license badge -->
    <a href="https://github.com/nerfstudio-project/nerfstudio/blob/master/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"></a>
    <!-- stars badge -->
    <a href="https://github.com/Ma-Hongbo/Styletailor/stargazers">
        <img alt="GitHub stars" src="https://img.shields.io/github/stars/Ma-Hongbo/Styletailor?style=social"/>
    </a>
    <!-- pull requests badge -->
    <a href="https://github.com/Ma-Hongbo/Styletailor/pulls">
        <img alt="Pull Requests" src="https://img.shields.io/github/issues-pr/Ma-Hongbo/Styletailor"/>
    </a>

</p>

<div align="center">

StyleTailor
===========================
_<h4>Towards Personalized Fashion Styling via Hierarchical Negative Feedback</h4>_


<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 10px; justify-content: center;">
    <a href='https://arxiv.org/abs/2508.06555'><img src='https://img.shields.io/badge/cs.CV-Paper-b31b1b?logo=arxiv&logoColor=red'></a>
    <a href='https://ma-hongbo.github.io/StyleTailor.github.io/'><img src='https://img.shields.io/badge/Styletailor-Website-green?logo=googlechrome&logoColor=green'></a>
</div>

> ##### [Hongbo Ma](https://ma-hongbo.github.io/), [Fei Shen](https://muzishen.github.io/), [Hongbin Xu](), [Xiaoce Wang](https://zephinuecode.github.io/resume/), [Gang Xu](), [Jinkai Zheng](), [Liangqiong Qu](), [Ming Li](https://ming1993li.github.io/)

</div>

## Installation

``` bash
conda create -n styletailor python=3.10
cd /code
pip install -r requirements.txt
```

``` bash
conda create -n styletailor_eval python=3.10
pip install pyiqa
```

## Inference

``` bash
conda activate styletailor
python pipeline.py
```

```bash
conda activate styletailor_eval
cd /code/utils
python eval.py
```