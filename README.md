![Home page](https://github.com/sanilrod/default-of-credit-card/blob/main/Img/Cover.png?raw=true "Main Page")

<br>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#ABSTRACT">Abstract</a> </li>
    <li><a href="#INTRODUCTION">Introduction</a></li>
    <li> <a href="#Tech Stack">Tech Stack</a> </li>
    <li><a href="#Prerequisites and Running Notebooks">Prerequisites and Running Notebooks</a></li>
    <li><a href="#Algorithms Used">Algorithms Used</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## ABSTRACT
<p align="justify"> Ability to distinguish reliable and unreliable clients has a significant impact on future financial stability of financial institutions and for this reason each aspect of the portfolio of potential clients is thoroughly analyzed before making a decision for providing credit. This project is aimed at building a classification supervised machine learning model to identify the credibility of the client based on the client's personal factors and prior payment history. Exploratory data analysis and data preprocessing was conducted to build four classification models: Naive Bayes, Logistic Regression, Decision Tree and Support Vector Machine.</p>

<br>


### INTRODUCTION
<p align="justify">Living in a modern world and being affected by social media and influencers has given way to consumerism and people's desire to spend money on goods and services. While all people aim to live their best lives, not all have sufficient funds to support this kind of life. Living from pay check to pay check does not provide flexibility to people to consume goods they want within such days. Financial institutions have provided people freedom in their consumption by allowing them to lend a certain amount of money for a specific period but protect themselves by imposing interest rates and influencing a borrower's reputation (credit score). Despite the protection methods being used, there are still customers who do not evaluate their purchasing power objectively or encounter challenging financial situations, which eventually result in the inability to repay the money lent and the default of their credit cards.</p>

<P align="justify">Taiwan's credit card and cash card debt reached $268 billion USD in February 2006. More than 500,000 borrowers were unable to make their loan payments. They were referred to as "credit card slaves" in Taiwan, a term used to describe people who could only make the minimum payment on their credit card debt each month. This problem caused significant societal issues. Due to debt, some borrowers and their families committed suicide, others lost their homes to foreclosure, and others could not afford their children's college tuition. Some credit card-enslaved people sold illegal drugs to pay back the banks. Lenders, particularly those in lower income groups, came under additional pressure due to some banks' violent and threatening collection practices.</p>

<p align="justify">The default of one credit card may not be an issue for banking institutions, but the insolvency of many customers may result in the bankruptcy of the company itself. In order for a financial institution to protect itself from a high rate of default, it analyzes the portfolio of potential borrowers to evaluate its ability to be a credible borrower and being able to repay the credit within the deadline provided. Our goal of this project is, by analyzing factors that may contribute to the result of default or not default of credit cards, build a model that assesses the probability of credit card result in default. Some of the questions that we would like to answer in our project:</p>

1) Which model is the best for predicting the probability of credit card default?<br>
2) What factors are more significant in identifying non-credible customers?<br>

<br>

### TECH STACK

* [Python](https://www.python.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Plotly](https://plotly.com/python/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/doc/stable/index.html)
* [Scipy](https://scipy.org/)
* [Tqdm](https://tqdm.github.io/)


<br>

<!-- GETTING STARTED -->
## Getting Started

Instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

<br>

### Prerequisites and Running Notebook

1. Open Jypyter Notebook using
2. Install Prerequisite Libraries

This are libraries you need to  install them. 
  ```sh
  pip install -r requirements.txt
  ```

3. Read the Dataset(.CSV) file
4. Hit Run All!!!


<br>


### Algorithms Used


<h3><b>1. Logistic Regression<b></h3>

<p align="justify">Establishing a relationship between input features (independent variables) and output features (dependent variables), typically categorical variables that require classification, is the primary goal of logistic regression.</p>

  

<br>
  
  
  
<h3><b>2. Naive Bayes<b></h3>
  
<p align="justify"> Naive Bayes is a classification model that classifies new record based on probability of appearance of a predictor given specific class. The only assumption of this model is the independence of predictors. Naive Bayes can be implemented for different types of variables using different probability functions.</p>
 
  
  
<br>
  
  
  
<h3><b>3. Decision Tree<b></h3>
  
<p align="justify"> Using non-parametric supervised learning, decision trees are used for classification and regression. The objective is to develop a model that, through learning, can predict the value of a target variable. The decision rules derived from the characteristics of the data. The fundamental unit of the decision tree is the node. </p>
 
  
  
<br>
  
<h3><b>Model Comparison<b></h3>
  
  
 <img src="https://github.com/sanilrod/default-of-credit-card/blob/main/Img/Comparison.png" width=100% height=100%>
  
  
  
<br>
  
<h3><b>Models’ Performance Evaluation Summary Table<b></h3>
  
  
 <img src="https://github.com/sanilrod/default-of-credit-card/blob/main/Img/Table.png" width=100% height=100%>
  
  
  <br>
  
 

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<br>
<br>
<br>


<h3 align="center"><b>Developed with :heart: by <a href="https://www.linkedin.com/in/zhibek-kassymkanova/"> Zhibek </a>, <a href="https://www.linkedin.com/in/shaarushi/"> Aarushi </a>, <a href="https://www.linkedin.com/in/sanil-rodrigues/"> Sanil </a>, <a href="https://www.linkedin.com/in/abhiram-desai-2119271b3/">Abhiram </a>.</b></h1>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png

