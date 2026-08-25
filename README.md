# Human-Drawn Image Recognition — Kaggle Contest

### Key Results
Built a CNN model to classify human-drawn images, achieving **76.73% test accuracy** (see `Best_Kaggle_Submission.ipynb`). Applied data augmentation and pixel intensity normalization to improve generalization. A baseline linear SVM model and a denoising + CNN variant were also explored for comparison (see notebooks below).

### Tech Stack
[Confirm: PyTorch or TensorFlow/Keras?], NumPy, Google Colab

### Notebooks
- `Baseline_Kaggle_Submission.ipynb` — baseline linear SVM model
- `Best_Kaggle_Submission.ipynb` — best-performing CNN model (76.73% test accuracy)
- `Kaggle_Denoising_CNN.ipynb` — CNN variant with a denoising preprocessing step

### Reports
- `Kaggle_competition_report.pdf` — write-up of the approach and results
- `FML_HW4-ShadowBrokers.pdf` — course assignment submission

### How to Run
1. Open the notebook in Google Colab (links below, or upload the `.ipynb` file directly).
2. Ensure the dataset is placed at `/Kaggle/data` in your Google Drive.
3. Authorize Colab to connect to your Google Drive when prompted.
4. Run all cells in order.

**Colab links:**
- [Baseline Linear SVM](https://colab.research.google.com/drive/17iX2OyaHf7dbZ8Mow742le4J-vOzQOV3)
- [Best CNN](https://colab.research.google.com/drive/14Aca-KYZbw8rKE4kQ5h44Ac0OL0gpWrh)
- [Denoising + CNN](https://colab.research.google.com/drive/1msJUvZL1uHr9sDa-72BN-Wx1k9GGFpV5)
