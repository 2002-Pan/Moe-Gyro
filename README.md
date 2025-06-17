# 🚀 MoE-Gyro: Self-Supervised Over-Range Reconstruction and Denoising for MEMS Gyroscopes


**Breakthrough in MEMS performance:** A **self-supervised hybrid architecture** that simultaneously **extends dynamic range by 3.3×** (±450°/s → ±1500°/s) and **reduces bias instability by 98.4%** with no additional hardware.

## 🔍 Problem Statement
MEMS gyroscopes face a fundamental tradeoff: increasing measurement range amplifies noise, while noise reduction limits dynamic range. Existing solutions require costly hardware modifications or calibrated ground truth data. **MoE-Gyro solves this .**

## ✨ Key Innovations
| **Component**               | **Innovation**                                                                 | **Performance Gain**              |
|------------------------------|--------------------------------------------------------------------------------|-----------------------------------|
| **Hybrid MoE Architecture**   | • **ORE Expert**: Gaussian Decay Attention (GD-Attn) reconstructs saturated signals<br>• **DE Expert**: Dual-branch masking + FFT denoising | Dynamic range: **3.3× ↑**<br>Noise: **98.4% ↓** |
| **Self-Supervised Training** | • Masked Autoencoder (MAE) framework<br>• Physics-Informed Neural Network (PINN) energy constraints | Zero ground-truth dependency      |


## 🛠️ ISEBench: IMU Signal Enhancement Benchmark
**First standardized evaluation platform for MEMS enhancement algorithms:**

Includes:​​

📊 ​​GyroPeak-100 Dataset​​: 100000+ real-world over-range sequences

⚖️ ​​7 Metrics​​: Bias instability, velocity random walk, etc.

🔧 ​​Evaluation Toolkit​​: Preprocessing scripts & baseline implementations

## 📈 Performance Highlights

​*Consumer-grade MEMS achieves strategic-grade performance*

<img width="900" alt="image" src="https://github.com/user-attachments/assets/691abd16-8c06-470c-a7bb-9b252ddc238c" />
<img width="900" alt="image" src="https://github.com/user-attachments/assets/b0fbbaef-2e6f-4f3d-8a3c-b10a36998886" />

Cite our work:​​

```bibtex
@misc{pan2025moegyroselfsupervisedoverrangereconstruction,
      title={MoE-Gyro: Self-Supervised Over-Range Reconstruction and Denoising for MEMS Gyroscopes}, 
      author={Feiyang Pan and Shenghe Zheng and Chunyan Yin and Guangbin Dou},
      year={2025},
      eprint={2506.06318},
      archivePrefix={arXiv},
      primaryClass={eess.SP},
      url={https://arxiv.org/abs/2506.06318}, 
}
```

## 🌐 Resources

📄 ​​Full Paper​​: https://arxiv.org/abs/2506.06318

💻 ​​Code & Data​​: https://figshare.com/s/03191f132008fbd3eaec

## Contact
If interested in our work, please contact us at:

- Feiyang Pan: 230238437@seu.edu.cn
