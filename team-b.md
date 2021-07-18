<!-- Headings -->
![markdown logo](https://technocolabs.tech/assets/img/logo1.png)
# *TECHNOCOLABS DATA ANALYSIS INTERNSHIP **PROJECT REPORT***
<br>

![markdown logo](https://digital.hbs.edu/platform-digit/wp-content/uploads/sites/2/2019/02/LC-Logo-Official-min.png)
# __Capstone Project- Lending Club__
<h1 style="color:blue;">Introduction</h1>
<p><a href = "https://www.lendingclub.com/">"LendingClub</a> is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform."  <a href ="https://en.wikipedia.org/wiki/LendingClub">  Wikipedia-Lending club</a>
​<br>
On the LendingClub platform, people invest on other people loan through an online secured system. On these types of platforms, in the most cases, the main criteria of giving loans to costumers is solely based on their credit scores, so that a customer with lower credit score (more risky) get higher rate and customer with higher credit score (less risky) get lower interest rate for their loan. Obviously, from the investor point of view, the loans with higher interest rate are more attractive due to their higher return of investment. However, it also has high risk of being not returned at all.
<br>
So, investing on "Bad loans" or charged-off, which means you loose your asset, is more worse than loosing an opportunity to gain more profit.
<br> 
The machine learning/deep learning model that could predict which of the high interest loans are more likely to be returned, would bring added value by minimizing the associated risks. Also, using other factors along with credit score may help us to identify the high risky loans and minimize the investors loss of money more accurately.</p>
 <h1 style="color:blue;">Problem statement</h1>
<p>In the last few years, applying for different types of loans through online peer-to-peer lending platforms such as the LendingClub is raising.</p>
<h1 style="color:blue;">Objective</h1>
<p>
<mark>1. First is to try to find a better prediction model to prevent investing on '"bad loans".</mark> To do that, First, going to implement some data engineering and preprocessing on LendingClub dataset to prepare data for analysis and modeling.
<br>
<mark>2. Second, need to apply explanatory data analysis (EDA) to investigate the features.</mark>
<br>
<mark>
3. Preprocessed data on LendingClub loans labeled on whether or not the borrower defaulted (charged-off) to develop a model and predict whether or not a borrower will pay back their loan.</mark> This way in the future when we get a new potential customer who assigned with higher interest loan, we can assess whether or not they are likely to pay back the loan.
</p>
<hr>

<h1 style="color:blue;">Dataset</h1>
<p>
We used LendigClub Dataset possessing almost all features including FICO scores. This dataset contains more than several millions data and because, here, We only use a normal laptop to analyze and model this dataset, thus, We only selected the loans issued in 2018 (almost 0.5 million data) to reduce the processing time.
<br>
<br>
Moreover, some of the features in this dataset are only relevant after loans are issued and thus, not available at the moment of investing. For this reason, We used features list from here that are available and visible to investors before issuing a loan. To match this feature list to the main dataset, We did some simple and primary cleaning, whitespace removing, and spell corrections using dropping and “regular expression” technique. Also, it requires to check the unmatched features to see if some of them could be matched manually.
<br>
<h1 style="color:blue;">Data Set Link:</h1>
<p11><a href="https://www.kaggle.com/wordsforthewise/lending-club/download">Kagle: your home for data science</a><p11>




