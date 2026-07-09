# SGLang-Diffusion Nightly Performance Dashboard

*Generated: Jul 09 | Commit: `074bb92`*

> [!WARNING]
> **Performance Regression Detected**
>
> - **ltx2.3_twostage_ti2v_2gpus** (sglang): 16.06s -> 17.07s (+6.3%)


## SGLang-Diffusion Performance

| Model | Risk | sglang (s) |
|-------|------|---------|
| FLUX.1-dev | ✅ | **4.87** |
| FLUX.2-dev | ✅ | **14.45** |
| Qwen-Image-2512 | ✅ | **10.74** |
| Qwen-Image-Edit-2511 | ✅ | **15.41** |
| Z-Image-Turbo | ✅ | **0.83** |
| Wan2.2-T2V-A14B-Diffusers | ✅ | **210.74** |
| Wan2.2-TI2V-5B-Diffusers | ✅ | **65.24** |
| LTX-2.3 | ⚠️ | **17.07** |
| ideogram-4-fp8 | ✅ | **5.34** |
| Cosmos3-Super | ✅ | **116.33** |
| Wan2.2-I2V-A14B-Diffusers | ✅ | **204.68** |

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


### Latency Trend: ltx2.3_twostage_ti2v_2gpus

![Latency Trend ltx2.3_twostage_ti2v_2gpus](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_ltx2.3_twostage_ti2v_2gpus.png)


### Latency Trend: ideogram4_fp8_t2i_2gpu

![Latency Trend ideogram4_fp8_t2i_2gpu](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_ideogram4_fp8_t2i_2gpu.png)


### Latency Trend: cosmos3_super_t2v_2gpu

![Latency Trend cosmos3_super_t2v_2gpu](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_cosmos3_super_t2v_2gpu.png)


### Latency Trend: wan22_i2v_a14b_720p

![Latency Trend wan22_i2v_a14b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_i2v_a14b_720p.png)


## SGLang Performance Trend (Last 30 Runs)

| Date | Commit | flux1_dev_t2i_1024 (s) | flux2_dev_t2i_1024 (s) | qwen_image_2512_t2i_1024 (s) | qwen_image_edit_2511 (s) | zimage_turbo_t2i_1024 (s) | wan22_t2v_a14b_720p (s) | wan22_ti2v_5b_720p (s) | ltx2.3_twostage_ti2v_2gpus (s) | ideogram4_fp8_t2i_2gpu (s) | cosmos3_super_t2v_2gpu (s) | wan22_i2v_a14b_720p (s) | Trend |
|------|--------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-------|
| Jul 09 | `074bb92` | 4.87 | 14.45 | 10.74 | 15.41 | 0.83 | 210.74 | 65.24 | 17.07 | 5.34 | 116.33 | 204.68 | :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 08 | `d7dcdf3` | 4.85 | 14.45 | 11.00 | 15.45 | 0.82 | 210.76 | 65.22 | 16.06 | 5.34 | 116.39 | 204.66 | :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 08 | `9a6f8e5` | 4.86 | 14.44 | 11.60 | 15.46 | 0.83 | 210.71 | 65.20 | 16.07 | 5.34 | 116.37 | 204.71 | :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 07 | `9a6f8e5` | 4.82 | 14.36 | 8.77 | 15.25 | 2.13 | 210.69 | 64.24 | 13.07 | 5.27 | 115.38 | 203.70 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 07 | `6c1fb8a` | 4.81 | 14.36 | 8.78 | 15.28 | 0.80 | 210.67 | 64.22 | 13.06 | 5.31 | 115.39 | 203.73 | :arrow_down:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 06 | `8673e85` | 5.12 | 14.46 | 9.34 | 15.43 | 0.80 | 210.67 | 65.18 | 13.05 | 5.33 | 116.32 | 205.76 | :arrow_up:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 05 | `754524d` | 4.87 | 14.57 | 10.80 | 15.44 | 0.82 | 210.75 | 65.23 | 16.07 | 5.34 | 115.38 | 204.67 | :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 04 | `b28bc10` | 4.82 | 14.38 | 8.93 | 15.31 | 0.81 | 210.68 | 64.19 | 13.05 | 5.32 | 115.38 | 204.62 | :left_right_arrow:  :left_right_arrow:  :arrow_down:  :arrow_down:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 03 | `75cdaf4` | 4.88 | 14.47 | 29.73 | 24.46 | 0.98 | 210.69 | 65.21 | 17.07 | 5.33 | 116.34 | 204.64 | :left_right_arrow:  :left_right_arrow:  :arrow_up:  :arrow_down:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 02 | `a3f6680` | 4.82 | 14.39 | 12.81 | 25.32 | 0.81 | 210.68 | 65.19 | 13.05 | 5.31 | 115.39 | 204.68 | :left_right_arrow:  :arrow_down:  :left_right_arrow:  :arrow_up:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jul 01 | `5b76f55` | 4.85 | 15.09 | 12.91 | 23.97 | 1.45 | 210.75 | 65.19 | 16.07 | 5.35 | 115.37 | 204.71 | :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow: |
| Jun 30 | `bc8b3ab` | 4.89 | 14.49 | 12.90 | 23.80 | 0.82 | 210.72 | 65.25 | 13.06 | 5.33 | 115.36 | 205.74 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down: |
| Jun 29 | `abaee46` | 4.87 | 14.49 | 12.85 | 23.66 | 0.83 | 210.57 | 65.18 | 17.07 | 5.35 | 116.32 | 270.90 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up: |
| Jun 28 | `8648127` | 4.87 | 14.54 | 12.91 | 23.88 | 0.83 | 210.75 | 65.24 | 17.07 | 5.36 | 115.38 | 204.66 | :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 28 | `da802dd` | 4.67 | 14.31 | 12.80 | 23.81 | 0.79 | 209.97 | 65.18 | 13.05 | N/A | N/A | 205.57 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 27 | `c570130` | 4.76 | 14.37 | 12.80 | 23.72 | 0.75 | 209.20 | 65.23 | 16.07 | 5.25 | 114.52 | 204.58 | :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down:  :arrow_down: |
| Jun 27 | `528f170` | 10.97 | 24.21 | 26.21 | 36.95 | 13.46 | 221.57 | 70.21 | 40.16 | 11.50 | 143.65 | 211.72 | :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up: |
| Jun 27 | `b78e95c` | 4.68 | 14.31 | 12.81 | 23.77 | 0.65 | 209.17 | 65.22 | 16.06 | 5.19 | 113.80 | 204.59 |      :left_right_arrow:  :left_right_arrow:  :arrow_up:   :left_right_arrow:  :left_right_arrow: |
| Jun 27 | `a526ca2` | N/A | N/A | N/A | N/A | N/A | 209.33 | 65.19 | 15.05 | N/A | 113.74 | 204.61 |      :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    |
| Jun 27 | `13b5bd9` | 4.68 | 14.31 | 12.79 | 23.65 | 0.65 | 209.32 | 64.20 | 15.05 | N/A | N/A | N/A | :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    |
| Jun 26 | `781537b` | 4.63 | 15.76 | 12.69 | 23.60 | 0.82 | 208.96 | 64.24 | 14.05 | N/A | N/A | 205.62 | :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 25 | `7002a37` | 4.68 | 14.32 | 12.75 | 23.62 | 0.66 | 209.34 | 64.22 | 15.06 | N/A | N/A | 204.64 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 24 | `5e6d7c1` | 4.68 | 14.36 | 12.82 | 23.75 | 0.64 | 209.73 | 65.22 | 14.06 | N/A | N/A | 205.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 23 | `7e6587c` | 4.68 | 14.35 | 12.84 | 23.79 | 0.64 | 209.91 | 65.20 | 14.05 | N/A | N/A | 205.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 23 | `a17753e` | 4.68 | 14.34 | 12.80 | 23.72 | 0.64 | 211.07 | 65.22 | 14.05 | N/A | N/A | 205.68 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 22 | `6779ca8` | 4.65 | 14.37 | 12.83 | 23.76 | 0.64 | 209.96 | 65.23 | 14.05 | N/A | N/A | 205.58 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 21 | `2552b86` | 4.67 | 14.33 | 12.74 | 23.63 | 0.65 | 209.38 | 64.15 | 19.07 | N/A | N/A | 204.55 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 20 | `2cbe1e6` | 4.65 | 14.33 | 12.78 | 23.63 | 0.66 | 209.30 | 64.20 | 15.05 | N/A | N/A | 205.54 | :arrow_down:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 19 | `05ee93c` | 6.99 | 24.86 | 12.81 | 23.75 | 0.91 | 209.14 | 65.23 | 15.06 | N/A | N/A | 204.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 18 | `74e2e48` | 6.93 | 24.48 | 12.71 | 23.57 | 0.92 | 209.03 | 64.21 | 24.08 | N/A | N/A | 204.67 | -- |

> [!CAUTION]
> **Action Required — Performance Alert**
>
> The following cases need attention:
> - ltx2.3_twostage_ti2v_2gpus: SGLang regression +13.3% vs 3-run avg (17.07s vs 15.07s)


---
*Generated by `generate_diffusion_dashboard.py` in SGLang nightly CI.*
