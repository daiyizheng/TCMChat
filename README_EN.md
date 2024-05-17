[**中文**](./README.md) | [**English**](./README_EN.md)

<p align="center" width="100%">
<a href="https://github.com/daiyizheng/TCMChat" target="_blank"><img src="assets/herb.png" alt="TCMChat" style="width: 25%; min-width: 300px; display: block; margin: auto;"></a>
</p>

# TCMChat: Traditional Chinese Medicine Recommendation System based on Large Language Model

[![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg)](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese/blob/main/LICENSE) [![Python 3.10.](https://img.shields.io/badge/python-3.-blue.svg)](https://www.python.org/downloads/release/python-390/)

## News

[2024-5-17]  Open source model weight on huggingface

## Usage

### Install

```
git clone https://github.com/daiyizheng/TCMChat
cd TCMChat

```

First install the dependency package. python environment 3.10+ is recommended

```
pip install -r requirements.txt
```

### inference on cli

```
python cli_infer.py \
--model_name_or_path /your/model/path \
--model_type  chat

```

### inference on web demo

```
python gradio_demo.py
```


### download weight

[TCMChat](https://huggingface.co/daiyizheng/TCMChat): QA and recommendation of Chinese medicine prescription knowledge based on baichuan2-7B-Chat






## Citing

```
@misc{tcmchat,
    doi = {xxx},
    url = {xxx},
    author = {Yizheng Dai},
    keywords = {xxx},
    title = {TCMChat: Traditional Chinese Medicine Recommendation System based on Large Language Model},
    publisher = {arXiv},
    year = {2024},
    copyright = {l}
}
```
