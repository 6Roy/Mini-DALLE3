<p align="center">
<a href="#">
    <img src="https://github.com/Zeqiang-Lai/Mini-DALLE3/assets/26198430/11856c34-b5ef-4665-8cb9-8a6e366ae238" alt="minidalle3" width="19%">
    </a> &ensp; 
</p>

<p align="center">
    <b>Interactive Text to Image Generation </b>
</br>
<a href="#">Paper</a> •
<a href="#">Demo</a> •
<a href="minidalle3.github.io/">Project page</a> 
</p>

![teaser4](https://github.com/Zeqiang-Lai/Mini-DALLE3/assets/26198430/036959fc-c81c-4b52-8559-34af29009bb7)


> An experimental attempt to obtain the interactive and interleave text to image and text to text experience of [DALL•E 3](https://openai.com/dall-e-3) and [ChatGPT](https://openai.com/chatgpt).

## Try Yourself 🤗 

- Download the [checkpoint](https://huggingface.co/h94/IP-Adapter) and save it as following 
```bash
checkpoints
   - models
   - sdxl_models
```

- run the following commands, and you will get a gradio-based web demo.

```bash
export OPENAI_API_KEY="your key"
python -m minidalle3.web
```

## TODO

- [x] Support generating image interleaved in the conversations.
- [ ] Support generating multiple images at once.
- [ ] Support selecting image.
- [ ] Support refinement.
- [ ] Support prompt refinement/variation.
- [ ] Instruct tuned LLM/SD.


## Citation

If you find this repo helpful, please consider citing us.

```bibtex
@misc{minidalle3,
    author={Zeqiang Lai, Wenhai Wang},
    title={Mini-DALLE3: Interactive Text to Image Generation by Prompting Large Language Models},
    year={2023},
    url={https://github.com/Zeqiang-Lai/Mini-DALLE3},
}
```

## Acknowledgement

[IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) • [Stable Diffusion XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FZeqiang-Lai%2FMini-DALLE3&countColor=%23263759&style=flat)
