# Brain-Tumor-Classification: CNN vs. Vision Transformers

This project compares the performance of Convolutional Neural Networks (CNN) and Vision Transformers (ViT) on MRI tumor detection.

## Results Summary

| Model | Type | Accuracy | Key Takeaway |
|-------|------|----------|--------------|
| **Custom CNN** | Convolutional | **97%** | Best performance, efficient on small data. |
| **ViT (Pre-trained)** | Transformer | **92%** | Competitive, requires transfer learning. |
| **ViT (From Scratch)**| Transformer | **65%** | Struggled due to lack of inductive bias & data. |

## Project Structure
* **`1_CNN_Baseline`**: Standard CNN implementation achieving state-of-the-art results.
* **`2_ViT_From_Scratch`**: Educational implementation of a ViT, including custom Patch Embedding and Encoder blocks.
* **`3_ViT_Transfer_Learning`**: Fine-tuning a Hugging Face ViT model.

## Usage
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Download the Brain Tumor Dataset (https://www.kaggle.com/datasets/ishans24/brain-tumor-dataset).
4. Run the notebooks in order.

## Article
Read the full breakdown of this experiment on my Medium blog: [Link to your article]
