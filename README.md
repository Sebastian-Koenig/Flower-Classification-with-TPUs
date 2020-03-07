# Flower-Classification-with-TPUs
Leveraging TPUs for Image Classification (Flowers).
Models used to date:    
1. VGG16 Transfer Learning
2. ResNet101V2 Transfer Learning
3. ResNet101V2 Full training
4. ResNet152V2 Full training with callbacks for learning rate decline and early stopping
5. DenseNet201 Full training with callbacks for learning rate decline and early stopping
6. DenseNet201 EfficientNet B7 ensamble. (Best Performance)
Point of note: While the Ensamble of DN201 and ENB7 has the best competition performance it would be ill suited to deployment in an apllication. Not only does the model require nearly twice the training time, it is also significantly slower in calculating the predictions.
