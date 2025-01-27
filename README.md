[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/qunash/r1-overthinker/blob/master/r1_overthinker.ipynb)
# **DeepSeek R1 Overthinker**
Using this app you can force [DeepSeek R1](https://api-docs.deepseek.com/news/news250120) models to think more deeply by extending their reasoning process. It uses [unsloth](https://github.com/unsloth/unsloth) optimized models for better performance and unlimited context length (only limited by available VRAM).

The app works by detecting when the model tries to conclude thoughts too early and replacing those with prompts that encourage additional reasoning, continuing until a minimum threshold of thinking set by you is reached.

<br>
<br>

App by [anzorq](https://twitter.com/hahahahohohe). If you like it, please consider supporting me:

[<a href="https://www.buymeacoffee.com/anzorq" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="45px" width="162px" alt="Buy Me A Coffee"></a>](https://www.buymeacoffee.com/anzorq)

---

## Features
- 🤔 Force models to think longer and more thoroughly
- 🔄 Customizable reasoning extensions and thinking thresholds
- 🎯 Fine-grained control over model parameters (temperature, top-p, etc.)
- 💭 Visible thinking process with token count tracking
- 📝 LaTeX support for mathematical expressions
- 🖥️ Optimized for various VRAM configurations
- ♾️ Unlimited context length (VRAM-dependent)

## Credits
- Original idea and implementation - [vgel's gist](https://gist.github.com/vgel/8a2497dc45b1ded33287fa7bb6cc1adc)
- DeepSeek LLM - https://github.com/deepseek-ai/DeepSeek-LLM
- unsloth - https://github.com/unsloth/unsloth
- Gradio - https://github.com/gradio-app/gradio

<br>

[![Visitors](https://api.visitorbadge.io/api/visitors?path=qunash%2Fr1-overthinker&labelColor=%23d9e3f0&countColor=%23263759)](https://visitorbadge.io/status?path=qunash%2Fr1-overthinker) 