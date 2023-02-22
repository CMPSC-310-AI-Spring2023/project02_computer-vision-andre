# Project 2: Computer Vision Application

## Deadlines:

- _Project Idea Exploration_: February 24th by 9:30am
- _Mid-Project Check-in_: March 1 by 2:30-4:20pm
- _Code and Report_: March 15th by 4:30pm
- _Project Presentation and Demonstration_: March 15th 2:30-4:20pm

## Table of Contents

- [Summary](#summary)
- [Objectives](#objectives)
- [Code of Conduct](#code-of-conduct)
- [Learning](#learning)
- [Assignment Specification](#assignment-specification)

  - [Baseline Requirements](#baseline-requirements)
  - [Steps to Project Completion](#steps-to-project-completion)

- [Planning](#planning)

- [Mid-Project Check-In](#mid-project-check-in)

- [Project presentation](#project-presentation)

- [Required Deliverables](#required-deliverables)

- [Assignment Assessment](#assignment-assessment)

- [GatorGrade](#gatorgrade)

- [Receiving Assistance](receiving-assistance)

## Summary

This laboratory assignment invites you to work individually or in a team of two (or three at the maximum) to implement a learning agent for computer vision application of your choice, for example a specific object detection or object recognition. Your developed application should interrogate issues of bias, fairness, or privacy, or a similar issue impacting society. You are also responsible for writing a detailed report, stored in the file `writing/report.md`. This is a Markdown file that must adhere to the standards described in the [Markdown Syntax Guide](https://guides.github.com/features/mastering-markdown/).

## Objectives

- To interrogate issues of bias, fairness, and privacy in computer vision applications.
- To learn how to use a computer vision OpenCV software and the machine learning library `scikit-learn` for computer vision applications.
- To correctly apply image pre-processing (for example, smoothing, blurring, thresholding, edge detection) to images using OpenCV functions.
- To gain understanding of image processing techniques that can be used for specific computer vision applications.
- To apply a computer vision technique using supervised learning algorithm to a problem in object detection.
- To evaluate the performance of the developed system under various environmental conditions and to reflect on its design and development.

## Code of Conduct

Throughout the completion of this project you must adhere to the [community guidelines](https://github.com/CMPSC-310-AI-Spring2023/course_information/blob/main/community_guidelines.md) that we developed as a class. In addition to reporting any violations of the code of conduct using [this form](https://forms.gle/W6Kf2jt1DmmKEdAs6), please make sure that you attest to the fact that you followed the code of conduct. Students who think that the class should revise some aspect of the guidelines must use the GitHub issue tracker for that repository to suggest, discuss, and implement any required changes.

## Learning

To review what you have learned about learning, `scikit-learn` and OpenCV, please read the supplemental chapter given in the lab repository and sections 7.1--7.3 from the [Artificial Intelligence: Foundations of Computational Agents](https://artint.info/2e/html/ArtInt2e.Ch1.html) textbook.

If you have not done so already, please read all of the relevant [GitHub Guides](https://guides.github.com/) that explain how to use many of the features that GitHub provides.

## Assignment Specification

In this two-week lab students are invited to implement a learning agent using an open-source learning platforms, `scikit-learn` and OpenCV, for a computer vision classification application of your choosing that highlights or solves issues of fairness, bias, privacy, etc. You must work with images, recorded videos, or a live video feed. As you select a specific application, you must first decide what type of object your agent will try to learn to identify by applying a classification algorithm and what environment it will operate in. Then, you need to select an algorithm to perform the classification and evaluate its effectiveness. You can utilize class programs, existing open source projects, and `scikit-learn` and OpenCV documentation for usage examples of various methods. You are also free to select an algorithm not discussed in class with the approval of the instructor.

### Baseline Requirements

- Your project must shine a light on or solves a specific issue related to fairness, bias, privacy, or similar.
- Your project must be implemented in Python. 
- Your implementation should perform some pre-processing on images or videos and then apply a learning algorithm to perform a specific task.
- You must use OpenCV and `scikit-learn` library.
- While your project can be and should be based on an existing project, it should NOT be just a copy of an existing project (for example, a class program or an online tutorial).
- You must include references to all resources used in your report as links to online resources or by specifying activity number or reading resource if using class resources.
- You must include and specify all the steps needed to successfully run your program(s) in your report. This include installation instructions if you prefer to run your tool outside of Colab.
- You must produce a visual product that demonstrates the results of your application (video, live demo, etc.).
- You must engage in mid-project check-in and participate in the presentation.

### Steps to Project Completion

1. Select an application for computer vision classification. What type of an object would you like to detect/recognize/work with? What civic issue does it help us interrogate (bias, privacy, etc.)? Are the pre-trained samples for this object available? You can consult resources such as [kaggle](https://www.kaggle.com/datasets) and [opencv cascades](https://github.com/opencv/opencv/tree/master/data).

2. Select a supervised learning algorithm for object detection, a classifier, that uses certain features of the image to correctly label them as a specific object or not. You need to select a learning algorithm that you will utilize (e.g., SVM, Random Forest, etc.) and possibly a feature descriptor that your algorithm will use (e.g., Haar, HOG, LBP). You should use supervised learning algorithms that are available in OpenCV and/or `scikit-learn` library. Make sure the classifier you select has already been trained using specific data sets and a certain feature descriptor in OpenCV or select a feature descriptor that already has compiled labeled data set that can be used for training.

3. Perform any necessary image pre-processing, and implement your learning algorithm.

4. Conduct an experimental analysis. After you have conducted preliminary tests to ensure your program(s) run without errors and you are satisfied with your detection accuracy, you need to conduct environment comparison experiments. Specifically, we are interested in learning the performance of object detection/recognition for different images or camera positions.

## Planning

Please take a couple of days to research and decide on your specific application. Make sure you have thought about steps 1 and 2 above before you commit to a project idea. By class time on Friday, February 24th, you must have a clearly defined project description, including the type of data and algorithms you will attempt to use. If your project requires any hardware, you must specify this as well by that date.

## Mid-Project Check-In

During the lab session on March 1st, the instructor and the TL will invite each team to provide an oral progress update. By this point, you should have:

- collected your data,
- conducted some image pre-processing as needed,
- selected learning algorithm,
- at the minimum, began implementation of the algorithm with clear understanding of its functionality.

## Project Presentation

At the beginning of the lab session on Wednesday, March 1st, each team will be given an opportunity to present their project. The presentation should have an accampanying visual product to demonstrate your project (be creative!). Teams can use slides if desired to aid in presentation. Each presentation should provide:

- an overview of the chosen application,
- civic problem interrogated by the chosen application,
- data and pre-processing steps,
- learning algorithm,
- experiments and results.

All team members should be a part of the presentation.

## Required Deliverables

This assignment invites you to submit the following deliverables through your team repository.

1. Planning portion of the report due on February 2th by 9:30am. The rest of the written requirements are due at 2:30 pm on March 15th.
2. A properly completed and commented source program(s). If Colab is used, make sure the notebook is committed to your repository.
3. The report, stored in /writing/report.md and written in Markdown, that contains the planning portion as described above, and provides answers in all remaining sections (follow the prompts inside the report document).
4. Lab session on March 1st will be used for lab work.
5. The lab session on March 15th will be used for presentations.

## Assignment Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 10%]:**: For lab02 repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements. A reduction maybe given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. All other requirements are evaluated manually.

- **Mastery of Verbal Explanation during Check-in and Presentation [up to 20%]:**: Since the timely project development and the ability to communicate technical details of a project is crucial to building successful applications, a portion of students' lab grade will be determined based on the quality of the project explanation and presentation.

- **Mastery of Technical Writing [up to 10%]:**: Students will also receive a checkmark grade when the responses to the writing questions presented in the `report.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

- **Mastery of Technical Knowledge and Skills [up to 60%]**: Students will receive the largest portion of their assignment grade when their project implementation reveals that they have mastered all of the technical knowledge and skills developed during the completion of this project. As a part of this grade, the instructor will assess aspects of the project including, but not limited to, the completeness and the correctness of the program(s), the use of effective source code comments and Git commit messages, the effective experimental analysis.

All grades for this project will be reported through a student's gradebook GitHub repository and the feedback pull request in this repository if necessary.

## GatorGrade

You can check the baseline requirements of this project by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python installed. If not, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Receiving Assistance

If you are having trouble completing any part of this project, then please talk with either the course instructor during the lab session. Alternatively, you may ask questions in the Slack workspace for this course. Finally, you can schedule a meeting during the course instructor's office hours.
