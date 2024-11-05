<div align="center">
<h2>Enhancing Road Safety: Real-Time Detection of Driver Distraction through CNNs 🚗💡</h2>

[**Amaan Aijaz Sheikh**](https://github.com/AmaanAijaz)<sup>1</sup> · [**Imaad Zaffar Khan**](https://github.com/imaad786)<sup>1</sup>

<sup>1</sup>University of Illinois at Urbana-Champaign



<a href="https://arxiv.org/abs/2405.17788"><img src='https://img.shields.io/badge/arXiv-DriverDistraction-red' alt='Paper PDF'></a>

</div>

# 🌟 Highlights

- Developed a **CNN-based system** for detecting driver distractions in real-time, enhancing automotive safety.
- Evaluated multiple **CNN architectures** (SimpleCNN, VGG16, VGG19, and Hybrid CNN-Transformer) for accuracy and efficiency.
- Achieved **high accuracy** while balancing computational demands, offering a practical solution for in-vehicle safety systems.

# 🚀 Introduction 

This project leverages **Convolutional Neural Networks (CNNs)** to detect driver distractions, addressing a critical issue in road safety. By assessing various CNN architectures, including VGG16, VGG19, and a Hybrid CNN-Transformer model, the system aims to deliver real-time, accurate detection to prevent accidents triggered by inattention.

# 🎯 Core Objectives

1. **Model Exploration**: Evaluate the capabilities of different CNN models for distraction detection.
2. **Real-Time Efficiency**: Achieve high-speed processing suitable for real-time deployment in vehicles.
3. **Accuracy and Robustness**: Optimize models for precise detection under diverse conditions, ensuring safety across varying driving environments.

# 🛠️ Methodology

Our approach involved the following steps:

1. **Data Preprocessing**: Applied standardization, augmentation, and brightness/contrast adjustments to ensure consistency in varied lighting conditions.
2. **CNN Architecture Testing**: Evaluated multiple configurations (SimpleCNN, VGG16, VGG19, and a Hybrid CNN-Transformer) for optimal performance.
3. **Performance Optimization**: Implemented early stopping and model checkpointing for efficient training, preventing overfitting.


# 🔬 Evaluation & Testing

We utilized the **State Farm Distracted Driver Detection** dataset and evaluated our models using **accuracy** and **training loss** metrics. Comparative analysis with existing approaches showcased significant advancements in balancing accuracy with processing speed.

## Comparative Analysis

### Accuracy & Elapsed Time Comparison

<div align="center">

| **Model**              | **Accuracy** | **Elapsed Time (s)** |
|------------------------|--------------|-----------------------|
| Simple CNN             | 0.89        | 10.56                |
| VGG16 Deep             | 0.95        | 10.95                |
| VGG16 Shallow          | 0.93        | 9.14                 |
| VGG16 Fine-Tuned       | 0.96        | 9.07                 |
| VGG19 Deep             | 0.94        | 10.68                |
| VGG19 Shallow          | 0.94        | 9.68                 |
| VGG19 Fine-Tuned       | 0.98        | 8.89                 |
| Hybrid CNN-Transformer | 0.98        | 11.05                |

</div>

This table highlights the **trade-off between accuracy and computational efficiency**, with fine-tuned models performing best in accuracy, making them ideal for real-time applications.

# 💡 Key Findings

- **Optimal Model Choice**: VGG19 Fine-Tuned and Hybrid CNN-Transformer achieved the highest accuracy, balancing complexity and detection reliability.
- **Efficiency**: Fine-tuned VGG models were the most computationally efficient, suitable for real-time integration into vehicle systems.

## 📈 Results & Comparisons

The models were benchmarked against standard CNN architectures, demonstrating the enhanced performance of fine-tuned and hybrid approaches, especially in terms of **precision** and **computational speed** for driver distraction detection.

## 🌍 Future Directions

Plans for future work include:
- **Scalability Testing** on diverse datasets to validate model robustness.
- **Exploring Lightweight Architectures** for resource-limited devices.
- **Enhanced Real-Time Processing** using advanced model pruning techniques.

---

# Citing this Project

To reference this project, use the following BibTeX entry:

```latex
@article{khan2024driversafety,
  title={Enhancing Road Safety: Real-Time Detection of Driver Distraction through CNNs},
  author={ Sheikh, Amaan Aijaz and Khan, Imaad Zaffar},
  journal={arXiv preprint arXiv:2405.17788v1 },
  year={2024}
}
