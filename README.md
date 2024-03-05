In this demo, we will get hands-on experiences on Sequential Models

We will be building and training a basic character-level RNN to classify words. The model receives a series of characters as input and returns a prediction of the next character together with the `hidden state` at each step. The `hidden step` will be fed onto the next step. At the end the model returns the category (language) a given word belongs to.

The dataset consists of surnames from 18 different languages and returns the language of a given surname. While pytorch has a set of NLP pre-processing functionalities lying on the library `torchtext`, this notebook builds from scratch all the desired functionallity.

![download](https://github.com/CPD9/Deep_learning_for_NLP/assets/66946145/505c8d4e-f085-4f0c-9b47-58bbdd4d5955)
