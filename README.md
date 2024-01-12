# Audio &amp; Speech Generation Paper List
A curated list of papers and resources related to Speech &amp; Audio Generation. This project is just starting and still requires a lot of work. So feel free to contribute!

## Paper

### Text to Speech (TTS)

* **VALL-E**: [Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2301.02111) (2023-01, Microsoft) [[Unofficial code](https://github.com/enhuiz/vall-e)] 
* **Your TTS**: [YourTTS: Towards Zero-Shot Multi-Speaker TTS and Zero-Shot Voice Conversion for Everyone](https://proceedings.mlr.press/v162/casanova22a.html) (ICML 2022) [[Code](https://github.com/coqui-ai/tts)]

### Voice Conversion (VC)

* **Your TTS**: [YourTTS: Towards Zero-Shot Multi-Speaker TTS and Zero-Shot Voice Conversion for Everyone](https://proceedings.mlr.press/v162/casanova22a.html) (ICML 2022) [[Code](https://github.com/coqui-ai/tts)]

### Audio Generation and Text to Audio (TTA)

Notes that actually many audio generation models are also able to generate speech.


### Singing Voice Synthesis (SVS)

### Speech to Speech Translation (S2ST/ STST)

* **Seamless**: [Seamless: Multilingual Expressive and Streaming Speech Translation](http://arxiv.org/abs/2312.05187) (2023-12, Meta) [[Official Code & Model](https://github.com/facebookresearch/seamless_communication)]
* **Translatotron 3**: [Translatotron 3: Speech to Speech Translation with Monolingual Data](https://arxiv.org/abs/2305.17547) (2023-05, Google) [[Demo](https://google-research.github.io/lingvo-lab/translatotron3/)]
* **VALL-E X**: [Speak Foreign Languages with Your Own Voice: Cross-Lingual Neural Codec Language Modeling](https://arxiv.org/abs/2303.03926) (2023-03, Microsoft) [[Demo](https://www.microsoft.com/en-us/research/project/vall-e-x/vall-e-x/), [Unofficial Code](https://github.com/Plachtaa/VALL-E-X)]

#### Streaming & Simultaneous Translation

* **STACL**: [STACL: Simultaneous Translation with Implicit Anticipation and Controllable Latency using Prefix-to-Prefix Framework](https://aclanthology.org/P19-1289/) (ACL 2019) [[Demo](https://simultrans-demo.github.io/)]

### Text to Music(TTM)

### Large Language Model(LLM)

* **AudioPaLM**: [AudioPaLM: A Large Language Model That Can Speak and Listen](https://arxiv.org/abs/2306.12925) (2023-06, Google) [[Demo](https://google-research.github.io/seanet/audiopalm/examples/)] A large language model which fuses text-based and speech-based language models, PaLM-2 and AudioLM, into a unified multimodal architecture that can process and generate text and speech with applications including speech recognition and speech-to-speech translation.
* **AudioLM**: [AudioLM: a language modeling approach to audio generation](https://ieeexplore.ieee.org/document/10158503) (TASLP 2023, Google) [[Code](https://github.com/lucidrains/audiolm-pytorch), [Blog](https://blog.research.google/2022/10/audiolm-language-modeling-approach-to.html), [Demo](https://google-research.github.io/seanet/audiolm/examples/)] AudioLM learns to generate natural and coherent continuations given short prompts. 


## Software/ Libraries

### Speech Synthesis

* [BERT-VITS2](https://github.com/fishaudio/Bert-VITS2): A TTS tool shows great performance on Chinese speech synthesis.
* [Amphion](https://github.com/open-mmlab/Amphion): An Open-Source Audio, Music, and Speech Generation Toolkit. The Goal of Amphion is to offer a platform for studying the conversion of any inputs into audio. (TTS, SVS, VC, SVC, TTA, TTM) [[Paper](https://arxiv.org/abs/2312.09911)]

