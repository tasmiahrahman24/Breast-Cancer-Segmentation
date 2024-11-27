# Breast Cancer Image Segmentation Using Attention UNet

This project implements a custom **Attention U-Net** architecture for the segmentation of breast cancer images using the **Breast Ultrasound Images Dataset**. The model focuses on accurately segmenting breast ultrasound images by combining the strengths of U-Net and attention mechanisms to enhance segmentation performance.

## Project Features
- **Model Architecture**: The model is based on U-Net, enhanced with attention gates for better focusing on important regions in the images.
- **Dataset**: Utilizes the Breast Ultrasound Images Dataset, which includes 780 images categorized as normal, benign, and malignant.
- **Training Strategy**: The model is trained with binary cross-entropy loss and optimized using the Adam optimizer. Metrics such as accuracy and Intersection over Union (IoU) are used to evaluate model performance.
- **Evaluation**: Model performance is validated using unseen data to ensure generalization and segmentation quality.

## Technologies Used
- **TensorFlow & Keras**: For model implementation.
- **Attention Mechanism**: To selectively focus on relevant parts of the input image during segmentation.
- **Python Libraries**: Includes NumPy, TensorFlow, Matplotlib, and more for data processing, model training, and visualization.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/breast-cancer-segmentation.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset) and place it in the `data/` folder.

4. Run the training script:
    ```bash
    python train_model.py
    ```

5. Visualize results using:
    ```bash
    python visualize_results.py
    ```

## Conclusion
This project demonstrates the effectiveness of combining **attention mechanisms** with **U-Net architecture** for semantic segmentation, achieving high performance in breast cancer image segmentation tasks.
