# Celebrity Detection with AI

> Made by Molten Cores ヽ( ´ ∇ ｀ )ノ


During our time in AI Camp, we learned a lot of things. We learned a lot of things during this camp such as the basics of python, ai topics such as CNN, neural networks, interperting graphs/data, neurons and designing a website using html, css, bootstrap and flask. By the end of the three weeks we created our own website with our Celebrity Detection with AI on it. 

# Overview of Our Celebrity Detection with AI Project
Have you ever gotten zero sleep because of the struggle of seeing a celebrity you recognize but not knowing their name? Well, fear no more! Our porject can detects celebrities through an image. However, there are way too many celebrities in the world so we decided to focus on a few celebrities first. Our model can detect the marvel superheros Spider man, Iron man, Falcoln, Dr. Strange, Wanda Maximoff and Evelyn. 

![Marvel](https://cdn.discordapp.com/attachments/756729454134296647/989544727756046397/B09B255F-034A-45C9-805F-BFDC8C603A4A_1_201_a.jpeg)


# Getting Our Dataset

We used [serpapi](https://serpapi.com) to quickly get images for our dataset. After the getting images, we uploaded our images to [roboflow](https://roboflow.com). Then, we checked to make sure the image was good for our dataset, labeled our images, and split them into a training set, validation set, and testing set. We were able to get a total of 968 images and 7 batches(Spider Man, Iron Man, Black Panther, Dr. Strange, Falcoln, Wanda Maximoff and Evelyn). 

# Training and Testing Our Model
Before exporting our dataset from roboflow, we added some augmentations such as blurr, flip, rotate, shear and saturation. We used yolov5 to train our model using a batch of 4 and epoch of 12. After that was done, we used [wandb](https://wandb.ai/site) to visualize our training. 

# Results
Run #1: 
Run #2:
Run #3:
Run #4: 

# Conclusion

