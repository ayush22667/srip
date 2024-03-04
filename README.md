# srip
Introduction
In this study, we analyze a dataset consisting of 90 distinct animal images. Our objective is to explore various classification tasks using this dataset. Initially, we will organize the data for one-vs-rest classification as binary classification, and addressing a 5-class classification challenge. To assess the efficacy of these two classification model, we will employ classification matrices for comprehensive evaluation.

Classification Techniques
One-vs-Rest Classification:
Initially, we organize the dataset to facilitate one-vs-rest classification. This approach involves training a separate classifier for each class while treating all other classes as a single class. Consequently, we iteratively train multiple classifiers, each distinguishing between one class and the rest.

5-Class Classification:
Finally, we address a more complex classification scenario involving five distinct classes. This setup requires the development of a classification model capable of accurately assigning each input image to one of the five predefined classes.

Model
The dataset underwent analysis utilizing three distinct architectures: CustomNN with attention mechanism, MobileNet, and EfficientNet. Across all cases examined, the test accuracy consistently surpassed the remarkable threshold of 99.5%.

Evaluation
To gauge the effectiveness of each classification model, we employ classification matrices. These matrices provide a comprehensive overview of the model's performance by presenting key metrics such as accuracy, and precision, recall, and F1-score can be calculated by using the printed confusion matrix for each class. By analyzing these metrics, we can identify the strengths and weaknesses of each classification approach, enabling informed decision-making regarding model selection and refinement.
