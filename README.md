# Performance-Evaluation-of-Convolutional-Neural-Network-Using-Synthetic-Medical-Data-Augmentation-Gen
## Abstract
Data augmentation is widely used in image processing and pattern recognition problems in order to increase the richness in diversity of available data. It is commonly used to improve the classification accuracy of images when the available datasets are limited. Deep learning approaches have demonstrated an immense breakthrough in medical diagnostics over the last decade. A significant amount of datasets are needed for the effective training of deep neural networks. The appropriate use of data augmentation techniques prevents the model from over-fitting and thus increases the generalization capability of the network while testing afterward on unseen data. However, it remains a huge challenge to obtain such a large dataset from rare diseases in the medical field. This study presents the synthetic data augmentation technique using Generative Adversarial Networks to evaluate the generalization capability of neural networks using existing data more effectively. In this research, the convolutional neural network (CNN) model is used to classify the X-ray images of the human chest in both normal and pneumonia conditions; then, the synthetic images of the X-ray from the available dataset are generated by using the deep convolutional generative adversarial network (DCGAN) model. Finally, the CNN model is trained again with the original dataset and augmented data generated using the DCGAN model. The classification performance of the CNN model is improved by 3.2% when the augmented data were used along with the originally available dataset.![image](https://user-images.githubusercontent.com/115944321/196048615-ee19ae1d-5090-4122-a501-4ebdb7b524e5.png)

Paper published link: [https://www.worldscientific.com/doi/10.1142/S021946782350002X]
