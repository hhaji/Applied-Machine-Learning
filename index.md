Lecturer: [Hossein Hajiabolhassan](http://facultymembers.sbu.ac.ir/hhaji/) <br>
[Data Science Center](http://ds.sbu.ac.ir), [Shahid Beheshti University](http://www.sbu.ac.ir/) <br>

---

### **Index:**
- [Course Overview](#Course-Overview)
- [Main TextBooks](#Main-TextBooks)
- [Slides and Papers](#Slides-and-Papers)
  1. Toolkit Lab: [Part 1](#Part-1) 
  2. Lecture 0: [Introduction](#Introduction)
  3. Lecture 1: [Empirical Risk Minimization](#Empirical-Risk-Minimization)
  4. Lecture 2: [PAC Learning](#PAC-Learning)
  5. Lecture 3: [The Bias-Complexity Tradeoff](#The-Bias-Complexity-Tradeoff)  
  6. Lecture 4: [The VC-Dimension](#The-VC-Dimension)
  7. Toolkit Lab: [Part 2](#Part-2) 
  8. Lecture 5: [Linear Predictors](#Linear-Predictors)
  9. Lecture 6: [Boosting](#Boosting)
  10. Lecture 7: [Model Selection and Validation](#Model-Selection-and-Validation)
  
  - [Extra NoteBooks and Slides](#Extra-NoteBooks-and-Slides)
- [Class Time and Location](#Class-Time-and-Location)
- [Projects](#Projects)
  - [Google Colab](#Google-Colab)
  - [Fascinating Guides For Machine Learning](#Fascinating-Guides-For-Machine-Learning)
  - [Latex](#Latex)
- [Grading](#Grading)
- [Prerequisites](#Prerequisites)
  - [Linear Algebra](#Linear-Algebra)
  - [Probability and Statistics](#Probability-and-Statistics)
  - [Discrete Mathematics](#Discrete-Mathematics)
- [Topics](#Topics)
- [Account](#Account)
- [Academic Honor Code](#Academic-Honor-Code)
- [Questions](#Questions)
- Miscellaneous
  - [Tutorials](https://hhaji.github.io/Applied-Machine-Learning/Tutorials) 
  - [Data](https://hhaji.github.io/Applied-Machine-Learning/Data)
  - [Projects](https://hhaji.github.io/Applied-Machine-Learning/Projects)
  
---

## <a name="Course-Overview"></a>Course Overview:
```javascript
Machine learning is an area of artificial intelligence that provides systems the ability to 
automatically learn. Machine learning allows machines to handle new situations via analysis, 
self-training, observation and experience. The wonderful success of machine learning has made 
it the default method of choice for artificial intelligence experts. In this course, we review 
the fundamentals and algorithms of machine learning. 
```
## <a name="Main-TextBooks"></a>Main TextBooks:
* [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning), by Shai Shalev-Shwartz and Shai Ben-David <br>
* [Machine Learning Mastery With Python](https://machinelearningmastery.com/machine-learning-with-python/) by Jason Brownlee<br>
    - [Python Codes](https://github.com/rupskygill/ML-mastery/tree/master/ml_with_python_code) <br>
* [Introduction to Machine Learning with Python: A Guide for Data Scientists](https://www.amazon.com/Introduction-Machine-Learning-Python-Scientists/dp/1449369413) by Andreas Mueller and Sarah Guido
    - [Notebooks](https://github.com/amueller/introduction_to_ml_with_python) <br>
* [Hands-On Machine Learning with Scikit-Learn & TensorFlow](http://shop.oreilly.com/product/0636920052289.do) by  Aurélien Géron <br>
    - [Notebooks](https://github.com/ageron/handson-ml) <br>
* [Machine Learning: The Art and Science of Algorithms That Make Sense of Data](https://www.cs.bris.ac.uk/~flach/mlbook/) by Peter Flach <br>
* [An Introduction to Statistical Learning: with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani <br>

## <a name="Slides-and-Papers"></a>Slides and Papers:

Recommended Slides & Papers:
1. ### Toolkit Lab: <a name="Part-1"></a>Part 1
- [Tools in Data Science](https://hhaji.github.io/Tools-in-Data-Science/)
- [Python Libraries for Data Science](https://github.com/hhaji/Tools-in-Data-Science#Python-Libraries-for-Data-Science) <br>
    **Exercises:** Practice Numpy in [LabEx](https://labex.io/courses/100-numpy-exercises) <br>
    **Exercises:** Practice Pandas in [LabEx](https://labex.io/courses/100-pandas-exercises) <br>
    **Exercises:** Practice Matplotlib in [LabEx](https://labex.io/courses/draw-2d-and-3d-graphics-by-matplotlib) <br>
2. ### <a name="Introduction"></a>Introduction
- Slide: [Machine Learning: Types of Machine Learning I](http://www.lsi.upc.es/~bejar/apren/docum/trans/00-introAprendizaje-eng.pdf) by Javier Bejar  
- Slide: [Machine Learning: Types of Machine Learning II](http://www.lsi.upc.edu/~bejar/apren/docum/trans/01-apind-eng.pdf) by Javier Bejar  
3. ### <a name="Empirical-Risk-Minimization"></a>Empirical Risk Minimization 
    A Formal Model – The Statistical Learning Framework & Empirical Risk Minimization <br>
   Chapter 2 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
       **Exercises:** 2.1, 2.2, and 2.3  
- Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
- Slide: [Lecture 1](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture1.pdf) by Shai Shalev-Shwartz <br>
    
4. ### <a name="PAC-Learning"></a>PAC Learning
   Chapter 3 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
       **Exercises:** 3.2, 3.4, 3.5, 3.7, 3.9  
 - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
 - Slide: [Lecture 2](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture2.pdf) by Shai Shalev-Shwartz 
5. ### <a name="The-Bias-Complexity-Tradeoff"></a>The Bias-Complexity Tradeoff  
   Chapter 5 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
       **Exercise:** 5.2  
  - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
  - Slide: [Lecture 3](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture3.pdf) by Shai Shalev-Shwartz <br>
  - Paper: [The Bias-Variance Dilemma](https://www.inf.fu-berlin.de/inst/ag-ki/rojas_home/documents/tutorials/bias.pdf) by Raul Rojas <br>
   
6. ###   <a name="The-VC-Dimension"></a>The VC-Dimension 
 Chapter 6 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
        **Exercises:** 6.2, 6.4, 6.6, 6.9, 6.10, and 6.11 <br>
- Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
     
7. ### Toolkit Lab: <a name="Part-2"></a>Part 2 
- [Machine Learning Mastery With Python](https://machinelearningmastery.com/machine-learning-with-python/) by Jason Brownlee <br>
  - [Python Codes](https://github.com/rupskygill/ML-mastery/tree/master/ml_with_python_code) <br>
- Data Exploration: <br>
  - NoteBook: [Titanic 1 – Data Exploration](http://stamfordresearch.com/titanic-1-data-exploration/) by John Stamford 
  - NoteBook: [Kaggle Titanic Supervised Learning Tutorial](https://www.kaggle.com/sashr07/kaggle-titanic-tutorial)
  - NoteBook: [An Example Machine Learning Notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by  Randal S. Olson <br>
- Homework: [Take the 7-Day Machine Learning Challenge of Kaggle:](https://www.kaggle.com/page/machine-learning-course-ads?utm_medium=paid) Machine learning is the hottest field in data science, and this track will get you started quickly. <br> 
     
8. ### <a name="Linear-Predictors"></a>Linear Predictors 
 Chapter 9 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
       **Exercises:** 9.1, 9.3, 9.4, and 9.6 <br>
 - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
 - Slide: [Tutorial 3: Consistent linear predictors and Linear regression](https://webcourse.cs.technion.ac.il/236756/Spring2014/ho/WCFiles/Tutorial%203.pdf) by Nir Ailon <br>
 - NoteBook: [Perceptron in Scikit](https://github.com/chrisalbon/notes/blob/master/content/machine_learning/basics/perceptron_in_scikit-learn.ipynb) by Chris Albon <br>
 - Paper: [Perceptron for Imbalanced Classes and Multiclass Classification](https://www.cs.utah.edu/~piyush/teaching/imbalanced_multiclass_perceptron.pdf) by Piyush Rai <br>
 - NoteBook: [Linear regression](http://nbviewer.ipython.org/github/justmarkham/DAT4/blob/master/notebooks/08_linear_regression.ipynb) by Kevin Markham <br>  
 - Paper: [Matrix Differentiation](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf) by Randal J. Barnes <br>
 - Lecture: [Logistic Regression](https://www.stat.cmu.edu/~cshalizi/uADA/12/lectures/ch12.pdf) by Cosma Shalizi <br>
 - NoteBook: [Logistic Regression-Analysis](https://nbviewer.jupyter.org/github/nborwankar/LearnDataScience/blob/master/notebooks/WB3.%20Logistic%20Regression%20-%20Analysis-%20Worksheet.ipynb) by Nitin Borwankar <br>
    - [DataSets](https://github.com/nborwankar/LearnDataScience/tree/master/datasets) <br>
 
9. ### <a name="Boosting"></a>Boosting 
 Chapter 10 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
       **Exercises:** 10.1, 10.3, 10.4, and 10.5 <br>
- Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
- Paper: [Ensemble Methods in Machine Learnin](http://web.engr.oregonstate.edu/~tgd/publications/mcs-ensembles.pdf) by Thomas G􏰀 Dietterich <br>
- Slide: [Ensemble methods: Bagging and Boosting](https://people.cs.pitt.edu/~milos/courses/cs2750-Spring04/lectures/class23.pdf) by Milos Hauskrecht <br>
- Slide: [Ensemble Learning through Diversity Management: Theory, Algorithms, and Applications](http://staff.ustc.edu.cn/~hchen/tutorial/IJCNN2011.pdf) by Huanhuan Chen and Xin Yao <br>
- Slide: [Ensemble Methods](http://users.umiacs.umd.edu/~hcorrada/PracticalML/pdf/lectures/EnsembleMethods.pdf) by Héctor Corrada Bravo (Adapted from slides by Todd Holloway) <br>
- Slide: [Tutorial 3](https://www.cs.ubc.ca/~schmidtm/Courses/340-F16/T3.pdf) by Mark Schmidt <br>
     
10. ### <a name="Model-Selection-and-Validation"></a>Model Selection and Validation  
- Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br> 
- NoteBook: [Cross Validation](https://www.ritchieng.com/machine-learning-cross-validation/) by Ritchie Ng <br>
     
- ### <a name="Extra-NoteBooks-and-Slides"></a>Extra NoteBooks and Slides:
  * [Python Machine Learning Book Code Repository](https://github.com/rasbt/python-machine-learning-book) <br>
  * [Dive into Machine Learning](https://github.com/hangtwenty/dive-into-machine-learning) <br>
  * [Python code for "An Introduction to Statistical Learning with Applications in R"](https://github.com/JWarmenhoven/ISLR-python) by Jordi Warmenhoven <br>
  * [iPython-NoteBooks](https://github.com/jdwittenauer/ipython-notebooks) by John Wittenauer <br>
  * [Scikit-Learn Tutorial](https://github.com/jakevdp/sklearn_tutorial) by Jake Vanderplas <br>
  * [Data Science Roadmap](https://github.com/estraviz/data-science-roadmap#4-machine-learning-back-to-top-) by Javier Estraviz <br>

## <a name="Class-Time-and-Location"></a>Class Time and Location:
Saturday and Monday 08:00-09:30 AM (Spring 2019), Room 204/1. 

## <a name="Projects"></a>Projects:
Projects are programming assignments that cover the topic of this course. Any project is written by     
**[Jupyter Notebook](http://jupyter.org)**. Projects will require the use of Python 3.7, as well as  
additional Python libraries as follows.  

* [Python 3.7:](https://www.python.org/downloads/) An interactive, object-oriented, extensible programming language. <br>
* [NumPy:](http://www.numpy.org) A Python package for scientific computing. <br>
* [Pandas:](https://pandas.pydata.org) A Python package for high-performance, easy-to-use data structures and data analysis tools. <br>
* [Scikit-Learn:](https://scikit-learn.org/stable/) A Python package for machine learning. <br>
* [Matplotlib:](https://matplotlib.org) A Python package for 2D plotting. <br>
* [SciPy:](https://www.scipy.org) A Python package for mathematics, science, and engineering. <br>
* [IPython:](https://ipython.org) An architecture for interactive computing with Python. <br>

### <a name="Google-Colab"></a>Google Colab:
[Google Colab](https://colab.research.google.com) is a free cloud service and it supports free GPU! 
  - [Primer for Learning Google Colab](https://medium.com/dair-ai/primer-for-learning-google-colab-bb4cabca5dd6)
  - [Deep Learning Development with Google Colab, TensorFlow, Keras & PyTorch](https://www.kdnuggets.com/2018/02/google-colab-free-gpu-tutorial-tensorflow-keras-pytorch.html)

### <a name="Fascinating-Guides-For-Machine-Learning"></a>Fascinating Guides For Machine Learning:
* [Technical Notes On Using Data Science & Artificial Intelligence: To Fight For Something That Matters](https://chrisalbon.com) by Chris Albon

### <a name="Latex"></a>Latex:
The students can include mathematical notation within markdown cells using LaTeX in their **[Jupyter Notebooks](http://jupyter.org)**.<br>
  - A Brief Introduction to LaTeX [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/latex.pdf)  <br>
  - Math in LaTeX [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/math.pdf) <br>
  - Sample Document [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/sample.pdf) <br>

## <a name="Grading"></a>Grading:
* Projects and Midterm – 50%
* Endterm – 50%

## <a name="Prerequisites"></a>Prerequisites:
General mathematical sophistication; and a solid understanding of Algorithms, Linear Algebra, and 
Probability Theory, at the advanced undergraduate or beginning graduate level, or equivalent.

### <a name="Linear-Algebra"></a>Linear Algebra:
- Video: Professor Gilbert Strang's [Video Lectures](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/) on linear algebra.

### <a name="Probability-and-Statistics"></a>Probability and Statistics:
- [Learn Probability and Statistics Through Interactive Visualizations:](https://seeing-theory.brown.edu/index.html#firstPage) Seeing Theory was created by Daniel Kunin while an undergraduate at Brown University. The goal of this website is to make statistics more accessible through interactive visualizations (designed using Mike Bostock’s JavaScript library D3.js).
- [Statistics and Probability:](https://stattrek.com) This website provides training and tools to help you solve statistics problems quickly, easily, and accurately - without having to ask anyone for help.
- Jupyter NoteBooks: [Introduction to Statistics](https://github.com/rouseguy/intro2stats) by Bargava
- Video: Professor John Tsitsiklis's [Video Lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/video-lectures/) on Applied Probability.
- Video: Professor Krishna Jagannathan's [Video Lectures](https://nptel.ac.in/courses/108106083/) on Probability Theory.

### <a name="Discrete-Mathematics"></a>Discrete Mathematics:
Course (Videos, Lectures, Assignments): [MIT OpenCourseWare (Discrete Mathematics)](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/index.htm)

## <a name="Topics"></a>Topics:
Have a look at some reports of [Kaggle](https://www.kaggle.com/) or Stanford students ([CS224N](http://nlp.stanford.edu/courses/cs224n/2015/), [CS224D](http://cs224d.stanford.edu/reports_2016.html)) to get some general inspiration.

## <a name="Account"></a>Account:
It is necessary to have a [GitHub](https://github.com/) account to share your projects. It offers 
plans for both private repositories and free accounts. Github is like the hammer in your toolbox, 
therefore, you need to have it!

## <a name="Academic-Honor-Code"></a>Academic Honor Code:
Honesty and integrity are vital elements of the academic works. All your submitted assignments must be entirely your own (or your own group's).

We will follow the standard of Department of Mathematical Sciences approach: 
* You can get help, but you MUST acknowledge the help on the work you hand in
* Failure to acknowledge your sources is a violation of the Honor Code
*  You can talk to others about the algorithm(s) to be used to solve a homework problem; as long as you then mention their name(s) on the work you submit
* You should not use code of others or be looking at code of others when you write your own: You can talk to people but have to write your own solution/code

## <a name="Questions"></a>Questions?
I will be having office hours for this course on Monday (09:30 AM--12:00 AM). If this is not convenient, email me at hhaji@sbu.ac.ir or talk to me after class.
