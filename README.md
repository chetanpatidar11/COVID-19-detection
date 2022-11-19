# COVID-19-detection
https://colab.research.google.com/drive/1NOe-oLRgqiLVA4xWe97Ijh78-EASrud2?usp=sharing
# What is the problem that we are handling?
The increasing frequency and magnitude of viral outbreaks in recent decades, by the current
COVID-19 pandemic, has resulted in an urgent need for rapid and sensitive viral diagnostic
methods. The symptoms of the disease can vary and include dyspnoea, high fever, runny
nose, and cough according to WHO. Instead of waiting for blood testing or RT-pcr which
takes approx. 5-6 hours to generate result. These cases can most commonly be diagnosed
using chest X-ray imaging analysis
# What is your approach to solve the problem?
Deep learning has shown a dramatic increase in the medical applications in general and
specifically in medical image-based diagnosis. Due to the very promising results provided by
CNNs in medical image analysis and classification, they are inspired by the visual system of
the human brain. The idea behind the CNNs is to make computers capable of viewing the
world as humans view it. This way CNNs can be used in the fields of image recognition and
analysis, image classification, and natural language processing.
# How do Convolutional neural networks work?
Convolutional neural networks are distinguished from other neural networks by their superior
performance with image, speech, or audio signal inputs. They have three main types of
layers, which are:
• Convolutional layer
• Pooling layer
• Fully-connected (FC) layer
# Convolutional layer
The convolutional layer is the core building block of a CNN, and it is where the majority of
computation occurs. It requires a few components, which are input data, a filter, and a feature
map. Let’s assume that the input will be a colour image, which is made up of a matrix of
pixels in 3D. This means that the input will have three dimensions—a height, width, and
depth—which correspond to RGB in an image. We also have a feature detector, also known
as a kernel or a filter, which will move across the receptive fields of the image, checking if
the feature is present. This process is known as a convolution.
# Pooling Layer:
Pooling layers, also known as down sampling, conducts dimensionality reduction, reducing
the number of parameters in the input.While a lot of information is lost in the pooling layer, it also has a number of benefits to the
CNN. They help to reduce complexity, improve efficiency, and limit risk of overfitting.
# Fully connected Layer:
The name of the full-connected layer aptly describes itself. As mentioned earlier, the pixel
values of the input image are not directly connected to the output layer in partially connected
layers. However, in the fully-connected layer, each node in the output layer connects directly
to a node in the previous layer.
