# Applied Machine Learning   

<table>
  <tr>
    <th colspan="2"><span style="font-weight:bold">Lecturer: </span><a href="http://facultymembers.sbu.ac.ir/hhaji/">Hossein Hajiabolhassan</a><br><br><a href="http://ds.sbu.ac.ir/">Data Science Center</a> <br><br><a href="http://en.sbu.ac.ir/">Shahid Beheshti University</a></th>
    <th colspan="3"><img src=".\Images\HH.jpg" alt="" border='3' height='140' width='140' /></th>
  </tr>
  <tr>
    <td colspan="5"><span style="font-weight:bold">Teaching Assistants:</span></td>
  </tr>
  <tr>
    <td><a href="https://github.com/zahta">Zahra Taheri</a></td>
    <td><a href="https://github.com/alihojatnia">Ali Hojatnia</a></td>
    <td><a href="https://github.com/YavarYeganeh">Yavar T. Yeganeh</a></td>
  </tr>
  <tr>
    <td><img src=".\Images\DrTaheri.jpeg" alt="" border='3' height='140' width='120' /></td>
    <td><img src=".\Images\MrHojatneia.jpeg" alt="" border='3' height='140' width='120' /></td>
     <td><img src=".\Images\MrYeganeh.jpg" alt="" border='3' height='140' width='120' /></td>
  </tr>
  <tr>
    <td><a href="https://github.com/fatemeamanian">Fatemeh Amanian</a></td>
    <td><a href="https://github.com/MhdsHosseini">Mahdis Hosseini</a></td>
    <td><a href="https://github.com/sohrabfaridi">Sohrab Faridi</a></td>
  </tr>
  <tr>
    <td><img src=".\Images\MsAmanian.jpeg" alt="" border='3' height='140' width='120' /></td>
    <td><img src=".\Images\MsHosseini.jpeg" alt="" border='3' height='140' width='120' /></td>
    <td><img src=".\Images\MrFaridi.jpg" alt="" border='3' height='140' width='120' /></td>   
  </tr>
</table>


---

### **Index:**
- [Course Overview](#Course-Overview)
- [TextBooks](#TextBooks)
- [Slides and Papers](#Slides-and-Papers)
  1. Lecture 1: [Toolkit Lab (Part 1)](#Part-1) 
  2. Lecture 2: [Introduction](#Introduction)
  3. Lecture 3: [Empirical Risk Minimization](#Empirical-Risk-Minimization)
  4. Lecture 4: [PAC Learning](#PAC-Learning)
  5. Lecture 5: [The Bias-Complexity Tradeoff](#The-Bias-Complexity-Tradeoff)  
  6. Lecture 6: [Learning via Uniform Convergence](#LUC)
  7. Lecture 7: [The VC-Dimension](#The-VC-Dimension)
  8. Lecture 8: [Toolkit Lab (Part 2)](#Part-2) 
  9. Lecture 9: [Linear Predictors](#Linear-Predictors)
  10. Lecture 10: [Decision Trees](#Decision-Trees) 
  11. Lecture 11: [Nearest Neighbor](#Nearest-Neighbor) 
  12. Lecture 12: [Ensemble Methods](#Ensemble-Methods)
  13. Lecture 13: [Model Selection and Validation](#Model-Selection-and-Validation)
  14. Lecture 14: [Neural Networks](#Neural-Networks)    
  15. Lecture 15: [Convex Learning Problems](#CLP) 
  16. Lecture 16: [Regularization and Stability](#Regularization-and-Stability) 
  17. Lecture 17: [Support Vector Machines](#Support-Vector-Machines) 
  18. Lecture 18: [Multiclass Classification](#Multiclass-Classification) 

  - [Additional NoteBooks and Slides](#Additional-NoteBooks-and-Slides)
- [Class Time and Location](#Class-Time-and-Location)
  - [Recitation and Assignments](#MTA)  
- [Projects](#Projects)
  - [Practical Guide](#Practical-Guide)
  - [Fascinating Guide to Use Python Libraries (Machine Learning)](#Fascinating-Guide-For-Machine-Learning)
  - [Google Colab](#Google-Colab)
  - [Latex](#Latex)
  - [Useful NoteBooks](#Useful-NoteBooks)
- [Grading](#Grading)
  - [Two Written Exams](#Two-Written-Exams)
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
  - [Data Handling](https://hhaji.github.io/Applied-Machine-Learning/Data-Handling)
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
## <a name="TextBooks"></a>TextBooks:

<table class="tg">
  <tr>
    <td class="tg-0lax"><img src=".\Images\shalev-shwartz-1x.jpg" alt="" border='3' height='160' width='170' /></td>
    <td class="tg-0lax"><img src=".\Images\james-1x.png" alt="" border='3' height='160' width='170' /></td>
    <td class="tg-0lax"><img src=".\Images\Hands-On-ML.jpg" alt="" border='3' height='160' width='170' /></td>
    <td class="tg-0lax"><img src=".\Images\bishop-1x.jpg" alt="" border='3' height='160' width='170' /></td>
    <td class="tg-0lax"><img src=".\Images\homl-cover.jpg" alt="" border='3' height='160' width='170' /></td>
  </tr>
</table>

```
Main TextBooks:
```

* [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning), by Shai Shalev-Shwartz and Shai Ben-David     
* [An Introduction to Statistical Learning: with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani    
* [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow (2nd Edition)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) by Aurelien Geron   

```
Additional TextBooks:
```

* [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/people/cmbishop/?from=https%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fum%2Fpeople%2Fcmbishop%2FPRML%2F#!prml-book) by Christopher Bishop <br>
* [Hands-On Machine Learning with R](https://bradleyboehmke.github.io/HOML/) by Bradley Boehmke and Brandon Greenwell   

## <a name="Slides-and-Papers"></a>Slides and Papers:

Recommended Slides & Papers:
1. ### <a name="Part-1"></a>Toolkit Lab (Part 1: Anaconda, Jupyter Lab, Markdown, Git, GitHub, and Google Colab)  

```
Required Reading:
```
Anaconda, Jupyter Lab, Markdown, Git, GitHub, and Google Colab:  
  * Blog: [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#managing-environments)   
  * Blog: [Kernels for Different Environments](https://ipython.readthedocs.io/en/stable/install/kernel_install.html#kernels-for-different-environments)   
  * Slide: [Practical Data Science: Jupyter NoteBook Lab](http://www.datasciencecourse.org/slides/jupyter.pdf) by Zico Kolter    
  * [Awesome JupyterLab](https://github.com/mauhai/awesome-jupyterlab) by Hai Nguyen Mau
  * Blog: [Learn Markdown Online](https://commonmark.org/help/tutorial/) 
  * Slide: [An Introduction to Git](https://elite.polito.it/files/courses/03FYZ/2017/slide/Git-01-intro.pdf) by Politecnico di Torino   
  * Blog: [Google Colab Free GPU Tutorial](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d) by Fuat   

<table>
  <tr>
    <th colspan="3">Teaching Assitant Class:</th>
  </tr>
  <tr>
    <td colspan="3">Python continues to take leading positions in solving data science tasks and challenges.  <br>Here are three of the most important of libraries.</td>
  </tr>
  <tr>
    <td><a href="http://www.numpy.org/">Numpy</a> is the fundamental<br>package for scientific <br>computing with Python.</td>
    <td><a href="https://pandas.pydata.org/">Pandas</a> is an easy-to-use data <br>structures and data analysis tools</td>
    <td><a href="https://matplotlib.org/">Matplotlib</a> is a Python <br>2D plotting library</td>
  </tr>
  <tr>
    <td colspan="3">Resources:</td>
  </tr>
  <tr>
    <th><a href="http://www.scipy-lectures.org/index.html">Scipy Lecture Notes</a></th>
    <th colspan="2"><a href="https://github.com/donnemartin/data-science-ipython-notebooks">Data Science iPython Notebooks</a></th>
  </tr>
</table>  


  * Homeworks: [Python Libraries for Data Science](https://github.com/hhaji/Tools-in-Data-Science#Python-Libraries-for-Data-Science)
    - **Exercises:** Practice Numpy in [LabEx](https://labex.io/courses/100-numpy-exercises) <br>
    - **Exercises:** Practice Pandas in [LabEx](https://labex.io/courses/100-pandas-exercises) <br>
    - **Exercises:** Practice Matplotlib in [LabEx](https://labex.io/courses/draw-2d-and-3d-graphics-by-matplotlib) <br>
 
```
Suggested Reading:
```
 
 * [Tools in Data Science](https://hhaji.github.io/Tools-in-Data-Science/) 
 * [28 Jupyter Notebook Tips, Tricks, and Shortcuts](https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/) by Josh Devlin  
 * Cheat Sheet: [Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)  
 * [Git Cheat Sheet](https://github.com/hhaji/Tools-in-Data-Science/blob/master/Cheat%20Sheets/Git%20Cheat%20Sheet.md) 
 * [R Tutorial for Beginners: Learning R Programming](https://www.guru99.com/r-tutorial.html) 

```
Additional Resources:
```
  * PDF: [Conda Cheat Sheet](https://docs.conda.io/projects/conda/en/latest/_downloads/1f5ecf5a87b1c1a8aaf5a7ab8a7a0ff7/conda-cheatsheet.pdf) 
  * Blog: [Conda Commands (Create Virtual Environments for Python with Conda)](http://deeplearning.lipingyang.org/2018/12/25/conda-commands-create-virtual-environments-for-python-with-conda/) by LipingY <br>  
  * Blog: [Colab Tricks](https://rohitmidha23.github.io/Colab-Tricks/) by  Rohit Midha   
  * Paper: [Machine Learning in Python: Main Developments and Technology Trends in Data Science, Machine Learning, and Artificial Intelligence](https://arxiv.org/pdf/2002.04803.pdf) by Sebastian Raschka, Joshua Patterson, and Corey Nolet   
  * The following table was adopted from [Applied Machine Learning and Deep Learning](http://people.uncw.edu/chenc/STT592_Deep%20Learning/STT592DeepLearning_Index.html) created by Cuixian Chen   
 
  <table>
  <tr>
    <td><span style="font-weight:bold">Python Overview [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Python%20Overview.docx"><span style="font-weight:bold">Word</span></a><span style="font-weight:bold">]</span><br><br><br><span style="font-weight:bold">Python Tutorial [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_intro.pdf"><span style="font-weight:bold">PDF</span></a><span style="font-weight:bold">]  [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_tutorial2.pdf"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Numpy [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_tutorial2.pdf"><span style="font-weight:bold">PDF</span></a><span style="font-weight:bold">] [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/numpy_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">User Guide [</span><a href="https://docs.scipy.org/doc/numpy-1.15.0/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Quickstart [</span><a href="https://docs.scipy.org/doc/numpy-1.15.0/user/quickstart.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://docs.scipy.org/doc/numpy-1.15.0/reference/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Practice Numpy in LabEx [</span><a href="https://labex.io/courses/100-numpy-exercises"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Matplotlib [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/python_tutorial2.pdf"><span style="font-weight:bold">PDF</span></a><span style="font-weight:bold">][</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/matplotlib_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Example [</span><a href="https://matplotlib.org/gallery/index.html#"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Tutorials [</span><a href="https://matplotlib.org/tutorials/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://matplotlib.org/api/_as_gen/matplotlib.pyplot.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Practice Matplotlib in LabEx [</span><a href="https://labex.io/courses/draw-2d-and-3d-graphics-by-matplotlib"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
  </tr>
  <tr>
    <td><span style="font-weight:bold">Pandas [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Pandas_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">10 Min to Pandas [</span><a href="https://pandas.pydata.org/pandas-docs/stable/10min.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cookbook [</span><a href="https://pandas.pydata.org/pandas-docs/stable/cookbook.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Tutorials [</span><a href="https://pandas.pydata.org/pandas-docs/stable/tutorials.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://pandas.pydata.org/pandas-docs/stable/"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Practice Pandas in LabEx [</span><a href="https://labex.io/courses/100-pandas-exercises"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Seaborn: Stat data </span><br><span style="font-weight:bold">Visulization [</span><a href="https://seaborn.pydata.org/"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Example [</span><a href="https://seaborn.pydata.org/examples/index.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Tutorials [</span><a href="https://seaborn.pydata.org/tutorial.html"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Reference [</span><a href="https://seaborn.pydata.org/api.html#api-ref"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="http://www.utc.fr/~jlaforet/Suppl/python-cheatsheets.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
    <td><span style="font-weight:bold">Scikit Learn [</span><a href="https://scikit-learn.org/stable/?fbclid=IwAR0DE6Q4LLO48d226SwF8j6TbUoqjBw769bNEcOBF9ohBW8Wgz9WscvgzEw"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">] </span><br><span style="font-weight:bold">Scikit Image [</span><a href="http://scikit-image.org/docs/dev/auto_examples/?fbclid=IwAR3v-V5IlW1Jjz-NcSbGuDFJ71KUFRk5KmPoFRCD8LuuAyTzUF8v0N4nwUU"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Scikit Tutorial #1 [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/scikit_tutorial.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Scikit Tutorial #2 [</span><a href="http://people.uncw.edu/chenc/STT592_Deep%20Learning/Python/Kling_Python%20Scripts/scikit_tutorial2.py"><span style="font-weight:bold">Code</span></a><span style="font-weight:bold">]</span><br><span style="font-weight:bold">Cheatsheet [</span><a href="https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Scikit_Learn_Cheat_Sheet_Python.pdf"><span style="font-weight:bold">Link</span></a><span style="font-weight:bold">]</span></td>
  </tr>
</table>

2. ### <a name="Introduction"></a>Introduction  
  
    ```
    Required Reading:
    ```
 
    - Introduction  
    Chapter 1 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)

3. ### <a name="Empirical-Risk-Minimization"></a>Empirical Risk Minimization  

    ```
    Required Reading:
    ```
    
    - A Formal Model – The Statistical Learning Framework & Empirical Risk Minimization   
    Chapter 2 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)
        - **Exercises:** 2.1, 2.2, and 2.3  
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt  <br>
    - Slide: [Lecture 1](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture1.pdf) by Shai Shalev-Shwartz    
    - Blog: [Some Key Machine Learning Definitions](https://medium.com/technology-nineleaps/some-key-machine-learning-definitions-b524eb6cb48) by Joydeep Bhattacharjee   
    
4. ### <a name="PAC-Learning"></a>PAC Learning  

    ```
    Required Reading:
    ```
    
    - Chapter 3 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)   
        - **Exercises:** 3.2, 3.3, 3.4, 3.5, 3.6, 3.7
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt   
    - Slide: [Lecture 2](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture2.pdf) by Shai Shalev-Shwartz  
    
5.  ### <a name="LUC"></a>Learning via Uniform Convergence 

    ```
    Required Reading:
    ```
     - Chapter 4 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>

    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt    
    
6. ### <a name="The-Bias-Complexity-Tradeoff"></a>The Bias-Complexity Tradeoff  

    ```
    Required Reading:
    ```
    
    - Chapter 5 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)  
        - **Exercise:** 5.2  
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
    - Slide: [Lecture 3](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture3.pdf) by Shai Shalev-Shwartz <br>
    - Paper: [The Bias-Variance Dilemma](https://www.inf.fu-berlin.de/inst/ag-ki/rojas_home/documents/tutorials/bias.pdf) by Raul Rojas     
    
    ```
    Suggested Reading:
    ```
    
    - Paper: [A Unified Bias-Variance Decomposition](https://homes.cs.washington.edu/~pedrod/bvd.pdf) by Pedro Domingos   
  
    ```
    Additional Reading:
    ```
    
    - NoteBook: [Exploring the Bias-Variance Tradeoff](https://github.com/justmarkham/DAT8/blob/master/notebooks/08_bias_variance.ipynb) by Kevin Markham    
    - Blog: [Bias-Variance Decomposition](http://rasbt.github.io/mlxtend/user_guide/evaluate/bias_variance_decomp/) by Sebastian Raschka  
    - Slide: [Bias-Variance Theory](https://web.engr.oregonstate.edu/~tgd/classes/534/slides/part9.pdf) by Thomas G. Dietterich   
       
7. ###   <a name="The-VC-Dimension"></a>The VC-Dimension 

    ```
    Required Reading:
    ```
    
    - Chapter 6 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
        - **Exercises:** 6.2, 6.4, 6.6, 6.9, 6.10, and 6.11 <br>
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
     
8. ### <a name="Part-2"></a>Toolkit Lab (Part 2) 

    ```
    Required Reading:
    ```
    
    - [Machine Learning Mastery With Python](https://machinelearningmastery.com/machine-learning-with-python/) by Jason Brownlee  <br>
        - [Python Codes](https://github.com/rupskygill/ML-mastery/tree/master/ml_with_python_code) <br>
    - Data Exploration:  
        - NoteBook: [Titanic 1 – Data Exploration](http://stamfordresearch.com/titanic-1-data-exploration/) by John Stamford  
        - NoteBook: [Kaggle Titanic Supervised Learning Tutorial](https://www.kaggle.com/sashr07/kaggle-titanic-tutorial)  
        - NoteBook: [An Example Machine Learning Notebook](https://github.com/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb) by  Randal S. Olson   
        - Homework: [Take the 7-Day Machine Learning Challenge of Kaggle:](https://www.kaggle.com/page/machine-learning-course-ads?utm_medium=paid) Machine learning is the hottest field in data science, and this track will get you started quickly.   
     
9. ### <a name="Linear-Predictors"></a>Linear Predictors 

    ```
    Required Reading:
    ```
    
    - Chapter 9 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)   
        - **Exercises:** 9.1, 9.3, 9.4, and 9.6   
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
    - Slide: [Tutorial 3: Consistent linear predictors and Linear regression](https://webcourse.cs.technion.ac.il/236756/Spring2014/ho/WCFiles/Tutorial%203.pdf) by Nir Ailon <br>
    - NoteBook: [Perceptron in Scikit](https://github.com/chrisalbon/notes/blob/master/content/machine_learning/basics/perceptron_in_scikit-learn.ipynb) by Chris Albon <br>
    - Blog: [Why Linear Regression is not Suitable for Classification](https://jinglescode.github.io/datascience/2019/05/07/why-linear-regression-is-not-suitable-for-classification/) by Hong Jing  
    - Slide: [Logistic Regression](http://courses.washington.edu/css490/2012.Winter/lecture_slides/05b_logistic_regression.pdf) by Jeff Howbert   

    ```
    Additional Reading:
    ```
   
    - Blog: [MAE, MSE, RMSE, Coefficient of Determination, Adjusted R Squared — Which Metric is Better?](https://medium.com/analytics-vidhya/mae-mse-rmse-coefficient-of-determination-adjusted-r-squared-which-metric-is-better-cd0326a5697e) by Akshita Chugh   
    - Blog: [Key Difference between R-squared and Adjusted R-squared for Regression Analysis](https://www.analyticsvidhya.com/blog/2020/07/difference-between-r-squared-and-adjusted-r-squared/) by Aniruddha Bhandari   
    - NoteBook: [Linear Regression](http://nbviewer.ipython.org/github/justmarkham/DAT4/blob/master/notebooks/08_linear_regression.ipynb) by Kevin Markham <br>  
    - Paper: [Matrix Differentiation](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf) by Randal J. Barnes   
    - Lecture: [Logistic Regression](https://www.stat.cmu.edu/~cshalizi/uADA/12/lectures/ch12.pdf) by Cosma Shalizi   
    - Lecture: [Multiclass Classification](https://u.cs.biu.ac.il/~jkeshet/teaching/aml2016/multiclass.pdf) by Yossi Keshet  
    - NoteBook: [Logistic Regression-Analysis](https://nbviewer.jupyter.org/github/nborwankar/LearnDataScience/blob/master/notebooks/WB3.%20Logistic%20Regression%20-%20Analysis-%20Worksheet.ipynb) by Nitin Borwankar <br>
        - [DataSets](https://github.com/nborwankar/LearnDataScience/tree/master/datasets) <br>
    - NoteBook: [Logistic Regression](https://github.com/justmarkham/DAT8/blob/master/notebooks/12_logistic_regression.ipynb) by Kevin Markham <br>  
    - Infographic and Code: [Simple Linear Regression (100 Days Of ML Code)](https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Code/Day2_Simple_Linear_Regression.md) by Avik Jain <br>
    - Infographic and Code: [Multiple Linear Regression (100 Days Of ML Code)](https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Code/Day3_Multiple_Linear_Regression.md) by Avik Jain <br>
    - Infographic and Code: [Logistic Regression (100 Days Of ML Code)](https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Code/Day%206%20Logistic%20Regression.md) by Avik Jain <br>

    ```
    R (Programming Language):
    ```
   
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Linear Regression](http://uc-r.github.io/linear_regression) by UC Business Analytics R Programming Guide <br>
    * Blog: [Linear Regression with lm()](https://bookdown.org/ndphillips/YaRrr/linear-regression-with-lm.html) by Nathaniel D. Phillips <br>
    * Blog: [Logistic Regression](http://uc-r.github.io/logistic_regression) by UC Business Analytics R Programming Guide <br>

10. ### <a name="Decision-Trees"></a>Decision Trees  

    ```
    Required Reading:
    ```
    
    - Chapter 18 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)   
        - **Exercise:** 18.2   
    - Slide: [Decision Trees](https://www.utdallas.edu/~nrr150130/cs6375/2015fa/lects/Lecture_6_Decision.pdf) by Nicholas Ruozzi   
    - Slide: [Representation of Boolean Functions](http://freeusermanuals.com/backend/web/manuals/1522928344lec2.pdf) by Troels Bjerre Sørensen <br>
    - Slide: [Overfitting in Decision Trees](https://www3.nd.edu/~rjohns15/cse40647.sp14/www/content/lectures/24%20-%20Decision%20Trees%203.pdf) by Reid Johnson <br>
    - NoteBook: [Decision Trees](https://github.com/hhaji/Applied-Machine-Learning/blob/master/NoteBooks/Decision-Trees.ipynb) <br>
 
    ```
    Additional Reading:
    ```

    - Paper: [Do We Need Hundreds of Classifiers to Solve Real World Classification Problems?](http://jmlr.csail.mit.edu/papers/volume15/delgado14a/delgado14a.pdf) by Manuel Fernandez-Delgado, Eva Cernadas, Senen Barro, and Dinani Amorim <br>
    - Blog: [Random Forest Classifier Example](https://chrisalbon.com/machine_learning/trees_and_forests/random_forest_classifier_example/) by Chris Albon.  This tutorial is based on Yhat’s 2013 tutorial on [Random Forests in Python](http://blog.yhat.com/posts/random-forests-in-python.html). 
          - [NoteBook](https://github.com/chrisalbon/notes/blob/master/docs/machine_learning/trees_and_forests/random_forest_classifier_example.ipynb) <br>
    - NoteBook: [Titanic Competition with Random Forest](https://github.com/chrisalbon/kaggle/blob/master/titanic/titanic_competition_with_random_forest.ipynb) by Chris Albon <br>
    - Infographic and Code: [Decision Trees (100 Days Of ML Code)]( https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Code/Day%2025%20Decision%20Tree.md) by Avik Jain <br>
 
    ```
    R (Programming Language):
    ```
   
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Decision Tree Classifier Implementation in R](http://dataaspirant.com/2017/02/03/decision-tree-classifier-implementation-in-r/) by Rahul Saxena <br>
    * Blog: [Regression Trees](http://uc-r.github.io) by UC Business Analytics R Programming Guide <br>

11. ### <a name="Nearest-Neighbor"></a>Nearest Neighbor   

    ```
    Required Reading:
    ```
    
    - Chapter 19 (Section 1) of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
    - Slide: [Nearest Neighbor Classification](http://svivek.com/teaching/machine-learning/fall2018/slides/nearest-neighbors/nearest-neighbors.pdf) by Vivek Srikumar <br>
    - NoteBook: [k-Nearest Neighbors](https://github.com/hhaji/Applied-Machine-Learning/blob/master/NoteBooks/k-Nearest-Neighbors.ipynb) <br>

    ```
    Additional Reading:
    ```
    - Blog: [Voronoi Tessellations](https://datagenetics.com/blog/may12017/index.html)     
    - NoteBook: [Training a Machine Learning Model with Scikit-Learn](https://github.com/justmarkham/scikit-learn-videos/blob/master/04_model_training.ipynb) by Kevin Markham <br>
        - [Video](https://www.youtube.com/watch?v=RlQuVL6-qe8&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=4) <br>
    - NoteBook: [Comparing Machine Learning Models in Scikit-Learn](https://github.com/justmarkham/scikit-learn-videos/blob/master/05_model_evaluation.ipynb) by Kevin Markham <br>
        - [Video](https://www.youtube.com/watch?v=0pP4EwWJgIU&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=5) <br> 
    - Infographic: [K-Nearest Neighbours (100 Days Of ML Code)](https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%207.jpg) by Avik Jain <br>
 
    ```
    R (Programming Language):
    ```
    
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Knn Classifier Implementation in R with Caret Package](http://dataaspirant.com/2017/01/09/knn-implementation-r-using-caret-package/) by Rahul Saxena <br>

12. ### <a name="Ensemble-Methods"></a>Ensemble Methods 

    ```
    Required Reading:
    ```
    
    - Chapter 10 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) and Chapter 8 of [An Introduction to Statistical Learning: with Applications in R](http://www-bcf.usc.edu/~gareth/ISL/) <br>
        - **Exercises:** 10.1, 10.3, 10.4, and 10.5 from [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)   
    - Slide: [Ensemble Learning through Diversity Management: Theory, Algorithms, and Applications](http://staff.ustc.edu.cn/~hchen/tutorial/IJCNN2011.pdf) by Huanhuan Chen and Xin Yao    
    - Slide: [Ensemble Learning, Model selection, Statistical validation](https://web.fe.up.pt/~ec/files_1112/week_11-EnsembleLearning.pdf) by João Mendes Moreira and José Luís Borges    
    - Slide: [Bagging and Random Forests](https://davidrosenberg.github.io/mlcourse/Archive/2017/Lectures/9a.bagging-random-forests.pdf) by David Rosenberg <br>
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
    - Slide: [Introduction to Machine Learning (Boosting)](http://www.cs.huji.ac.il/~shais/Lectures2014/lecture4.pdf) by Shai Shalev-Shwartz <br>
    - Paper: [Ensemble Methods in Machine Learnin](http://web.engr.oregonstate.edu/~tgd/publications/mcs-ensembles.pdf) by Thomas G. Dietterich <br>
    - NoteBook: [AdaBoost](https://github.com/hhaji/Applied-Machine-Learning/blob/master/NoteBooks/AdaBoost.ipynb)  
    - Question: [Adaboost with a Weak Versus a Strong Learner](https://stats.stackexchange.com/questions/246820/adaboost-with-a-weak-versus-a-strong-learner) 
    
    ```
    Additional Reading:
    ```

    - Blog: [Ensemble Methods](https://www.datavedas.com/ensemble-methods/) by Rai Kapil    
    - Blog: [Ensemble Methods (Part 3): Meta-learning, Stacking and Mixture of Experts](https://www.commonlounge.com/discussion/1697ade39ac142988861daff4da7f27d) by Marta Enesco and Keshav Dhandhania    
    - Blog: [Consensus Clustering](https://towardsdatascience.com/consensus-clustering-f5d25c98eaf2) by Lance Fernando  
    - Blog: [Boosting, Bagging, and Stacking — Ensemble Methods with sklearn and mlens](https://medium.com/@rrfd/boosting-bagging-and-stacking-ensemble-methods-with-sklearn-and-mlens-a455c0c982de) by Robert R.F. DeFilippi    
        - [NoteBook](https://github.com/robertdefilippi/ensemble-bagging-boosting/blob/master/binning-bagging.ipynb)
    - NoteBook: [Introduction to Python Ensembles](https://www.dataquest.io/blog/introduction-to-ensembles/) by Sebastian Flennerhag    
    - [Library (ML-Ensemble):](http://ml-ensemble.com/docs/ensemble.html) Graph handles for deep computational graphs and ready-made ensemble classes for ensemble networks by Sebastian Flennerhag <br>
    - NoteBook: [Ensemble Methods](https://github.com/vsmolyakov/experiments_with_python/blob/master/chp01/ensemble_methods.ipynb) by Vadim Smolyakov <br>
    - Paper: [On Agnostic Boosting and Parity Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/2008-On_Agnostic_Boosting-and_Parity_Learning.pdf) by A. T. Kalai, Y. Mansour, and E. Verbin <br>  
    - Paper: [Faster Face Detection Using Convolutional Neural Networks & the Viola-Jones Algorithm](https://www.csustan.edu/sites/default/files/groups/University%20Honors%20Program/Journals/01_enriquez.pdf) by Karina Enriquez  

    ```
    R (Programming Language):
    ```
    
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Random Forests](http://uc-r.github.io/random_forests) by UC Business Analytics R Programming Guide <br>

13. ### <a name="Model-Selection-and-Validation"></a>Model Selection and Validation  

    ```
    Required Reading:
    ```
    
    - Chapter 11 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
          - **Exercises:** 11.1 and 11.2 from [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning)    
    - Blog: [What is the Difference Between a Parameter and a Hyperparameter?](https://machinelearningmastery.com/difference-between-a-parameter-and-a-hyperparameter/) by Jason Brownlee 
    - Blog: [A “short” introduction to model selection](https://towardsdatascience.com/a-short-introduction-to-model-selection-bb1bb9c73376) by David Schönleber   
    - Blog: [K-Fold and Other Cross-Validation Techniques](https://medium.com/datadriveninvestor/k-fold-and-other-cross-validation-techniques-6c03a2563f1e) by Renu Khandelwal   
    - Tutorial: [Learning Curves for Machine Learning in Python](https://www.dataquest.io/blog/learning-curves-machine-learning/) by Alex Olteanu    
            
    ```
    Suggested Reading:
    ```
    
    - NoteBook: [Split the Dataset Using Stratified K-Folds Cross-Validator](https://github.com/hhaji/Applied-Machine-Learning/blob/master/NoteBooks/Stratified-K-Folds-Cross-Validator.ipynb)
    - Blog: [Hyperparameter Tuning the Random Forest in Python](https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74) by Will Koehrsen  
        - [Jupyter NoteBook](https://github.com/WillKoehrsen/Machine-Learning-Projects/blob/master/random_forest_explained/Improving%20Random%20Forest%20Part%202.ipynb) <br>
    - Blog: [Hyperparameter Optimization: Explanation of Automatized Algorithms](http://dkopczyk.quantee.co.uk/hyperparameter-optimization/#easy-footnote-bottom-1-379) by Dawid Kopczyk <br>
        - [Code (Python):](https://github.com/dawidkopczyk/blog/blob/master/hyperparam.py)  
    - Blog: [How to Use Random Seeds Effectively](https://towardsdatascience.com/how-to-use-random-seeds-effectively-54a4cd855a79) by Jai Bansal   
    
    ```
    Additional Reading:
    ```
    
    - Blog: [Nested Cross Validation Explained](https://weina.me/nested-cross-validation/) by Weina Jin   
    - NoteBook: [Cross Validation](https://www.ritchieng.com/machine-learning-cross-validation/) by Ritchie Ng <br>
    - NoteBook: [Cross Validation With Parameter Tuning Using Grid Search](https://chrisalbon.com/machine_learning/model_evaluation/cross_validation_parameter_tuning_grid_search/) by Chris Albon<br>
    - Blog: [Random Test/Train Split is not Always Enough](http://www.win-vector.com/blog/2015/01/random-testtrain-split-is-not-always-enough/) by Win-Vector <br>
    - Slide: [Cross-Validation: What, How and Which?](https://www.humanbrainmapping.org/files/2017/ED%20Courses/Course%20Materials/Crossvalidation_Raamana_PradeepReddy.pdf) by Pradeep Reddy Raamana <br>
    - Paper: [Algorithms for Hyper-Parameter Optimization (NIPS 2011)](http://papers.nips.cc/paper/4443-algorithms-for-hyper-parameter-optimization.pdf) by J. Bergstra, R. Bardenet,Y. Bengio, and B. Kégl <br>
    - Library: [Yellowbrick (Machine Learning Visualization)](https://www.scikit-yb.org/en/latest/index.html)
        - [Learning Curve](https://www.scikit-yb.org/en/latest/api/model_selection/learning_curve.html)
        - [Validation Curve](https://www.scikit-yb.org/en/latest/api/model_selection/validation_curve.html)
        - [Double Descent](https://medium.com/mlearning-ai/double-descent-8f92dfdc442f#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6IjAzMmIyZWYzZDJjMjgwNjE1N2Y4YTliOWY0ZWY3Nzk4MzRmODVhZGEiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJuYmYiOjE2MzY4MTg1MTIsImF1ZCI6IjIxNjI5NjAzNTgzNC1rMWs2cWUwNjBzMnRwMmEyamFtNGxqZGNtczAwc3R0Zy5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsInN1YiI6IjExMTQyMDY5ODY4MzQ3MDc5Nzk2MCIsImVtYWlsIjoiaGhoYWppQGdtYWlsLmNvbSIsImVtYWlsX3ZlcmlmaWVkIjp0cnVlLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJuYW1lIjoiSGFuaXRhIEhhamlhYm9saGFzc2FuIiwicGljdHVyZSI6Imh0dHBzOi8vbGgzLmdvb2dsZXVzZXJjb250ZW50LmNvbS9hLS9BT2gxNEdqLUVCRlZxWHVkVVJrRUZMMmg2N0ZmYjgzQ1Z5aU9sRkNXX2plV01BPXM5Ni1jIiwiZ2l2ZW5fbmFtZSI6Ikhhbml0YSIsImZhbWlseV9uYW1lIjoiSGFqaWFib2xoYXNzYW4iLCJpYXQiOjE2MzY4MTg4MTIsImV4cCI6MTYzNjgyMjQxMiwianRpIjoiYjkwYzgxMTUyZjExYzI1ZDc0OTlmNGQ0YWE1NWYzOTBmYWMwODg3YyJ9.wblR52En-lt6rc__BTvddXHRevSL8eFvOqoZ3gSZDFUeJaM-eOREXgzrl2_OqzkgJHA_b7KYMcTPguLC25RJ7Xkc9rYqEnnZUqK2j_CTBNN260KKDVmoenxmA3fPiz3efHXI7WwNsOzjJrusgPZmHROdt3thYxmIjBg896g9p9rQoJ6ETZdGZp0KGGTXB_-bRTDqgcycMMcwOtQ68y33f7gwAXfYF1tQYFmBO5eIl-FC2hP_l4DVWHmmtwUOCKEYY_z3AwUBIqQB3fEZawjNQxekJ74-pp9KLBWf_K_rmG8Ek7QC4JDMgBQdEqg7smS7756XSzMWCV4zl4L_EIi5aQ) by Arjun Ahuja   
        - [Deep Double Descent](https://openai.com/blog/deep-double-descent/) by Preetum Nakkiran, Gal Kaplun, Yamini Bansal, Tristan Yang, Boaz Barak, and Ilya Sutskever  
      
    ```
    R (Programming Language):
    ```
    
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Resampling Methods](http://uc-r.github.io/resampling_methods) by UC Business Analytics R Programming Guide <br>
    * Blog: [Linear Model Selection](http://uc-r.github.io/model_selection) by UC Business Analytics R Programming Guide <br>
 
14. ### <a name="Neural-Networks"></a>Neural Networks   

    ```
    Required Reading:
    ```
    
    - Chapter 20 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
    - Slide: [Neural Networks](https://www.cs.huji.ac.il/~shais/Lectures2014/lecture10.pdf) by Shai Shalev-Shwartz <br>
    - Blog: [7 Types of Neural Network Activation Functions: How to Choose?](https://missinglink.ai/guides/neural-network-concepts/7-types-neural-network-activation-functions-right/) <br>
    - Blog: [Activation Functions](https://ml-cheatsheet.readthedocs.io/en/latest/activation_functions.html#id5)
    - Blog: [Back-Propagation, an Introduction](https://www.offconvex.org/2016/12/20/backprop/) by Sanjeev Arora and Tengyu Ma <br>
 
    ```
    Additional Reading:
    ```
    
    - Blog: [The Gradient](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/partial-derivative-and-gradient-articles/a/the-gradient) by Khanacademy <br>
    - Blog: [Activation Functions](https://towardsdatascience.com/activation-functions-b63185778794) by Dhaval Dholakia <br>
    - Paper: [Why Does Deep & Cheap Learning Work So Well?](https://arxiv.org/pdf/1608.08225.pdf) by Henry W. Lin, Max Tegmark, and David Rolnick <br>
    - Slide: [Basics of Neural Networks](http://www.connellybarnes.com/work/class/2016/deep_learning_graphics/03_neural_net_basics.pdf) by Connelly Barnes <br> 
 
    ```
    R (Programming Language):
    ```
    
    * Blog: [Classification Artificial Neural Network](http://uc-r.github.io/ann_classification) by UC Business Analytics R Programming Guide <br>
 
15. ### <a name="CLP"></a>Convex Learning Problems   

    ```
    Required Reading:
    ```
    
    - Chapter 12 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
 
    ```
    Additional Reading:
    ```
    - Blog: [Escaping from Saddle Points](https://www.offconvex.org/2016/03/22/saddlepoints/) by Rong Ge <br>
 
16. ### <a name="Regularization-and-Stability"></a>Regularization and Stability   

    ```
    Required Reading:
    ```
    
    - Chapter 13 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
    - Slide: [Machine Learning](https://github.com/rkwitt/teaching/blob/master/SS17/ML/VO/ml.pdf) by Roland Kwitt <br>
    - Blog: [L1 and L2 Regularization](https://medium.com/datadriveninvestor/l1-l2-regularization-7f1b4fe948f2) by Renu Khandelwal <br>
    - Blog: [L1 Norm Regularization and Sparsity Explained for Dummies](https://medium.com/mlreview/l1-norm-regularization-and-sparsity-explained-for-dummies-5b0e4be3938a) by Shi Yan <br>
 
    ```
    Additional Resources:
    ```
    
    - NoteBook: [Regularization](https://github.com/ethen8181/machine-learning/blob/master/regularization/regularization.ipynb) by Ethen <br>
 
    ```
    R (Programming Language):
    ```
    
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Regularized Regression](http://uc-r.github.io/regularized_regression) by UC Business Analytics R Programming Guide <br>
 
17. ### <a name="Support-Vector-Machines"></a>Support Vector Machines   

    ```
    Required Reading:
    ```
    
    - Chapter 15 of [Understanding Machine Learning: From Theory to Algorithms](http://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning) <br>
    - Slide: [Support Vector Machines and Kernel Methods](https://www.cs.huji.ac.il/~shais/Lectures2014/lecture8.pdf) by Shai Shalev-Shwartz <br>
    - Blog: [Understanding the Mathematics behind Support Vector Machines](https://heartbeat.fritz.ai/understanding-the-mathematics-behind-support-vector-machines-5e20243d64d5) by Nikita Sharma    
  
    ```
    Additional Reading:
    ```
    - Infographic: [Support Vector Machines (100 Days Of ML Code)](https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Info-graphs/Day%2012.jpg) by Avik Jain <br>
        - [Markdown (NoteBook)](https://github.com/Avik-Jain/100-Days-Of-ML-Code/blob/master/Code/Day%2013%20SVM.md)
     
    ```
    R (Programming Language):
    ```
    
    * Book: [Machine Learning Mastery With R](https://machinelearningmastery.com/machine-learning-with-r/) by Jason Brownlee <br>
    * Blog: [Support Vector Machine Classifier Implementation in R with Caret Package](http://dataaspirant.com/2017/01/19/support-vector-machine-classifier-implementation-r-caret-package/) by Rahul Saxena <br>
    * Blog: [Support Vector Machine](http://uc-r.github.io/svm) by UC Business Analytics R Programming Guide <br>
    
18. ### <a name="Multiclass-Classification"></a>Multiclass Classification   

    ```
    Required Reading:
    ```
    
    - Chapter 17 of [Understanding Machine Learning: From Theory to Algorithms]
    - Slide: [Machine Learning Basics Lecture 7: Multiclass Classification](https://www.cs.princeton.edu/courses/archive/spring16/cos495/slides/ML_basics_lecture7_multiclass.pdf) by Yingyu Liang   
      
- ### <a name="Additional-NoteBooks-and-Slides"></a>Additional NoteBooks and Slides: 
  * Course: [Fondations of Machine Learning](https://bloomberg.github.io/foml/#home) by David S. Rosenberg <br>
  * [Python Machine Learning Book Code Repository](https://github.com/rasbt/python-machine-learning-book) <br>
  * [Dive into Machine Learning](https://github.com/hangtwenty/dive-into-machine-learning) <br>
  * [Python code for "An Introduction to Statistical Learning with Applications in R"](https://github.com/JWarmenhoven/ISLR-python) by Jordi Warmenhoven <br>
  * [iPython-NoteBooks](https://github.com/jdwittenauer/ipython-notebooks) by John Wittenauer <br>
  * [Scikit-Learn Tutorial](https://github.com/jakevdp/sklearn_tutorial) by Jake Vanderplas <br>
  * [Data Science Roadmap](https://github.com/estraviz/data-science-roadmap#4-machine-learning-back-to-top-) by Javier Estraviz <br>

## <a name="Class-Time-and-Location"></a>Class Time and Location:
Saturday, Monday, Wednesday 10:30-12:00 PM

### <a name="MTA"></a>Recitation and Assignments:
Monday and Wednesday 17:00-18:30 PM 
Refer to the following [link](https://github.com/hhaji/Applied-Machine-Learning/tree/master/Recitation-Assignments) to check the assignments.    
Also, I recommend to study [link](https://github.com/hhaji/Applied-Machine-Learning/blob/master/Recitation-Assignments/README2020.md) of recitation and assignments of machine learning in 2020. 

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

### <a name="Practical-Guide"></a>Practical Guide:
* Slide: [Practical Advice for Building Machine Learning Applications](https://svivek.com/teaching/machine-learning/fall2018/slides/practical/advice.pdf) by Vivek Srikumar <br>
* Blog: [Comparison of Machine Learning Models](https://github.com/justmarkham/DAT8/blob/master/other/model_comparison.md) by Kevin Markham <br>

### <a name="Fascinating-Guide-For-Machine-Learning"></a>Fascinating Guide to Use Python Libraries (Machine Learning):
* [Technical Notes On Using Data Science & Artificial Intelligence: To Fight For Something That Matters](https://chrisalbon.com) by Chris Albon

### <a name="Google-Colab"></a>Google Colab:
[Google Colab](https://colab.research.google.com) is a free cloud service and it supports free GPU!
  - [How to Use Google Colab](https://www.geeksforgeeks.org/how-to-use-google-colab/) by Souvik Mandal 
  - [Primer for Learning Google Colab](https://medium.com/dair-ai/primer-for-learning-google-colab-bb4cabca5dd6)
  - [Deep Learning Development with Google Colab, TensorFlow, Keras & PyTorch](https://www.kdnuggets.com/2018/02/google-colab-free-gpu-tutorial-tensorflow-keras-pytorch.html)

### <a name="Latex"></a>Latex:
The students can include mathematical notation within markdown cells using LaTeX in their **[Jupyter Notebooks](http://jupyter.org)**.<br>
  - A Brief Introduction to LaTeX [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/latex.pdf)  <br>
  - Math in LaTeX [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/math.pdf) <br>
  - Sample Document [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/sample.pdf) <br>

### <a name="Useful-NoteBooks"></a>Useful NoteBooks:
* [Preparing and Cleaning Data for Machine Learning](https://www.dataquest.io/blog/machine-learning-preparing-data/) by Josh Devlin
* [Getting Started with Kaggle: House Prices Competition](https://www.dataquest.io/blog/kaggle-getting-started/) by Adam Massachi 
* [Scikit-learn Tutorial: Machine Learning in Python](https://www.dataquest.io/blog/sci-kit-learn-tutorial/) by Satyabrata Pal 

## <a name="Grading"></a>Grading:
* Homework – 30% <br>
— Will consist of mathematical problems and/or programming assignments.
* Midterm – 20%
* Endterm – 50%

### <a name="Two-Written-Exams"></a>Three Written Exams:
Midterm Examination: Saturday 1400/08/27, 10:30-12:00   
Final Examination:  Thursday 1400/11/07, 14:00-16:00   

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
