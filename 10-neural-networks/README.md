# Module 10: Neural Networks – Deep Learning Foundations and Practice

## Objective  
This module introduces neural networks and deep learning as the foundational models behind modern AI systems. It traces the progression from logistic regression to multilayer architectures capable of learning complex, hierarchical representations. Across three parts, it covers network architecture, training techniques, activation functions, and real-world applications including image classification, object detection, and transfer learning.

---

## Learning Outcomes  
- Understand the architecture and operation of deep neural networks  
- Rewrite linear and logistic regression as network structures  
- Identify and apply activation functions (ReLU, Sigmoid, Softmax)  
- Design networks with appropriate layer depth and width  
- Train models using TensorFlow and Keras in Google Colab  
- Choose appropriate loss functions (MSE, Cross-Entropy)  
- Apply gradient descent, early stopping, and dropout to avoid overfitting  
- Use convolutional neural networks (CNNs) for image data  
- Implement transfer learning with pre-trained models (e.g. ResNet)

---

## Techniques Covered  
- Feedforward neural networks (vanilla DNNs)  
- Hidden layers, weights, and biases  
- Nonlinear transformations using activation functions  
- Backpropagation and stochastic gradient descent  
- Regularization (dropout, early stopping)  
- Image preprocessing: grayscale, RGB, pixel normalization  
- CNNs: convolutional filters, pooling layers, feature maps  
- Transfer learning and feature reuse via pre-trained models  
- TensorFlow and Keras implementation workflows

---

## Tools Used  
- Python  
- TensorFlow  
- Keras  
- Google Colab  
- Fashion-MNIST Dataset  
- Matplotlib / Seaborn for training visualization  
- ResNet for transfer learning

---

## Personal Reflection

This was the first module that truly made me feel like I was stepping into the world of AI.

I had previously built logistic regression and tree-based models, but neural networks introduced an entirely new way of thinking — not just about models, but about **representation, abstraction, and transformation**. The key realization for me was this: with enough data and layers, a network can **learn to see what we can’t describe.**

In health and human behavior, many of the most important variables are **unstructured, nonlinear, and interdependent**. A client’s progress might depend on a subtle interaction between stress, social support, and physiology. Linear models can’t capture this — but deep learning can.

The architecture design component was also revealing. Choosing layer depth and activation functions felt less like textbook modeling and more like **engineering a system**. It reminded me that models are more than math — they’re decisions. Every neuron, activation, and connection reflects a bet on how data flows, and the right design helps unlock complexity instead of obscuring it.

The image classification segment tied it all together. Training a CNN on the Fashion-MNIST dataset felt like a rite of passage. When I used transfer learning with ResNet and saw accuracy improve with less data, I realized this wasn’t just technical training — it was **practical AI engineering**. I now understand the power and responsibility that comes with using these models in real-world contexts.

---

## Example Case Studies  
- **Neural Network from Scratch (Structured Data)**  
  Transformed logistic regression into a network structure. Used ReLU in hidden layers and Sigmoid in output to predict binary outcomes.

- **Fashion-MNIST Image Classification (CNN)**  
  Built a convolutional neural network to classify grayscale clothing images. Achieved >90% accuracy using convolutional, pooling, and fully connected layers.

- **Transfer Learning with ResNet**  
  Replaced output layer of ResNet with a custom classification head. Used features from millions of prior training images to build a robust classifier with limited data.

---

## Key Takeaways  
- Deep neural networks extend linear models through layered nonlinear transformations  
- Hierarchical representation learning enables abstraction from raw data  
- CNNs are foundational to image recognition and many AI applications  
- Regularization techniques like dropout and early stopping are essential to avoid overfitting  
- Transfer learning allows small teams to leverage massive models for meaningful use cases  
- Building AI systems requires both technical rigor and ethical awareness

---

## Notebook: `neural_networks_deep_learning.ipynb` *(coming soon)*
