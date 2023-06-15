# Coding-3-Final-Project

PS: I can't add all the files to GitHub because the folder is too big, the code is in the cat folder above, you can download and view the rest of the content via the link below.

I have referred to week 5 as the basis for my final assignment and the following are links to the content I have referred to: https://git.arts.ac.uk/rfiebrink/ExploringMachineIntelligence_Spring2023/blob/main/week5/dcgan.ipynb 

This is a link to the dataset I referenced and you can download the relevant images here: https://www.kaggle.com/datasets/yapwh1208/cats-breed-dataset  (After downloading you will need to delete the html files in the folder and then import the remaining images into the cat_v1 folder in the data folder of the Cat folder)

You can also download all the images I have used directly via the Dropbox link at ：https://www.dropbox.com/scl/fo/5nhh0ie4gsl2ya82dyw7j/h?dl=0&rlkey=slyep5hr81d81lxh4qua96p0g  

My runs with Jupyter are placed in the following folders: https://www.dropbox.com/scl/fo/r0b0r6gl6511jn5llkekw/h?dl=0&rlkey=ot9iljmqizti72iwz1zub0dxg  

Video link: https://youtu.be/IlopEVxszsA

1. Creative concept
Domesticated cats are popular companion animals in many households as pets under human care. It is estimated that the number of stray cats worldwide may be in the hundreds of millions, which far exceeds the number of domesticated cats. Compared to stray cats, domesticated cats are not only kept, cared for and provided shelter by humans, but they have their own names, healthy food, water and medical care, and are well cared for and given records by humans. Whereas stray cats they not only don't have a name, but also have to go through hunger, cold and various dangers every day, so I wanted to collect photos of stray cats through machine learning, not only to leave some trace of their life in this world, but also to increase people's attention to the problem of stray cats and to help convey their plight.

2. Project description
For this project I implemented a GAN-based image generation model using the TensorFlow and Keras libraries, which consists of two main components: a generator and a discriminator. The generator is responsible for generating generic image samples, while the discriminator is responsible for distinguishing the generated images from the real ones. Through adversarial training, the generator and discriminator compete and collaborate with each other to gradually improve the quality of the generated images.

3. Why machine learning is used
Machine learning is used to collect photos of stray cats because: 1. Machine learning algorithms can be written to automate the collection of stray cat photos, which can greatly reduce manual labour and improve the data collection process. 2. Machine learning can help collect a large number of stray cat photos quickly. Through automation and large-scale data collection, a more comprehensive and diverse sample of photos can be obtained to better represent the stray cat population. 3. Machine learning algorithms can automatically detect and validate photos of stray cats through image processing and analysis techniques. 4. By using machine learning techniques, you can create an attractive platform or application that displays photos of stray cats and provides information about information on stray cat issues.

4. Demonstration of operational results:
This is a photo from the 5,000 training sessions
![Image text](https://github.com/JasonGao818/Coding-3-Final-Project/blob/main/Coding3%20Final%20Project/1.jpg)
Because it was too vague, I increased the number of training sessions and here are the results when I trained 10,000 times.

![Image text](https://github.com/JasonGao818/Coding-3-Final-Project/blob/main/Coding3%20Final%20Project/2.png)
