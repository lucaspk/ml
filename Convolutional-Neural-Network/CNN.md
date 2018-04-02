# Convolutional Neural Network (CNN)

CNN has three main concepts:
- **Convolutional Layers**
    - Apply convolution filters to the image;
    - Each application involves a **subregion**;
    - Select the size of the subregion (e.g. 2x2 window) and the **stride** (how many pixels to jump at each iteration - e.g. *stride = 2*);
    - After that, apply mathematical operations in each subregion to produce one value (**output**) and put it in the **feature map**. 
        - So, the feature map is constructed by repeated application of convolution with linear filter, adding bias term and then applying non-linear function to it (e.g. tanh).  
- **Pooling Layers**
- **Dense (fully-connected) Layers**