---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# For courses with a single offering in the _config.yml,
# uncomment the following line and comment out the course-multi line

#layout: course-single
layout: course-multi
---

<!-- # <a name="description">Overview</a>

{{ site.description }} -->

## <a name="goals">Course Description</a>

* This is a Special Topics course focusing on the foundations of computer vision and machine learning/ deep learning methods for computer vision tasks. The students are expected to have obtained a solid
background in machine learning, linear algebra, and coding skills.
* This course is a combination of lectures and student presentations. We plan to read and discuss recent research papers on the intersection between computer vision and machine learning. We plan to invite internal (within the department) and external speakers to give guest lectures to give introductory and state-of-the-art developments in the area of computer vision and machine learning.
* This course satisfies the ECE graduate program requirement.

{% include resources.html content=site.goals %}

## <a name="resources">Contacts</a>
* Instructor: Dr. Xiaoxiao Li (xiaoxiao.li@ece.ubc.ca)
* TA: Chun-Yin Huang (chunyinhuang17@gmail.com)
* TA: Sana Ayromlou (ayromlous@gmail.com)

{% include resources.html content=site.resources %}

## <a name="additional-resources">Time and Location</a>

* Location:
Tue/Thu ∥ 11:00 am – 12:30 pm ∥ Neville Scarfe∥ Rm 1004
* Zoom participation ID:
[https://ubc.zoom.us/j/65807504716?pwd=RnV0Z2dHR1NCMkcwcnVYVmluZ2RRdz09](https://pythonintro-yorgey.notebooks.azure.com/j/notebooks/PythonIntro.ipynb)
* TA Office Hours: TBA
* Instructor Office Hours: Thursday afternoon (by appointment only)

{% include resources.html content=site.extra-resources %}

## Computational Resources

GPU computing is required for this class. I strongly recommend to Google Colab or use your
own/lab’s GPU since that is the most convenient way of writing and testing code with GUI. [Click
here](https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb) to try out the Colab tutorial. You can also consider using other computational resources
offered by UBC.

<hr>

# <a name="inclasscode">In-Class Code</a>

When we write code together in class, it will be posted here!

| Date | Topic | Code |
|:----:|------||-----||
| F 30 Aug | Intro to Python | [Intro Notebook](https://pythonintro-yorgey.notebooks.azure.com/j/notebooks/PythonIntro.ipynb) |
| W 4 Sep | More Math and Functions | [Box Math](https://boxmath-yorgey.notebooks.azure.com/j/notebooks/BoxMath.ipynb) |
| F 6 Sep | Strings and Booleans | [Booleans](https://booleans-yorgey.notebooks.azure.com/j/notebooks/Strings%20and%20Booleans.ipynb)

<hr>
# Coursework

Each student has **four late days** to spend throughout the semester as they wish.
Simply inform the instructor any time *prior* to the due date for an assignment
that you wish to use a late day; you may then turn in the assignment up to 24
hours late. Multiple late days may be used on the same assignment. There are no
partial late days; turning in an assignment 2 hours late or 20 hours late will
both use 1 late day. Note that late days are intended to cover both normal
circumstances (you simply want more time to work on the assignment) and
exceptional circumstances (you get sick, travel for a game or family
obligation, *etc.*). After you have used up your late days, late assignments
will receive at most half credit.

## <a name="hwqz">Homework and Quizzes</a>: 140 points

| #  | Name | Assigned | Due |
|:--:|-----||:--------:|:---:|
|0 | [Info Sheet](https://docs.google.com/forms/d/e/1FAIpQLSdtxgmw2tL6IzzK0qq3Fw2h2FTFmGHoTRs8p6wTfTToUn7pZg/viewform?usp=sf_link) | W Aug 28 | F Aug 30 |
|1 | [Sample Homework]({{site.baseurl}}/homework/function-reading.pdf) | F Sep 27 | W Oct 2 |
|2 | [Sample Homework]({{site.baseurl}}/homework/function-reading.pdf) | F Sep 27 | W Oct 2 |
|3 | [Sample Homework]({{site.baseurl}}/homework/function-reading.pdf) | F Sep 27 | W Oct 2 |

There will often be short homework assignments to be completed over the weekend, assigned on Friday and due Wednesday, sometimes with a corresponding quiz at the beginning of class on Wednesday.

## <a name="labs">Labs</a>: 260 points

| #  | Name | Assigned | Due |
|:--:|-----||:--------:|:---:|
|1 | [Sample Lab]({{site.baseurl}}/labs/sample-lab.html) | Aug 28-29 | Sep 4-5 |
|2 | [Sample Lab]({{site.baseurl}}/labs/sample-lab.html) | Sep 4-5 | Sep 11-12 |
|3 | [Sample Lab]({{site.baseurl}}/labs/sample-lab.html) | Sep 11-12 | Sep 18-19 |

Much of your experience with programming in this course will be through weekly labs. Each lab will be assigned in lab with time allotted to work through the materials, and will be due **by the start of the following lab**. All labs are weighted equally within the lab portion of your final grade.

On these labs, you will work with a partner on the lab assignments. Their name must be listed on any code you hand in as joint work. A partnership should only turn in a **single copy** of the assignment. If students working as partners wish to turn in a lab late, both students must use a late day.

**Lab attendance is required**. Labs take place in the **Snoddy Computer Lab**, in the Bailey Library. As you go through the exterior door of the library, turn immediately to your left and enter the Snoddy Academic Resource Center. Continue through the door at the far end of the hall into the first computer lab, and then enter the second lab at the back.

## <a name="projects">Projects</a>: 350 points

| #  | Name | Points | Assigned | Due |
|:--:|-----||:------:|:--------:|:---:|
|1 | [Sample Project]({{site.baseurl}}/projects/sample-project.html)  | 50  | Sep 21 | Sep 30 |
|2 | [Sample Project]({{site.baseurl}}/projects/sample-project.html) | 100 | Oct 16 | Nov 1 |
|3 | [Sample Project]({{site.baseurl}}/projects/sample-project.html) | 200 | Nov 18 | Final Exam Day |

You will have three projects in this course, one about every five weeks. These projects will cover concepts we have discussed in class and in labs, and will be due approximately one week after they are assigned.

**You must work individually on the first two projects.** You may discuss concepts and ideas with your classmates, but the code you turn in must be your own. You will be graded not only on correctness, but also technique, documentation and evaluation of your solution. Further details on the grading standards and handin instructions for each project will be given when they are assigned.

## <a name="exams">Exams</a>: 250 points

There will be three in-class exams, the first worth 50 points and the second and
third worth 100 of your final grade. They will consist of short answer
questions along with writing and debugging code.

* Exam 1: Sep 20, covering functions, math, numerical data, conditionals, and binary encoding
* Exam 2: Oct 16, covering input/output, while loops, lists, and strings
* Exam 3: Nov 25, covering for loops, dictionaries, classes and objects

There is no final exam; you will complete a final project instead, as described above under Projects.

## <a name="scale">Grading Scale</a>

| Score  | Grade  |
|:------:|:------:|
| 900-1000  | A   |
| 800-899   | B   |
| 700-799   | C   |
| 600-699   | D   |
| 0-599     | F   |
