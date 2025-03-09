# AeroUNet3+: Attention-aware UNet3+ for UAV Semantic Segmentation

AeroUNet3+ is an enhanced UNet3+ model designed for UAV aerial imagery segmentation, integrating **Convolutional Block Attention Module (CBAM)** and **Atrous Convolution** for improved feature selection and receptive field expansion. This model achieves state-of-the-art accuracy while maintaining computational efficiency.

## Features
- **Attention-Enhanced Segmentation:** CBAM refines feature maps using channel and spatial attention.
- **Expanded Receptive Field:** Atrous Convolution captures multi-scale contextual information.
- **Improved Accuracy:** Achieves **67.58% mIoU on AeroScapes** and **49.60% on UAVid** datasets.
- **Class Imbalance Mitigation:** Uses **Focal Loss** and **data augmentation** to improve model robustness.
- **Lightweight & Efficient:** Balances computational efficiency with high segmentation accuracy.

## Tech Stack
- **Deep Learning Framework:** PyTorch
- **Architecture:** UNet3+ with CBAM and Atrous Convolution
- **Datasets:** AeroScapes, UAVid
- **Optimization:** Focal Loss, Data Augmentation

## Setup & Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/AeroUNet3.git
   cd AeroUNet3
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Train the model:
   ```sh
   python train.py --dataset aeroscapes
   ```
4. Evaluate performance:
   ```sh
   python evaluate.py --dataset uavid
   ```

## Publication
This work has been submitted for publication at **IEEE GCON 2025**.

## Contributors
- **Arijit** – Lead Developer & Researcher
- **Anirban Paul** – Researcher & Developer
- **Piyush Roy** – Researcher & Developer

### Mentor
- **Alexy Bhowmick**

## License
This project is licensed under the MIT License.

## Screenshots
Below are images showcasing AeroUNet3+ segmentation results:

![Segmentation Screenshot 1](https://github.com/ArijitRoy22/AeroUNet3-/blob/main/Images/MeanIoU_Uavid.JPG)
![Segmentation Screenshot 2](https://github.com/ArijitRoy22/AeroUNet3-/blob/main/Images/MeanIoU_Aero.JPG)
![Segmentation Screenshot 3](https://github.com/ArijitRoy22/AeroUNet3-/blob/main/Images/Uavid.JPG)
![Segmentation Screenshot 4](https://github.com/ArijitRoy22/AeroUNet3-/blob/main/Images/Aero.JPG)

