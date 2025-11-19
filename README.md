# Aircraft_Damage_Classification
This project uses transfer learning with VGG16 to classify aircraft damage as "dent" or "crack" and BLIP transformer model to generate natural language descriptions of the damage. The VGG16 model (pretrained on ImageNet with frozen base layers) achieved 71.88% test accuracy using a simple architecture with two 512-unit dense layers and 0.3 dropout, trained for 5 epochs on the Roboflow aircraft damage dataset. The BLIP model successfully generates captions and summaries that describe damage location and characteristics. While the model shows successful learning above the 50% baseline, overfitting was observed (15% gap between training and validation accuracy), which could be improved with data augmentation, callbacks, and reduced model complexity.

<img width="598" height="657" alt="image" src="https://github.com/user-attachments/assets/a5d61033-8ff0-443c-aae4-28d6c2e95d23" />
<img width="910" height="731" alt="image" src="https://github.com/user-attachments/assets/963b30e2-40c6-4190-af21-41ee84ec3e8d" />

