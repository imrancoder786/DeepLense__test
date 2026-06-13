## Task VI.B: Super-Resolution on Real Telescope Data

### Dataset
- **300 real image pairs**
- Sources: **HSC & HST telescopes**
- Limited dataset size

---

### Preprocessing & Augmentation

- Min-Max normalization
- Data augmentation:
  - Rotation (90°, 180°, 270°)
  - Horizontal & Vertical Flip
  - Noise Injection

---

### Model: EDSR (Best for Real Data)

- Residual-based SR architecture
- Effective for small datasets

---

### Results

#### Bicubic Baseline

| Metric | Value |
|--------|------|
| MSE    | 0.005888 |
| PSNR   | 23.58 dB |
| SSIM   | 0.3724 |

---

#### Final Model (EDSR)

| Metric | Value |
|--------|------|
| MSE    | 0.000683 |
| PSNR   | 35.6530 dB |
| SSIM   | 0.8853 |

---


### Training History (Task VI.B)
![Training History](project_task/task_2/ouputs/Tranning_Historys.png) 

###  Super-Resolution Visualization (Task VI.B)
![SR Visualization](project_task/task_2/ouputs/sample_visualizations.png)

---
