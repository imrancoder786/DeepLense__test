## Super-Resolution on Real Telescope Data

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


###  Super-Resolution Visualization 
![SR Visualization](ouputs/sample_visualizations.png)

---
