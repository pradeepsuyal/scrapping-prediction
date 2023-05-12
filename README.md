![Apache License](https://img.shields.io/hexpm/l/apa)  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  [![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png) ![medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white) ![coursera](https://img.shields.io/badge/Coursera-0056D2?style=for-the-badge&logo=Coursera&logoColor=white)

## Scrapping with BeautifulSoup and prediction with NLP
## Acknowledgements

 - [python for ML and Data science, udemy](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass)
 - [ML by Stanford University ](https://www.coursera.org/learn/machine-learning)

## Appendix

* [Aim](#aim)
* [Dataset used](#data)
* [Run Locally](#run)
* [Exploring the Data](#viz)
   - [Matplotlib](#matplotlib)
* [feature engineering](#fe)
* [conclusion](#conclusion)

## AIM:<a name="aim"></a>

Need to scrap the data from a blog site and then using NLP technique to find num_of_complex_word, POSITIVE SCORE,	NEGATIVE SCORE	POLARITY SCORE, SUBJECTIVITY SCORE and various attributes from different blog posts. 

## Dataset Used:<a name="data"></a>

`provided an input data with various links redirecting to the blog post so that we can scrap the data from that link to make predictions`

## Run locally:<a name="run"></a>

Clone the project

```bash
  git clone https://github.com/pradeepsuyal/scarpping-prediction
```

Go to the project directory

```bash
  cd scrapping-prediction
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

## Exploring the Data:<a name="viz"></a>

I have used pandas, matplotlib and seaborn visualization skills.

**Matplotlib:**<a name="matplotlib"></a>
--------
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.You can draw up all sorts of charts(such as Bar Graph, Pie Chart, Box Plot, Histogram. Subplots ,Scatter Plot and many more) and visualization using matplotlib.

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install matplotlib:

    pip: pip install matplotlib

    anaconda: conda install matplotlib
    
    import matplotlib.pyplot as plt

![matplotlib](https://eli.thegreenplace.net/images/2016/animline.gif)

for more information you can refer to [matplotlib](https://matplotlib.org/) official site

## My approaches on Feature Engineering<a name="fe"></a>
-------

* scarpped heading, sub-heading and text from the posts.
* use Natural Language to implement technique such as stop words, tokenize words, sentiment intensity analyzer, etc.
* saved the prediction in an excel file.


## Conclusion<a name="conclusion"></a>
---------
I have used various Natural lnaguage processing technique to discover sentiment score, polarity score and diffent aspects from various posts.

