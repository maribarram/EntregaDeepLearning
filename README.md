# EntregaDeepLearning

En este repositorio se implementa un modelo de Deep Learning, utilizando la red ResNet50 bia transferlearning para poder crear un modelo el cual sea capaz de predecir el autor de la obra, tomado como entrada la pintura. 

El dataset se tomo del siguiente link: https://www.kaggle.com/datasets/ikarus777/best-artworks-of-all-time

Video del modelo en entrenamiento: https://drive.google.com/drive/folders/1AAmLlz4PXABXriYjjc_AXHa9ILW5ELBR?usp=sharing

| Modelo      | Arquitectura | Accuracy | Accuracy Val
| ----------- | -----------  | -------- | ------------
| Modelo      | Resnet, Flatten, Dense(3,softmax)| 96% | 90%
| Modelo1     | Resnet, Flatten, Dense(256,relu), Dense(3,softmax)|98%|94%
| Modelo2 (4 categorias)| Resnet, Flatten, Dense(256,relu), Dense(4,softmax)|96%|83%
| Modelo3 (4 categorias)| Resnet, Flatten, Dense(256,relu), Dropout(0.5),Dense(4,softmax)|96%|83%
