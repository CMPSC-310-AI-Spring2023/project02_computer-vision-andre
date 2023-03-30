# Report by Andre

## Project Selection [DUE: February 24th]

: 
Identify your application. Describe what type of object detection/identification/etc. you plan to pursue and address its feasibility (for example, is there labeled data, appropriate supervised learning algorithms to be applied).

Also, include instructions on how to run your application.

For my project, I found a data set of NFL images on kaggle and will be using this to determines/predict biases in the photos which would reflect biases in the games. The application is just a google collab notebook, and can just be run by pressing the run arrow on each code block.

## Learning Agent

Describe the methodology used for your learning agent (algorithms, the goals of learning, inputs, outputs, etc.)

The algorithm behind this project takes in the dataset of images, and returns modified images that highlight the key aspects of the image that are used for the project. These aspects are elements such as the hash marks, the yard numbers and the yard lines. The algorithm uses the OpenCV library and matplotlib. The algorithm goes through each shape in the image, and labels each shape. Then for each shape it checks the label name and if it matches a specific value, an annotation is added. it then displays the new image with the imshow() function which now has all the new shapes on top of the old image over the key elements.

## Experimental Analysis

:
Describe the performance metrics for different environment settings (different images or positions of the camera). Also, discuss the accuracy of the performance of the algorithm for your application.

After running the program on different images, it seems that it is very accurate in correctly identifying the key elements on the football field. On an endzone and sideline view it was able to correctly id lal the elements and not mistakenly id any extra elements.

## Ethical Benefits and Implications

:
In this section, drawing on the civic issue you aimed to highlight or address, answer the following questions:

1. What entities, businesses, organizations do you envision developing the type of the application you have chosen to develop?

Im sure the following already have some iteration of this, but news channels that broadcast the games as well as the nfl and other analyst companies. 

2. Who are the intended users of this technology?

Sports analysts that want to get more data on the game and field positioning of a specific game.

3. Who is not supposed to use this technology?

No one is really not supposed to use this tech, however it may be obsolete or useless to people not interest in football.

4. How can the application developed in this project cause harm? How?

I'm not sure as all its doing is highlighting key elements on a football field and not interacting with any elements such as players. If it was analyzing players it may have potential to cause harm to individuals.

5. What solutions could be implemented to avoid the harm or to fix the harm described above?

Making sure that the program stays focused o analyzing the field, and not players would be the easiest way to continue avoiding harm.

## Challenges and Learning Experiences

:
Discuss any challenges you have encountered during the work on this lab and  describe what have you learned. 

While working on the lab and tutorial code, i was able ot implement some addition code in the first section to analyze more images, however in the second part where it is attempting to perform further analysis on the images I ran into some issues. Specifically the tutorial was using a method of approach that required CUDA cores to perform analysis and that was unable to be run on google collab.

## Team Work

:
Describe the details of your team working strategy, specifically explain how did you complete this work as a team and describe the specific contributions of each team member.

Single team member.
