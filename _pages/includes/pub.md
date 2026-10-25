<span class="anchor" id="publications"></span>

## 📝 Publications

For the most up-to-date publication list, please visit my [Google Scholar](https://scholar.google.com/citations?user=YAvLb6UAAAAJ&hl=en) profile. (* indicates equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/papers/sembridge.png' alt="SemBridge overview image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SemBridge: Semantic Token Anchoring for Continuous-Latent Autoregressive Speech Generation](https://arxiv.org/abs/2608.07462)

**Hanke Xie**, Haopeng Lin, Jiale Qian, Dake Guo, Yuepeng Jiang, Zhichao Wang, Wenxiao Cao, Jingbin Hu, Guobin Ma, Wenhao Li, Huakang Chen, Chengyou Wang, Ming Tao, Zhonghua Fu, Lei Xie, Xinsheng Wang

[**Paper**](https://arxiv.org/abs/2608.07462) [**Demo**](https://tiamojames.github.io/SemBridge_Demo/) [**Code**](https://github.com/ASLP-lab/SemBridge) [**Model**](https://huggingface.co/ASLP-lab/SemBridge) [![](https://img.shields.io/github/stars/ASLP-lab/SemBridge?style=social)](https://github.com/ASLP-lab/SemBridge)

- A training-only semantic-token anchoring framework that directly supervises the states of a continuous-latent AR language model with discrete semantic tokens, while inference remains entirely continuous.
- Consistently improves content accuracy (WER/CER) on both zero-shot TTS and score-conditioned singing voice synthesis.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech Report</div><img src='images/papers/soulx-podcast.png' alt="SoulX-Podcast model overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SoulX-Podcast: Towards Realistic Long-form Podcasts with Dialectal and Paralinguistic Diversity](https://arxiv.org/abs/2510.23541)

**Hanke Xie**<sup>*</sup>, Haopeng Lin<sup>*</sup>, Wenxiao Cao, Dake Guo, Wenjie Tian, Jun Wu, Hanlin Wen, Ruixuan Shang, Hongmei Liu, Zhiqi Jiang, Yuepeng Jiang, Wenxi Chen, Ruiqi Yan, Jiale Qian, Yichao Yan, Shunshun Yin, Ming Tao, Xie Chen, Lei Xie, Xinsheng Wang

[**Paper**](https://arxiv.org/abs/2510.23541) [**Demo**](https://soul-ailab.github.io/soulx-podcast/) [**Code**](https://github.com/Soul-AILab/SoulX-Podcast) [**Model**](https://huggingface.co/collections/Soul-AILab/soulx-podcast) [![](https://img.shields.io/github/stars/Soul-AILab/SoulX-Podcast?style=social)](https://github.com/Soul-AILab/SoulX-Podcast)

- A podcast-style multi-turn, multi-speaker dialogue speech generation system with paralinguistic controls, supporting Mandarin, English and Chinese dialects (Sichuanese, Henanese and Cantonese).
- Continuously generates over **90 minutes** of conversation with stable speaker timbre and smooth speaker transitions.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interspeech 2026</div><img src='images/papers/flashtts.jpg' alt="FlashTTS overview image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FlashTTS: Fast Streaming TTS with MTP Acceleration and X-pred Mean Flow Distillation](https://arxiv.org/abs/2606.09141)

**Hanke Xie**, Xiaming Ren, Dake Guo, Ruonan You, Wenhao Li, Jingbin Hu, Guobin Ma, Huakang Chen, Kejie Xu, Rui Huang, Weiguo Tan, Xianrong Wang, Lei Xie

[**Paper**](https://arxiv.org/abs/2606.09141) [**Demo**](https://aslp-lab.github.io/flashtts_demo/) [**Code**](https://github.com/ASLP-lab/FlashTTS) [![](https://img.shields.io/github/stars/ASLP-lab/FlashTTS?style=social)](https://github.com/ASLP-lab/FlashTTS)

- An open-source low-latency streaming TTS framework with a lagged multi-track architecture for native streaming text/speech input, parallel Multi-Token Prediction (MTP), and a 2-NFE X-pred mean-flow decoder.
- Reduces first-packet latency to **325 ms** while preserving strong zero-shot voice cloning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCSLP 2026</div><img src='images/papers/xpred-meanflow.png' alt="X-Pred MeanFlow overview image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[X-Pred MeanFlow for Streaming Token-to-Mel Speech Decoding](https://arxiv.org/abs/2609.12728)

**Hanke Xie**, Xiaming Ren, Qirui Zhan, Jingbin Hu, Wenhao Li, Haoyu Zhang, Ruonan You, Chengyou Wang, Yunxiang Chen, Houdun Liu, Su Feng, Lei Xie

[**Paper**](https://arxiv.org/abs/2609.12728) [**Demo**](https://renxiaming.github.io/xpred-meanflow-stream-demo/)

- A few-step streaming token-to-mel decoder that reparameterizes MeanFlow with mel-space prediction, together with layer-selective block-wise attention for chunk-wise streaming generation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">APSIPA ASC 2025</div><img src='images/papers/dialospeech.png' alt="DialoSpeech overview image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DialoSpeech: Dual-Speaker Dialogue Generation with LLM and Flow Matching](https://arxiv.org/abs/2510.08373)

**Hanke Xie**, Dake Guo, Chengyou Wang, Yue Li, Wenjie Tian, Xinfa Zhu, Xinsheng Wang, Xiulin Li, Guanqiong Miao, Bo Liu, Lei Xie

[**Paper**](https://arxiv.org/abs/2510.08373) [**Demo**](https://tiamojames.github.io/DialoSpeech/)

- A dual-track architecture combining an LLM with chunked flow matching for human-like dual-speaker dialogue generation with coherent turn-taking and natural overlaps, plus a pipeline for building dual-track dialogue data.

</div>
</div>

- ``ACM MM 2026`` [MINT-Bench: A Comprehensive Multilingual Benchmark for Instruction-Following Text-to-Speech](https://arxiv.org/abs/2604.17958), Huakang Chen, Jingbin Hu, Liumeng Xue, Qirui Zhan, Wenhao Li, Guobin Ma, **Hanke Xie**, Dake Guo, Linhan Ma, Yuepeng Jiang, Bengu Wu, Pengyuan Xie, Chuan Xie, Qiang Zhang, Lei Xie.
- ``Tech Report`` [SoulX-Singer: Towards High-Quality Zero-Shot Singing Voice Synthesis](https://arxiv.org/abs/2602.07803), Jiale Qian, Hao Meng, Tian Zheng, Pengcheng Zhu, Haopeng Lin, Yuhang Dai, **Hanke Xie**, Wenxiao Cao, Ruixuan Shang, Jun Wu, Hongmei Liu, Hanlin Wen, Jian Zhao, Zhonglin Jiang, Yong Chen, Shunshun Yin, Ming Tao, Jianguo Wei, Lei Xie, Xinsheng Wang.
- ``Tech Report`` [OSUM-EChat: Enhancing End-to-End Empathetic Spoken Chatbot via Understanding-Driven Spoken Dialogue](https://arxiv.org/abs/2508.09600), Xuelong Geng, Qijie Shao, Hongfei Xue, Shuiyuan Wang, **Hanke Xie**, Zhao Guo, Yi Zhao, Guojian Li, Wenjie Tian, Chengyou Wang, Zhixian Zhao, Kangxiang Xia, Ziyu Zhang, Zhennan Lin, Tianlun Zuo, Mingchen Shao, Yuang Cao, Guobin Ma, Longhao Li, Yuhang Dai, Dehui Gao, Dake Guo, Lei Xie.
