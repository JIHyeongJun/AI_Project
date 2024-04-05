# Control Net

## Scribble

lineart, white background, masterpiece, extremely detailed thick line drawing, 1girl , hoodie, animal gloves, skirt, sneakers,, smile, long hair, black hair,best quality, very aesthetic

Negative prompt: wings, nsfw, low quality, worst quality, normal quality,
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 5, Seed: 2806862934, Size: 1000x1000, Model hash: cbfba64e66, Model: counterfeitV30_v30, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: scribble_pidinet, Model: control_v11p_sd15_scribble [d4ba51ff], Weight: 1, Resize Mode: Crop and Resize, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: 1.8.0-RC

---

![image](https://github.com/JIHyeongJun/AI_Project/blob/main/ControlNet/Scribble_01.png?raw=true)


---

## Depth

Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1011914466, Size: 512x512, Model hash: 262e95d3ef, Model: noormix_v1, VAE hash: df3c506e51, VAE: vae-ft-mse-840000-ema-pruned.ckpt, ControlNet 0: "Module: depth_leres, Model: control_v11f1p_sd15_depth [cfd03158], Weight: 1, Resize Mode: Crop and Resize, Low Vram: False, Processor Res: 512, Threshold A: 0, Threshold B: 0, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: 1.8.0-RC

![image](![alt text](00025-1011914466.png))