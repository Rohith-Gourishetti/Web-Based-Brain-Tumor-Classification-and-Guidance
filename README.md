#Dataset Link:
          https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

Problem Statement: Early detection and classification of brain tumors are crucial for effective treatment and improved patient outcomes. This project aims to develop a web-based brain tumor classification system that uses advanced deep learning models to accurately detect and classify brain tumors from medical images, providing timely and accurate information for healthcare professionals.

Methodology: The system leverages Convolutional Neural Networks (CNNs), employing architectures like ResNet101, ResNet50, VGG16, VGG19, and EfficientNetB0 for brain tumor classification. Among these, ResNet50 was identified as the most accurate model. The selected model was fine-tuned and deployed using Flask, where users can upload brain MRI images for analysis. If a tumor is detected, the system classifies it into one of three types and provides recommendations for potential reduction strategies. If no tumor is detected, the system simply displays "No tumor." The web-based deployment ensures accessibility and usability for healthcare providers in clinical settings.






