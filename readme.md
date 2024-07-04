# Чутка информации по sd/invoke

## Модели

NSFW модели https://gigazine.net/gsc_news/en/20221004-stable-diffusion-models-matome/

| Название                                                     | Описание и настройки                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| gg1342*.ckpt                                                 | The model was trained on 280 NSFW (extreme content that should be viewed with caution at work) images and 80 SFW images of fictional characters, and is said to be suitable for generating live-action images |
| [f222](https://civitai.com/models/1188/f222)                 |                                                              |
| bf_fb_v3_t4_b16_noadd-ema-pruned-fp16.ckpt                   | Bare Feet / Full Body b4_t16_noadd is a model trained on a carefully selected dataset of images that include bare feet and full nudity. An image actually generated with Bare Feet / Full Body b4_t16_noadd has been posted on the image sharing site Imgur. |
| [realisticVision](https://civitai.com/models/4201?modelVersionId=501240) | Sampler: DPM++ SDE Karras or another / 4-6+ steps<br />CFG Scale: 1.5-2.0 / 3,5-7 (the lower the value, the more mutations, but the less contrast)<br/>Hires. fix with 4x-UltraSharp upscaler<br />Denoising strength: 0.25-0.45<br />Upscale by: 1.1-2.0<br />Clip Skip: 1-2<br />I also recommend using ADetailer for generation (some examples were generated with ADetailer, this will be noted in the image comments).<br />Prompt: RAW photo, subject, 8k uhd, dslr, soft lighting, high quality, film grain, Fujifilm XT3<br />Negative Prompt: (deformed iris, deformed pupils, semi-realistic, cgi, 3d, render, sketch, cartoon, drawing, anime), text, cropped, out of frame, worst quality, low quality, jpeg artifacts, ugly, duplicate, morbid, mutilated, extra fingers, mutated hands, poorly drawn hands, poorly drawn face, mutation, deformed, blurry, dehydrated, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, missing arms, missing legs, extra arms, extra legs, fused fingers, too many fingers, long neck, UnrealisticDream |
| [LazyMix+ (Real Amateur Nudes)](https://civitai.com/models/10961/lazymix-real-amateur-nudes) |                                                              |

## LoRAs

| Название                                                     | Описание и настройки                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Shirtlift: a LORA for flashing tits](https://civitai.com/models/6693/shirtlift-a-lora-for-flashing-tits) | Trigger Words: shirtlift                                     |
| [[Free] Breast Helper 1.2](https://civitai.com/models/17875/free-breast-helper-12) | Trigger Words: flat breast,small breast,medium breast, big breast,fake breast,bimbo breast,sagge breast,torpedo breast,normal_nipples, normal_areolae, pink_nipples |
| [Droptop](https://civitai.com/models/49044/droptop)          | Trigger Words: droptop                                       |
| [Breasts Out fashion clothing (SDXL) = 2BoutOvalXL4](https://civitai.com/models/91780/breasts-out-fashion-clothing-or) | Trigger Words: breasts cutout                                |
| [Flashing Tits #1 (shirtlift) SDXL](https://civitai.com/models/126320/flashing-tits-1-shirtlift-sdxl) | Trigger Words: shirtlift                                     |
| [RetouchPhoto for PonyV6](https://civitai.com/models/343602/retouchphoto-for-ponyv6) | Trigger Words: photo, realistic, irl<br />Weight: 0.6+<br />Sampling method: DPM++ 2M SDE Karras / Restart<br />Negative prompts: score_6_up, score_5_up, score_4_up, text, watermark, low-quality, signature, moiré pattern, downsampling, aliasing, distorted, blurry, glossy, blur, jpeg artifacts, compression artifacts, poorly drawn, low-resolution, bad, distortion, twisted, excessive, exaggerated pose, exaggerated limbs, grainy, symmetrical, duplicate, error, pattern, beginner, pixelated, fake, hyper, glitch, overexposed, high-contrast, bad-contrast |
| [Skin & Hands (male/female) from Polyhedron](https://civitai.com/models/109043/skin-and-hands-malefemale-from-polyhedron) | Trigger Words: detailed skin, skin blemish                   |
| [SDXL Nudes](https://civitai.com/models/122601/sdxl-nudes)   | Trigger Words: nude                                          |

## Samplers

https://stable-diffusion-art.com/samplers/

Good speed: DPM++ 2M Karras
Good quality: DPM++ SDE Karras
?? DPM++ 2M SDE Karras

## Прочитать и формализовать

https://stable-diffusion-art.com/automatic1111-extensions/ Must-have AUTOMATIC1111 extensions

https://betterwaifu.com/blog/nsfw-prompts Must-have AUTOMATIC1111 extensions

https://safereactor.cc/post/5601957 Как перерисовать/раздеть любого персонажа с помощью Stable Diffusion

https://tryolabs.com/blog/2022/10/25/the-guide-to-fine-tuning-stable-diffusion-with-your-own-images The guide to fine-tuning Stable Diffusion with your own images
