# Qwen3-VL


<p align="center">
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/qwen3vllogo.png" width="400"/>
<p>

<p align="center">
        💜 <a href="https://chat.qwenlm.ai/"><b>Qwen Chat</b></a>&nbsp&nbsp | &nbsp&nbsp🤗 <a href="https://huggingface.co/collections/Qwen/qwen3-vl-68d2a7c1b8a8afce4ebd2dbe">Hugging Face</a>&nbsp&nbsp | &nbsp&nbsp🤖 <a href="https://modelscope.cn/collections/Qwen3-VL-5c7a94c8cb144b">ModelScope</a>&nbsp&nbsp | &nbsp&nbsp📑 <a href="https://qwen.ai/blog?id=99f0335c4ad9ff6153e517418d48535ab6d8afef&from=research.latest-advancements-list">Blog</a>&nbsp&nbsp | &nbsp&nbsp📚 <a href="https://github.com/QwenLM/Qwen3-VL/tree/main/cookbooks">Cookbooks</a>&nbsp&nbsp | &nbsp&nbsp📑 <a href="https://arxiv.org/pdf/2511.21631">Paper</a>&nbsp&nbsp
<br>
🖥️ <a href="https://huggingface.co/spaces/Qwen/Qwen3-VL-Demo">Demo</a>&nbsp&nbsp | &nbsp&nbsp💬 <a href="https://github.com/QwenLM/Qwen/blob/main/assets/wechat.png">WeChat (微信)</a>&nbsp&nbsp | &nbsp&nbsp🫨 <a href="https://discord.gg/CV4E9rpNSD">Discord</a>&nbsp&nbsp | &nbsp&nbsp📑 <a href="https://help.aliyun.com/zh/model-studio/developer-reference/qwen-vl-api">API</a>&nbsp&nbsp | &nbsp&nbsp🖥️ <a href="https://gallery.pai-ml.com/#/preview/deepLearning/cv/qwen2.5-vl">PAI-DSW</a>
</p>



## Introduction
Meet Qwen3-VL — the most powerful vision-language model in the Qwen series to date.

This generation delivers comprehensive upgrades across the board: superior text understanding & generation, deeper visual perception & reasoning, extended context length, enhanced spatial and video dynamics comprehension, and stronger agent interaction capabilities.

Available in Dense and MoE architectures that scale from edge to cloud, with Instruct and reasoning‑enhanced Thinking editions for flexible, on‑demand deployment.


#### Key Enhancements:

* **Visual Agent**: Operates PC/mobile GUIs—recognizes elements, understands functions, invokes tools, completes tasks.

* **Visual Coding Boost**: Generates Draw.io/HTML/CSS/JS from images/videos.

* **Advanced Spatial Perception**: Judges object positions, viewpoints, and occlusions; provides stronger 2D grounding and enables 3D grounding for spatial reasoning and embodied AI.

* **Long Context & Video Understanding**: Native 256K context, expandable to 1M; handles books and hours-long video with full recall and second-level indexing.

* **Enhanced Multimodal Reasoning**: Excels in STEM/Math—causal analysis, logical, evidence-based answers.

* **Upgraded Visual Recognition**: Broader, higher-quality pretraining is able to “recognize everything”—celebrities, anime, products, landmarks, flora/fauna, etc.

* **Expanded OCR**: Supports 32 languages (up from 10); robust in low light, blur, and tilt; better with rare/ancient characters and jargon; improved long-document structure parsing.

* **Text Understanding on par with pure LLMs**: Seamless text–vision fusion for lossless, unified comprehension.


#### Model Architecture Updates:

<p align="center">
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/qwen3vl_arc.jpg" width="80%"/>
<p>


1. **Interleaved-MRoPE**: Full‑frequency allocation over time, width, and height via robust positional embeddings, enhancing long‑horizon video reasoning.

2. **DeepStack**: Fuses multi‑level ViT features to capture fine‑grained details and sharpen image–text alignment.

3. **Text–Timestamp Alignment:** Moves beyond T‑RoPE to precise, timestamp‑grounded event localization for stronger video temporal modeling.






## News
* 2025.11.27: We have released the [**Qwen3-VL paper**](https://arxiv.org/pdf/2511.21631), which introduces many technical details about Qwen3-VL, and we hope it will be helpful to everyone.
* 2025.10.21: We have released the **Qwen3-VL-2B** ([Instruct](https://huggingface.co/Qwen/Qwen3-VL-2B-Instruct)/[Thinking](https://huggingface.co/Qwen/Qwen3-VL-2B-Thinking)) and **Qwen3-VL-32B** ([Instruct](https://huggingface.co/Qwen/Qwen3-VL-32B-Instruct)/[Thinking](https://huggingface.co/Qwen/Qwen3-VL-32B-Thinking)). Enjoy it!
* 2025.10.15: We have released the **Qwen3-VL-4B** ([Instruct](https://huggingface.co/Qwen/Qwen3-VL-4B-Instruct)/[Thinking](https://huggingface.co/Qwen/Qwen3-VL-4B-Thinking)) and **Qwen3-VL-8B** ([Instruct](https://huggingface.co/Qwen/Qwen3-VL-8B-Instruct)/[Thinking](https://huggingface.co/Qwen/Qwen3-VL-8B-Thinking)). Enjoy it!
* 2025.10.4: We have released the [Qwen3-VL-30B-A3B-Instruct](https://huggingface.co/Qwen/Qwen3-VL-30B-A3B-Instruct) and [Qwen3-VL-30B-A3B-Thinking](https://huggingface.co/Qwen/Qwen3-VL-30B-A3B-Thinking). We have also released the FP8 version of the Qwen3-VL models — available in our [HuggingFace collection](https://huggingface.co/collections/Qwen/qwen3-vl-68d2a7c1b8a8afce4ebd2dbe) and [ModelScope collection](https://modelscope.cn/collections/Qwen3-VL-5c7a94c8cb144b).
* 2025.09.23: We have released the [Qwen3-VL-235B-A22B-Instruct](https://huggingface.co/Qwen/Qwen3-VL-235B-A22B-Instruct) and [Qwen3-VL-235B-A22B-Thinking](https://huggingface.co/Qwen/Qwen3-VL-235B-A22B-Thinking). For more details, please check our [blog](https://qwen.ai/blog?id=99f0335c4ad9ff6153e517418d48535ab6d8afef&from=research.latest-advancements-list)!
* 2025.04.08: We provide the [code](https://github.com/QwenLM/Qwen2.5-VL/tree/main/qwen-vl-finetune) for fine-tuning Qwen2-VL and Qwen2.5-VL.
* 2025.03.25: We have released the [Qwen2.5-VL-32B](https://huggingface.co/Qwen/Qwen2.5-VL-32B-Instruct). It is smarter and its responses align more closely with human preferences. For more details, please check our [blog](https://qwenlm.github.io/blog/qwen2.5-vl-32b/)!
* 2025.02.20: we have released the [Qwen2.5-VL Technical Report](https://arxiv.org/abs/2502.13923). Alongside the report, we have also released AWQ-quantized models for Qwen2.5-VL in three different sizes: [3B](https://huggingface.co/Qwen/Qwen2.5-VL-3B-Instruct-AWQ), [7B](https://huggingface.co/Qwen/Qwen2.5-VL-7B-Instruct-AWQ) , and [72B](https://huggingface.co/Qwen/Qwen2.5-VL-72B-Instruct-AWQ) parameters.
* 2025.01.28: We have released the [Qwen2.5-VL series](https://huggingface.co/Qwen). For more details, please check our [blog](https://qwenlm.github.io/blog/qwen2.5-vl/)!
* 2024.12.25: We have released the [QvQ-72B-Preview](https://huggingface.co/Qwen/QVQ-72B-Preview). QvQ-72B-Preview is an experimental research model, focusing on enhancing visual reasoning capabilities. For more details, please check our [blog](https://qwenlm.github.io/blog/qvq-72b-preview/)!
* 2024.09.19: The instruction-tuned [Qwen2-VL-72B model](https://huggingface.co/Qwen/Qwen2-VL-72B-Instruct) and its quantized version [[AWQ](https://huggingface.co/Qwen/Qwen2-VL-72B-Instruct-AWQ), [GPTQ-Int4](https://huggingface.co/Qwen/Qwen2-VL-72B-Instruct-GPTQ-Int4), [GPTQ-Int8](https://huggingface.co/Qwen/Qwen2-VL-72B-Instruct-GPTQ-Int8)] are now available. We have also released the [Qwen2-VL paper](https://arxiv.org/pdf/2409.12191) simultaneously.
* 2024.08.30: We have released the [Qwen2-VL series](https://huggingface.co/collections/Qwen/qwen2-vl-66cee7455501d7126940800d). The 2B and 7B models are now available, and the 72B model for open source is coming soon. For more details, please check our [blog](https://qwenlm.github.io/blog/qwen2-vl/)!


## Performance

### Visual Tasks

<div style="display: flex; justify-content: center; gap: 16px; flex-wrap: wrap;">
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/table_nothinking_vl.jpg" width="24%" />
    <img src="https://qianwen-res.oss-cn-beijing.aliyuncs.com/Qwen3-VL/table_thinking_vl_.jpg" width="24%" />
	<img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/table_nothinking_vl-30a3.jpg" width="26%" />
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/table_thinking_vl_30A3.jpg" width="22.5%" />
</div>

<div style="display: flex; justify-content: center; gap: 16px; flex-wrap: wrap;">
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/qwen3vl_2b_32b_vl_instruct.jpg" width="30%" />
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/qwen3vl_2b_32b_vl_thinking.jpg" width="24%" />
</div>


### Text-Centric Tasks

<div style="display: flex; justify-content: center; gap: 16px; flex-wrap: wrap;">
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/table_nothinking_text.jpg" width="30%" />
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/table_thinking_text.jpg" width="32%" />
	<img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/table_nothinking_text-30a3.jpg" width="30%" />
</div>



<div style="display: flex; justify-content: center; gap: 16px; flex-wrap: wrap;">
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/qwen3vl_4b_8b_text_instruct.jpg" width="33%" />
    <img src="https://qianwen-res.oss-accelerate.aliyuncs.com/Qwen3-VL/qwen3vl_4b_8b_text_thinking.jpg" width="28%" />
</div>


## Cookbooks

We are preparing [cookbooks](https://github.com/QwenLM/Qwen3-VL/tree/main/cookbooks) for many capabilities, including recognition, localization, document parsing, video understanding, key information extraction, and more. Welcome to learn more!

| Cookbook | Description | Open |
| -------- | ----------- | ---- |
| [Omni Recognition](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/omni_recognition.ipynb) | Not only identify animals, plants, people, and scenic spots but also recognize various objects such as cars and merchandise. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/omni_recognition.ipynb) |
| [Powerful Document Parsing Capabilities](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/document_parsing.ipynb) | The parsing of documents has reached a higher level, including not only text but also layout position information and our Qwen HTML format. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/document_parsing.ipynb) |
| [Precise Object Grounding Across Formats](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/2d_grounding.ipynb) | Using relative position coordinates, it supports both boxes and points, allowing for diverse combinations of positioning and labeling tasks. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/2d_grounding.ipynb) |
| [General OCR and Key Information Extraction](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/ocr.ipynb) | Stronger text recognition capabilities in natural scenes and multiple languages, supporting diverse key information extraction needs. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/ocr.ipynb) |
| [Video Understanding](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/video_understanding.ipynb) | Better video OCR, long video understanding, and video grounding. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/video_understanding.ipynb) |
| [Mobile Agent](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/mobile_agent.ipynb) | Locate and think for mobile phone control. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/mobile_agent.ipynb) |
| [Computer-Use Agent](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/computer_use.ipynb) | Locate and think for controlling computers and Web. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/computer_use.ipynb) |
| [3D Grounding](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/3d_grounding.ipynb) | Provide accurate 3D bounding boxes for both indoor and outdoor objects. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/3d_grounding.ipynb) |
| [Thinking with Images](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/think_with_images.ipynb) | Utilize image_zoom_in_tool and search_tool to facilitate the model’s precise comprehension of fine-grained visual details within images. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/think_with_images.ipynb) |
| [MultiModal Coding](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/mmcode.ipynb) | Generate accurate code based on rigorous comprehension of multimodal information. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/mmcode.ipynb) |
| [Long Document Understanding](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/long_document_understanding.ipynb) | Achieve rigorous semantic comprehension of ultra-long documents. | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/long_document_understanding.ipynb) |
| [Spatial Understanding](https://github.com/QwenLM/Qwen3-VL/blob/main/cookbooks/spatial_understanding.ipynb) | See, understand and reason about the spatial information | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/QwenLM/Qwen3-VL/blob/main/cookbooks/spatial_understanding.ipynb) |


## Citation

If you find our paper and code useful in your research, please consider giving a star :star: and citation :pencil: :)




```BibTeX

@article{Qwen3-VL,
      title={Qwen3-VL Technical Report}, 
      author={Shuai Bai and Yuxuan Cai and Ruizhe Chen and Keqin Chen and Xionghui Chen and Zesen Cheng and Lianghao Deng and Wei Ding and Chang Gao and Chunjiang Ge and Wenbin Ge and Zhifang Guo and Qidong Huang and Jie Huang and Fei Huang and Binyuan Hui and Shutong Jiang and Zhaohai Li and Mingsheng Li and Mei Li and Kaixin Li and Zicheng Lin and Junyang Lin and Xuejing Liu and Jiawei Liu and Chenglong Liu and Yang Liu and Dayiheng Liu and Shixuan Liu and Dunjie Lu and Ruilin Luo and Chenxu Lv and Rui Men and Lingchen Meng and Xuancheng Ren and Xingzhang Ren and Sibo Song and Yuchong Sun and Jun Tang and Jianhong Tu and Jianqiang Wan and Peng Wang and Pengfei Wang and Qiuyue Wang and Yuxuan Wang and Tianbao Xie and Yiheng Xu and Haiyang Xu and Jin Xu and Zhibo Yang and Mingkun Yang and Jianxin Yang and An Yang and Bowen Yu and Fei Zhang and Hang Zhang and Xi Zhang and Bo Zheng and Humen Zhong and Jingren Zhou and Fan Zhou and Jing Zhou and Yuanzhi Zhu and Ke Zhu},
	  journal={arXiv preprint arXiv:2511.21631},
      year={2025}
}
```

<br>

1. related project [DeepSeek-VL2](https://github.com/deepseek-ai/DeepSeek-VL2)
2. related project [Aria](https://github.com/rhymes-ai/Aria)
3. related project [Kimi-VL](https://github.com/moonshotai/Kimi-VL)
