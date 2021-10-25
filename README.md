# MNIST-Digit-Recognizer

## Remember to use GPU, as this was done on GOOGLE COLAB so I activated gpu runtime!!

The MNIST dataset is a large database of handwritten digits. It commonly used for training various image processing systems. Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255 and labels are from 0-9 as shown:

![1](https://user-images.githubusercontent.com/77119829/138691919-5602cd82-ae05-4af0-a021-47ad8b5d9b29.PNG)

Then we scaled every pixel between 0-1 and then we applied the CNN to those training images by applying suitable parametrs which would increase our accuracy as shown:

![2](https://user-images.githubusercontent.com/77119829/138692253-e8f81973-e7f8-49f3-a530-b947fd5f3660.PNG)

After it we checked our accuracy and loss which were very impressive:


![3](https://user-images.githubusercontent.com/77119829/138692519-1e9027ff-0bc5-4989-a4e0-36346de44e81.PNG)

Then we try to analyze the output on our test images which was also very impressive as shown :

![4](https://user-images.githubusercontent.com/77119829/138692657-553018d9-b144-4293-a206-829ba6212d1a.PNG)
