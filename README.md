## 🫁 Pneumonia Detection using Chest X-Rays:
This project applies deep learning to detect pneumonia in chest X-ray images using object detection models. 
It compares RetinaNet, Fast R-CNN, and an ensemble model to find the most accurate and efficient approach. 

### Project Structure:
- pneumonia_detection.ppt : project presentation.
- pneumonia_detection_using_DeepLearning.docx: project detailed report.
- dl_for_medical_imaging.ipynb: All training, evaluation, and preprocessing code.

### Dataset:
- RSNA Pneumonia detection challenge Dataset.
- Source: Kaggle.

### Models Used:
1. RetinaNet:
    - Focal loss to handle class imbalance.
    - Great at detecting difficult or unclear cases.
      
2. FastRCNN:
   - ROI Pooling wih regional proposals.
     
3. Ensemble:
   - Combined predictions from both models for enhanced accuracy.
   
### Evaluation Metrics:
- AUC curve.
- Precision,Recall,F1-score.
- Confusion Matrix.

### Feedback Loop: 
A simple feedback loop  was also implemented for RetinaNet to allow correction and continuous model improvement.
