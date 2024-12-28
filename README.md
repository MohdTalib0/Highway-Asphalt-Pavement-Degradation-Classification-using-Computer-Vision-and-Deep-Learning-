# Results

## Precision-Recall Curve 

![image](https://github.com/OmdenaAI/port-harcourt-chapter-asphalt-degradation/assets/65142149/344a3d66-085b-4509-a587-0c6ddbfa7de9)

From the results shown above, we observe that the cracks and potholes classes present the best performance with an mAP of 0.617 for the pothole class and an mAP of 0.785 for the crack class while ruts and repairs classes have lower scores. 

This could be because cracks and potholes have more instances than ruts and repair classes as it is shown in the next figure.

![image](https://github.com/OmdenaAI/port-harcourt-chapter-asphalt-degradation/assets/65142149/a917afbf-f046-4ed3-aff8-19ab1f87b35a)

## Discussion of Results

[Results and metrics](https://docs.google.com/document/d/1SZ1vNSHybq_1-h_xrpS9BnTjqzwrlndm0oydPsb50WQ/edit?usp=sharing)

Based on the evaluation metrics and visualizations, it is evident that the YOLOv8 model demonstrates promising potential for detecting pavement defects. The overall accuracy for the classes with more instances in the training set ranges from 0.6 to 0.78, indicating a reasonably medium level of classification performance.

Overall, the results thus far indicate that the YOLOv8 model is a promising approach for pavement defect detection. However, further experimentation with a bigger training dataset and optimization are necessary to enhance the model's performance, particularly in terms of recall and reducing false positives.
