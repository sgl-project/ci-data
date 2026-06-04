# Diffusion Cross-Framework Performance Dashboard

*Generated: Jun 04 | Commit: `14ed9b4`*

## Cross-Framework Performance Comparison

| Model | Risk | sglang (s) |
|-------|------|---------|
| FLUX.1-dev | ✅ | **7.03** |
| FLUX.2-dev | ✅ | **24.53** |
| Qwen-Image-2512 | ✅ | **12.73** |
| Qwen-Image-Edit-2511 | ✅ | **23.56** |
| Z-Image-Turbo | ✅ | **0.90** |
| Wan2.2-T2V-A14B-Diffusers | ✅ | **212.01** |
| Wan2.2-TI2V-5B-Diffusers | ✅ | **64.21** |
| LTX-2 | ✅ | **7.55** |
| LTX-2.3 | ✅ | **18.07** |
| Wan2.2-I2V-A14B-Diffusers | ✅ | **207.65** |

### Latency Trend: flux1_dev_t2i_1024

![Latency Trend flux1_dev_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_flux1_dev_t2i_1024.png)


### Latency Trend: flux2_dev_t2i_1024

![Latency Trend flux2_dev_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_flux2_dev_t2i_1024.png)


### Latency Trend: qwen_image_2512_t2i_1024

![Latency Trend qwen_image_2512_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_qwen_image_2512_t2i_1024.png)


### Latency Trend: qwen_image_edit_2511

![Latency Trend qwen_image_edit_2511](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_qwen_image_edit_2511.png)


### Latency Trend: zimage_turbo_t2i_1024

![Latency Trend zimage_turbo_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_zimage_turbo_t2i_1024.png)


### Latency Trend: wan22_t2v_a14b_720p

![Latency Trend wan22_t2v_a14b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_t2v_a14b_720p.png)


### Latency Trend: wan22_ti2v_5b_720p

![Latency Trend wan22_ti2v_5b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_ti2v_5b_720p.png)


### Latency Trend: ltx2_twostage_t2v

![Latency Trend ltx2_twostage_t2v](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_ltx2_twostage_t2v.png)


### Latency Trend: ltx2.3_twostage_ti2v_2gpus

![Latency Trend ltx2.3_twostage_ti2v_2gpus](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_ltx2.3_twostage_ti2v_2gpus.png)


### Latency Trend: wan22_i2v_a14b_720p

![Latency Trend wan22_i2v_a14b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_i2v_a14b_720p.png)


## SGLang Performance Trend (Last 30 Runs)

| Date | Commit | flux1_dev_t2i_1024 (s) | flux2_dev_t2i_1024 (s) | qwen_image_2512_t2i_1024 (s) | qwen_image_edit_2511 (s) | zimage_turbo_t2i_1024 (s) | wan22_t2v_a14b_720p (s) | wan22_ti2v_5b_720p (s) | ltx2_twostage_t2v (s) | ltx2.3_twostage_ti2v_2gpus (s) | wan22_i2v_a14b_720p (s) | Trend |
|------|--------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-------|
| Jun 04 | `14ed9b4` | 7.03 | 24.53 | 12.73 | 23.56 | 0.90 | 212.01 | 64.21 | 7.55 | 18.07 | 207.65 | :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow: |
| Jun 03 | `83bc776` | 7.06 | 25.15 | 12.73 | 23.57 | 0.90 | 212.26 | 64.20 | 7.58 | 21.08 | 207.65 | :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :arrow_down:  :left_right_arrow: |
| Jun 01 | `373cadc` | 7.04 | 24.59 | 12.74 | 23.65 | 0.90 | 212.46 | 64.16 | 8.16 | 23.08 | 207.52 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| May 31 | `9b4be9c` | 7.09 | 24.66 | 12.83 | 24.82 | 0.92 | 212.42 | 65.17 | 8.06 | 23.08 | 207.50 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :arrow_down:  :left_right_arrow: |
| May 30 | `c2ac37d` | 7.13 | 24.65 | 12.84 | 23.80 | 0.92 | 212.39 | 65.24 | 8.47 | 28.11 | 208.66 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :arrow_up:  :left_right_arrow: |
| May 29 | `a8cfae0` | 7.09 | 24.69 | 12.89 | 23.76 | 0.90 | 212.73 | 65.20 | 7.56 | 20.07 | 207.62 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :arrow_down:  :left_right_arrow: |
| May 28 | `421bda6` | 7.06 | 24.50 | 12.75 | 23.65 | 0.91 | 212.60 | 65.19 | N/A | 21.08 | 207.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :arrow_up:  :left_right_arrow: |
| May 27 | `737c6cd` | 7.11 | 24.67 | 12.91 | 23.77 | 0.90 | 212.76 | 65.19 | 7.54 | 17.06 | 208.67 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow: |
| May 26 | `8f2a4e7` | 7.10 | 24.67 | 12.86 | 23.76 | 0.90 | 212.72 | 65.20 | 7.55 | 22.07 | 207.57 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow: |
| May 25 | `ed179bf` | 7.14 | 24.60 | 12.83 | 23.76 | 0.90 | 212.84 | 65.20 | 7.59 | 17.07 | 208.61 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :arrow_down:  :left_right_arrow: |
| May 24 | `af8f669` | 7.06 | 24.48 | 12.75 | 23.59 | 0.91 | 214.35 | 64.14 | 8.35 | 24.07 | 212.44 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow: |
| May 23 | `c112f76` | 7.04 | 24.48 | 12.70 | 23.63 | 0.91 | 214.46 | 64.17 | 8.23 | 22.06 | 211.54 | :arrow_up:  :arrow_up:  :left_right_arrow:  :arrow_down:  :arrow_down:  :left_right_arrow:  :arrow_up:  :arrow_down:   :left_right_arrow: |
| May 22 | `ff700aa` | 6.68 | 22.77 | 12.89 | 24.13 | 0.94 | 216.10 | 59.18 | 8.57 | N/A | 212.54 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow: |
| May 22 | `ff700aa` | 6.62 | 22.60 | 12.77 | 23.95 | 0.93 | 215.70 | 59.19 | 8.49 | N/A | 211.59 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:   :left_right_arrow:  :arrow_down:   |
| May 22 | `16b3edc` | 6.63 | 22.78 | 12.80 | 23.83 | 0.91 | N/A | 59.16 | 9.46 | 22.07 | N/A | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:   :left_right_arrow:  :arrow_up:  :arrow_up:  |
| May 21 | `c4a7d12` | 6.57 | 22.53 | 12.66 | 23.55 | 0.89 | 215.71 | 58.19 | 8.84 | 20.07 | 210.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :arrow_up:  :left_right_arrow: |
| May 20 | `7f154ba` | 6.57 | 22.61 | 12.72 | 23.52 | 0.89 | 215.30 | 58.19 | 8.58 | 19.07 | 210.64 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| May 19 | `dbac464` | 6.65 | 22.68 | 12.79 | 23.84 | 0.90 | 216.13 | 59.20 | 8.62 | 19.07 | 211.64 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow: |
| May 18 | `b380316` | 6.58 | 22.52 | 12.69 | 23.56 | 0.89 | 215.85 | 58.15 | 8.58 | 25.08 | 211.55 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow: |
| May 17 | `229cade` | 6.67 | 22.78 | 12.81 | 23.75 | 0.89 | 216.27 | 59.19 | 8.62 | 19.07 | 212.61 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow: |
| May 16 | `99fc29d` | 6.67 | 22.77 | 12.90 | 24.05 | 0.94 | 215.93 | 59.17 | 8.49 | N/A | 211.62 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:    :left_right_arrow: |
| May 08 | `3c3f0bd` | 6.60 | 22.60 | 12.72 | 23.85 | 0.93 | 211.58 | 59.20 | N/A | N/A | 207.62 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow:    :left_right_arrow: |
| May 06 | `b91b05a` | 6.68 | 22.79 | 12.90 | 24.08 | 0.93 | N/A | 59.21 | 11.00 | 40.14 | 208.67 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow: |
| May 04 | `c611a3f` | 6.63 | 22.62 | 13.07 | 23.91 | 0.91 | 210.23 | 59.17 | 11.72 | 40.12 | 205.57 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :arrow_down:  :arrow_down: |
| May 03 | `d44eb43` | 6.69 | 22.92 | 13.22 | 24.12 | 0.89 | 210.75 | 60.17 | 12.09 | 53.14 | 226.73 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:   :arrow_up: |
| Apr 30 | `3553fd0` | 6.74 | 22.93 | 13.25 | 24.03 | 0.90 | 212.47 | 62.18 | 11.99 | N/A | 207.63 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow: |
| Apr 29 | `14b4e6f` | 6.69 | 22.78 | 13.16 | 23.84 | 0.89 | 210.95 | 62.20 | 11.88 | N/A | 207.67 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow: |
| Apr 28 | `4a04a98` | 6.69 | 22.75 | 13.28 | 23.89 | 0.89 | 211.33 | 61.19 | 11.84 | N/A | 208.57 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:   :left_right_arrow: |
| Apr 27 | `977830e` | 6.72 | 22.91 | 13.24 | 23.91 | 0.89 | 212.10 | 63.20 | 11.80 | N/A | 208.53 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:   :left_right_arrow: |
| Apr 26 | `7141735` | 6.71 | 22.84 | 13.24 | 23.89 | 0.89 | 212.74 | 62.22 | 11.86 | N/A | 208.55 | -- |

---
*Generated by `generate_diffusion_dashboard.py` in SGLang nightly CI.*
