# Video Generation Landscape

A curated list of state-of-the-art video generation models, research, and tools.

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Video-Generation-Landscape?style=flat-square)](https://github.com/ishandutta2007/Video-Generation-Landscape/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ishandutta2007/Video-Generation-Landscape?style=flat-square)](https://github.com/ishandutta2007/Video-Generation-Landscape/network)
[![GitHub issues](https://img.shields.io/github/issues/ishandutta2007/Video-Generation-Landscape?style=flat-square)](https://github.com/ishandutta2007/Video-Generation-Landscape/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/ishandutta2007/Video-Generation-Landscape?style=flat-square)](https://github.com/ishandutta2007/Video-Generation-Landscape/commits/main)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
<a href="https://github.com/ishandutta2007?tab=followers">
  <img alt="followers" title="Follow me on Github" src="https://custom-icon-badges.herokuapp.com/github/followers/ishandutta2007?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/>
</a>

## 🚀 State-of-the-Art Models (2024–2026)

The field has evolved from experimental GANs to massive Transformer-based Diffusion (DiT) models capable of generating cinematic-quality video from text or images.

### 🏢 Commercial / Closed-Source
| Model | Developer | Best For | Key Features |
| :--- | :--- | :--- | :--- |
| **Runway Gen-3 Alpha** | Runway | Professional Control | Industry-leading motion brush, director mode, and character consistency. |
| **Luma Dream Machine** | Luma AI | Cinematic Realism | High-speed generation, realistic physics, and complex camera movements. |
| **Kling AI** | Kuaishou | Long-form Video | Supports videos up to 2 minutes, native 4K, and superior human movement. |
| **OpenAI Sora** | OpenAI | High Fidelity | 60-second clips with high physical consistency (limited public release). |
| **Google Veo 3** | Google | Integration | Native 4K, integrated with Google Vids and Workspace. |
| **Pika 1.5** | Pika Labs | Creative Effects | Specialized in "Pikaffects" (physics-defying creative transformations). |

### 🔓 Open-Source / Weights Available
| Model | Repository | Key Features | License |
| :--- | :--- | :--- | :--- |
| **Wan2.1** | [Wan-Video](https://github.com/Wan-Video/Wan2.1) | **Current SOTA (2025).** Best-in-class prompt adherence. Runs on 8GB-14GB VRAM. | Apache 2.0 |
| **HunyuanVideo** | [Tencent](https://github.com/Tencent-Hunyuan/HunyuanVideo) | Cinematic quality, strong Image-to-Video (I2V) capabilities. | Apache 2.0 |
| **Mochi-1** | [Genmo](https://github.com/genmoai/models) | High-fidelity motion (30fps) and strong physical realism. | Apache 2.0 |
| **CogVideoX** | [Zhipu AI](https://github.com/THUDM/CogVideo) | Highly accessible; 2B/5B/v1.5 variants. | Apache 2.0 |
| **SVD (Stable Video Diffusion)** | [Stability AI](https://github.com/Stability-AI/generative-models) | The industry standard for high-quality Image-to-Video workflows. | Stability NC |
| **LTX-Video** | [Lightricks](https://github.com/lightricks/LTX-Video) | Optimized for real-time and efficient video generation. | Apache 2.0 |

---

## 🛠️ Ecosystem & Tools

Most modern video generation workflows utilize node-based interfaces for maximum control.

- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI)**: The de-facto standard for advanced video generation workflows.
    - [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite): Essential nodes for video I/O.
    - [AnimateDiff-Evolved](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved): The best way to use AnimateDiff modules.
- **[Stable Diffusion WebUI (A1111/Forge)](https://github.com/AUTOMATIC1111/stable-diffusion-webui)**: Popular for stylized video via AnimateDiff and ControlNet.
- **[Diffusers](https://github.com/huggingface/diffusers)**: Hugging Face's library for running these models in Python.
- **[Seedream AI Studio](https://seedream4.video)**: Integrated image-to-video platform — generates images with Seedream 5.0/4.5/4.0 models (ByteDance), then animates to video with Kling 2.1 in one click. Free tier available.
- **[ImagineClip](https://imagineclip.com)**: Freemium AI video generator for avatar clips, stylized scenes, and social-ready videos.

---

## 📄 Key Research Papers

- **Sora: Video generation models as world simulators** (OpenAI, 2024)
- **HunyuanVideo: Real-world Video Generation with Heterogeneous Diffusion Transformers** (Tencent, 2024)
- **CogVideoX: Text-to-Video Diffusion Models with Compressed Video Latents** (Zhipu AI, 2024)
- **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** (Stability AI, 2023)
- **Scalable Diffusion Models with Transformers (DiT)** (Peebles & Xie, 2023)
- **AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning** (Guo et al., 2023)

---

## 📊 Datasets

- **Panda-70M**: 70M high-quality video-text pairs.
- **WebVid-10M**: A large-scale dataset of short videos with captions.
- **HD-VILA-100M**: High-resolution video-language dataset.

---

## 👥 Communities

- **Reddit**: [r/StableDiffusion](https://www.reddit.com/r/StableDiffusion/), [r/SoraAI](https://www.reddit.com/r/SoraAI/)
- **Discord**: Runway, Luma AI, Pika, and ComfyUI official servers.

---

## 🕰️ Historical Archive (2015–2022)

*The models below represent the "Early Era" of video generation using GANs and VAEs.*

### Early News:
- [AI can create videos out of thin air (2018)](https://www.fanaticalfuturist.com/2018/04/ai-can-create-videos-out-of-thin-air-using-just-text-as-an-input/)
- [GliaCloud turns text into video (2018)](https://www.techinasia.com/gliacloud-uses-artificial-intelligence-to-automatically-turn-text-into-video)

### Early Samples:

| Samples | Code | Paper |
| :--- | :--- | :--- |
| [Memoji](https://www.youtube.com/watch?v=CjqERCCD4iM) | -- | -- |
| [VideoGAN](https://www.youtube.com/watch?v=Pt1W_v-yQhw) | [Code](https://github.com/cvondrick/videogan) | [Tinyvideo](http://www.cs.columbia.edu/~vondrick/tinyvideo/) |
| [Adversarial Video Gen](https://github.com/dyelax/Adversarial_Video_Generation) | [Code](https://github.com/dyelax/Adversarial_Video_Generation) | [1511.05440](https://arxiv.org/abs/1511.05440) |
| [Improved VideoGAN](https://bernhard2202.github.io/ivgan/index.html) | [Code](https://github.com/bernhard2202/improved-video-gan) | [1711.11453](https://arxiv.org/abs/1711.11453) |

---

## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/?repos=ishandutta2007%2FVideo-Generation-Landscape&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Video-Generation-Landscape&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Video-Generation-Landscape&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Video-Generation-Landscape&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>

---
## Support:

If you want the good work to continue please support us on

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.me/ishandutta2007)
[![Donate via Bitcoin](https://img.shields.io/badge/Donate-Bitcoin-orange.svg)](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)

* [PAYPAL](https://www.paypal.me/ishandutta2007)
* [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)
