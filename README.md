# Low Light Image Enhancement using Deep Learning
A deep learning model inspired by <a href="https://ieeexplore.ieee.org/document/8305143">LLCNN</a> proposed by Li Tao, Chuang Zhu, Guoqing Xiang, Yuan Li et. al. The model is pretty much the same as the one LLCNN authors proposed but I added attention mechanism using Squeeze-and-Excitation blocks. <i><b>No noticable improvements were found.</b></i>

My primary objective for this project was to apply practical deep learning and to learn the PyTorch framework. I had a great learning experience and also did an Udemy course parallelly to learn PyTorch. A fun project to say the least!

### Tech stack and frameworks/modules used:
- Python for scripting
- PyTorch for creating, training, testing of the Deep Learning model
- Numpy, CV2, PIL for data pre-processing
  
Huge thanks to <a href="https://github.com/Mr-TalhaIlyas/">Talha Ilyas</a> for his <a href="https://github.com/Mr-TalhaIlyas/EMPatches">EMPatches</a> Python module which made it easier for me to extract patches and stitching the resultant patches together

## The model in action on Set14 dataset's image:

The original image was synthetically darkened by applying a gamma value of 4 and was passed to the model. The output that the model gave is shown below as "enhanced"

![Demo Image](https://imgur.com/25khCMs.png)

- More test results and metrics can be found in the <a href="https://github.com/Rakeshkumar-7/image-enhancement-deep-learning/blob/main/Test_Model.ipynb">Test_Model</a> file. 
- To look at how the model was created, see <a href="https://github.com/Rakeshkumar-7/image-enhancement-deep-learning/blob/main/Research_Image_Enhancement.ipynb">this notebook</a>
- The data pre-processing methodology was borrowed from the LLCNN and LLNet papers
- All of the model was written and trained on Google Colab

Here's the flow diagram:

![Flow Diagram](https://imgur.com/SzMLASZ.png)

This was done as a project to my University course "CSE3043 - Video Analytics" in which we learn about images, videos, compression, enhancement, motion detection, textures, etc
