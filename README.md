COVID Detection Using Transfer Learning:

->>Overview::

This project demonstrates the automatic detection of COVID-19 from chest X-ray images using deep learning techniques. The objective is to identify COVID-19 positive cases by applying Convolutional Neural Networks (CNN) and leveraging the power of Transfer Learning.

Models Used:
•	VGG19
•	ResNet50
•	InceptionNet (GoogleNet)

->>Approach:
I applied the Transfer Learning method by using pre-trained CNN architectures (VGG19, ResNet50, InceptionNet) and fine-tuned them on our chest X-ray dataset. The dataset consists of labeled X-ray images categorized into three classes: COVID-19, Pneumonia, and Normal. By comparing these models, I aimed to identify the most accurate model for COVID-19 detection.

->>Key Features:
•	Preprocessing of X-ray images (rescaling, resizing).
•	Fine-tuning CNN models with Transfer Learning.
•	Model evaluation based on accuracy, loss, and confusion matrix.
•	Detailed comparison of model performance using metrics like accuracy and loss.

->>Results:
The models were trained on a limited dataset and achieved the following accuracies:
•	VGG19: 98.33%
•	InceptionNet: 83.33%
•	ResNet50: 75.00%

->>Conclusion:
While VGG19 outperformed the other models in accuracy, the results suggest further validation with larger datasets for improved model robustness. This project demonstrates the feasibility of detecting COVID-19 via chest X-rays using state-of-the-art deep learning models.


