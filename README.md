# Medical Image Analysis course (8DC00)
This course is a sequel to the second year introductory image analysis course. In that course the basic principles of image analysis were covered. In 8DC00 we will concentrate on the more advanced image analysis methods and on how they can be used to tackle clinical problems. Topics covered include image registration and computer-aided diagnosis (CAD).

## Learning outcomes
After passing this course, the student is able to:
1.	explain the fundamental principles behind point- and intensity-based image registration.
2.	compose (homogeneous) 2D transformation matrices and identify the required transformation model, image similarity measure and optimization method, given an example of a medical image registration problem.
3.	explain the fundamental principles behind machine learning for medical image analysis tasks (classification & regression), including the k-Nearest neighbors algorithm and linear and logistic regression.
4.	recall the different building blocks of (convolutional) neural networks and explain how supervised and unsupervised machine learning techniques can be applied to medical image analysis problems.
5.	design medical image analysis methods using basic engineering and mathematical techniques such as optimization, and implement these techniques in Python.
6.	analyze the performance of the medical image analysis methods using appropriate validation metrics and interpret the results in a scientific report.

## Use of Canvas
This GitHub page contains information about the course and the study material. The Canvas page of the course will be used only for sharing course information that cannot be made public, quizzes, submission of the practical work and posting questions to the instructors and teaching assistants (in the Discussion section). Students are highly encouraged to use the Discussion section in Canvas for general questions (e.g., issues with programming environment, methodology questions).

TLDR: GitHub is for content, Canvas for communication and submission of assignments.

## Schedule
The 2024 edition of the course will be given on campus. The lectures will not be recorded to encourage on-campus participation.

The schedule is as follows:

* **Lectures**: Tuesdays 08:45 – 10:45 & Fridays 13:30 – 15:30
* **Guided self-study**: Tuesdays 10:45 - 12:45 & Fridays 15:30 - 17:30

The course schedule is summarized below:

| Week | Day | Date   | Time        | Activity                                 | Module              | Lecturer         | Topic                                                                                                        |
| ---- | --- | ------ | ----------- | ---------------------------------------- | ------------------- | ---------------- | ------------------------------------------------------------------------------------------------------------ |
| 1    | Tue | 03/Sep | 08:45-10:45 | Lecture                                  | Registration        | R. Su | Course introduction; introduction image registration; Geometrical transformations                            |
|      | Tue | 03/Sep | 10:45-12:45 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      | Fri | 06/Sep | 13:30-15:30 | Lecture                                  | Registration        | R. Su | Point-based registration                                                                                     |
|      | Fri | 06/Sep | 15:30-17:30 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 2    | Tue | 10/Sep | 08:45-10:45 | Lecture                                  | Registration        | R. Su | Intensity-based registration                                                                                 |
|      | Tue | 10/Sep | 10:45-12:45 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      | Fri | 13/Sep | 13:30-15:30 | Lecture                                  | Registration        | R. Su | Validation; Active shape models                                                                              |
|      | Fri | 13/Sep | 15:30-17:30 | Guided selfstudy                         | Registration        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 3    | Tue | 17/Sep | 08:45-10:45 | Lecture                                  | CAD        | C. Scannell          | Introduction CAD and machine learning 1                                                                                           |
|      | Tue | 17/Sep | 10:45-12:45 | Guided selfstudy                         | Registration        |                  |                                                                                                                                                                                     |
|      | Fri | 20/Sep | 13:30-15:30 | Lecture                                  | CAD                 | C. Scannell      | Linear regression                                                                                             |
|      | Fri | 20/Sep | 15:30-17:30 | Guided selfstudy                         | CAD        |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 4    | Tue | 24/Sep | 08:45-10:45 | Lecture                                  | CAD                 | C. Scannell      | Logistic regression and neural networks                                                                                               |
|      | Tue | 24/Sep | 10:45-12:45 | Guided selfstudy                         | CAD                 |                  |                                                                                                              |
|      | Fri | 27/Sep |     | NO LECTURE   (MomenTUm)                               |                  |       |                                                                      |
|      | Fri | 27/Sep |  | NO LECTURE  (MomenTUm)                      |                |                  |  | 
|      |     |        |             |                                          |                     |                  |                                                                                                              |
|   5    | Mon | 30/Sep | 23:59       | DEADLINE Report project 1 (registration) |                     | |      |
|    | Tue | 01/Oct | 08:45-10:45 | Lecture                                  | CAD                 | C. Scannell      | Convolutional neural networks                                                           
|      | Tue | 01/Oct | 10:45-12:45 | Guided selfstudy                         | CAD                 |                  |                                                                                                              |
|      | Fri | 04/Oct | 13:30-15:30 | Lecture                                  | CAD                 | C. Scannell      |  Deep learning frameworks and applications                                                                               |
|      | Fri | 04/Oct | 15:30-17:30 | Guided selfstudy                         | CAD                 |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 6    | Tue | 08/Oct | 08:45-10:45| Catch up day (NO LECTURE)                |                     | -                |                                                                    |
|      | Tue | 08/Oct | 10:45-12:45 | Guided selfstudy                         | CAD                 |                  |                                                                                                              |
|      | Fri | 11/Oct | 13:30-15:30 | Catch up day (NO LECTURE)               | CAD                 | -    |                                                                          |
|      | Fri | 11/Oct | 15:30-17:30 | Guided selfstudy                         | CAD                 |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 7    | Tue | 15/Oct | 08:45-10:45 | Lecture                                  | CAD                 |    C. Scannell              | Unsupervised machine learning                                                                                             |
|      | Tue | 15/Oct | 10:45-12:45 | Guided selfstudy                         |                     |                  |                                                                                                              |
|      | Fri | 18/Oct | 13:30-15:30 | Lecture                                  | Registration/CAD |        R. Su          | Deep Learning for Image Registration |
|      | Fri | 18/Oct | 15:30-17:30 | Guided selfstudy                         |                     |                  |                                                                                                              |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
| 8   | Tue | 22/Oct | 08:45-10:45 | Lecture                                  | Registration/CAD                 | C. Scannell  & R. Su     | Questions & preparing for the exam                                                                                                |
|     | Tue | 22/Oct | 23:59       | DEADLINE Report project 2 (CAD)          |                     |                  |
|      |     |        |             |                                          |                     |                  |                                                                                                              |
|      | ? | ?  | ?   | WRITTEN EXAM                             |                     |                  |                                                                                                              |

## Materials
Primary study materials are the **lecture slides** (will be added to GitHub soon) and the [**Jupyter Notebooks**](https://github.com/tueimage/8dc00-mia/tree/master/reader) containing theory, practical exercises and questions. An easy way to access the theory in these Notebooks, e.g. to study for the exam, is the [**virtual reader**](https://8dc00-mia-docs.readthedocs.io/en/latest/index.html). In addition, you can study the relevant sections from the following **books**:

* Fitzpatrick, J.M., Hill, D.L. and Maurer Jr, C.R., [Image registration](https://citeseerx.ist.psu.edu/pdf/929f5e30e0d02d9e72b7933ab88cdd0def9b4323).
* Kolter, Z. Do, C., [Linear Algebra Review and Reference](http://cs229.stanford.edu/section/cs229-linalg.pdf)
* Toennies, Klaus D., [Guide to Medical Image Analysis - Methods and Algorithms](https://www.springer.com/gp/book/9781447173182)

## Lectures handouts and connection with notebooks
Please find below an overview of the lecture handhouts, the contents discussed, and the corresponding notebook(s).

| Lecture handouts (PDF) | Filename                                                        | Contents                                                                                                                   | Notebook(s)                                |
| ---------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| 1a                      | Course introduction                                             | Practical information about the course                                                                                     | 0.1                                        |
| 1b                      | Introduction to image registration; Geometrical transformations | Review of linear algebra; Introduction to image registration; Geometrical transformations                                  | 1.1                                        |
| 2                      | Point-based registration                                        | Point-based registration (theory); Optimization; Evaluation of registration accuracy                                       | 1.2                                        |
| 3                      | Intensity-based registration                                    | Probability theory; Intensity-based similarity metrics; Optimization; Gradient descent; Intensity-based image registration | Spread over three notebooks: 1.3, 1.4, 1.5 |
| 4                      | Validation; Active shape models                                 | Validation in medical image analysis; Active shape models                                                                  | 1.5; Notebook on Active Shape Models       |
| 5                      | Computer-aided diagnosis                                        | Introduction into computer-aided diagnosis & machine learning                                                              | 2.1, partially 2.3                         |
| 6                      | Linear regression                                               | Linear regression as the most basic building block of deep neural networks; generalization and overfitting                 | 2.1, partially 2.3                         |
| 7                      | Logistic regression and neural networks                         | Logistic regression; extension of neural network definition; k-NN algorithm                                                | 2.2, partially 2.3                         |
| 8                      | Convolutional neural networks                                   | Building blocks of neural networks                                                                                         | 2.3                                        |
| 9                     | Deep learning frameworks and applications                       | Examples of neural networks / deep learning frameworks with applications                                                   | 2.3                                        |
| 10                     | Unsupervised machine learning                                   | Supervised vs. unsupervised learning; K-means; PCA; autoencoder                                                            | 2.4                                        |
| 11                     | Deep learning for image registration                            | Additional course material on using deep learning for (deformable) image registration                                      | Partially in 2.4                           |

# Practical work (exercises and project work)
During the practical sessions the students can work on practical exercises and the project (however, it is expected that students will also work on the project in their own time). The goal of the practical exercises is to help study and understand the material, and develop code and methods that can be used to complete the project work. Your are expected to do this work independently with the help of the teaching assistants during the guided self-study sessions (begeleide zelfstudie). You can also post your questions in the Discussion section in Canvas at any time.

NB: Sign yourself up for a project group in Canvas->people->groups.

## Software

**IMPORTANT: It is essential that you correctly set up the Python working environment by the end of the first week of the course so there are no delays in the work on the practicals.**

To get started, carefully follow the instructions [here](https://8dc00-mia-docs.readthedocs.io/en/latest/reader/0.1_Software_guide.html).

## Python quiz

**IMPORTANT: Attempting the quiz before the specified deadline is mandatory.**

In the first week of the course you have to do a Python self-assessment quiz in Canvas. The quiz will not be graded. If you fail to complete the quiz before the deadline, you will not get a grade for the course. The goal of the quiz is to give you an idea of the Python programming level that is expected.

If you lack prior knowledge of the Python programming language, you can use the material in the "Python essentials" and "Numerical and scientific computing in Python" modules available [here](https://github.com/tueimage/essential-skills/).

## Projects
During this course you will work on two projects: [project 1 (image registration)](https://github.com/tueimage/8dc00-mia/blob/master/reader/1.6_Registration_project.ipynb) and [project 2 (CAD)](https://github.com/tueimage/8dc00-mia/blob/master/reader/2.5_CAD_project.ipynb). The projects are done in groups of up to 4 students. The groups will be formed in Canvas and you will also submit all your work there (check the Assignments section for the deadlines). 


## Assessment
The assessment will be performed in the following way:
* Project work: 30% of the grade (both projects have equal contribution)
* Written exam (open answer and multiple-choice questions): 70% of the grade

To pass the course the written exam grade needs to be > 5.0 and the final grade needs to be > 5.5.

Grading of the assignments will be done per group, however, it is possible that individual students get a separate grade from the rest of the group (e.g. if they did not sufficiently participate in the work of the group). More info on the assessment criteria can be found [here](rubric.md).

## Lecturers and teaching assistants
Course instructors:
* dr. Cian Scannell (Assistant Professor)
* dr. Ruisheng Su (Assistant Professor)

Teaching assistants:
* Rebecca Pelsser
* Mike Albertz
* Sarah de Ruiter
* Jasper Bongers
* Marijn de Lange



The main communication with the teachers will be via Canvas and regularly scheduled office hours. We recommend the Discussion section in Canvas as the primary communication channel as this is visible for all students and teachers. Please note that the frequency of the office hours will not increase close to deadlines and the exam, so if you have any questions please come well on time.
