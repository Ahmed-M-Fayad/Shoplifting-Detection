# Shoplifting Detection Model

> ⚠ **Note:** An issue occurred during training that prevented the results from fully meeting expectations.  
> The complete **training notebook** and **results directory** are still available for reference.

## Model Overview
- **Architecture**: ResNet50 (feature extraction) + GRU (sequence modeling)
- **Input**: Video sequences of 20 frames at 224x224 resolution
- **Classes**: N/A
- **Test Accuracy**: 100.00% if 'test_accuracy' in locals() else 'N/A'

## Files in this directory:
- `shoplifting_detection_model.keras`: Main trained model
- `preprocessing_components.pkl`: Scaler and label processor
- `complete_results_summary.json`: Detailed training and performance metrics
- `model_summary.txt`: Model architecture details
- `README.md`: This file

## Usage:
Load the model using the code in Section 13 of the notebook.

## Training Details:
- Trained on Google Colab
- Dataset: 855 videos (855 successfully processed)
- Training samples: N/A
- Test samples: N/A
- GPU: /device:GPU:0

Generated automatically by the shoplifting detection notebook.
                            
