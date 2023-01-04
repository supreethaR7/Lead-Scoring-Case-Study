# Lead-Scoring-Case-Study


BUSINESS PROBLEM:


About Company and its sales Process:
   a.  An education company named X Education sells online courses to industry professionals.
   b.  The company markets its courses on several websites and search engines like Google.
   c.  Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos.
   d.  When these people fill up a form providing their email address or phone number, they are classified to be a lead.
   e.  Moreover, the company also gets leads through past referrals.
   f.  Once these leads are acquired, employees from the sales team start making calls, writing emails, etc.
   g.  Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.


Challenges for a company:
    a.  Now, although X Education gets a lot of leads, its lead conversion rate is very poor beacuse with limited time, they are not able to focus more on the potential customers.
    b.  The company wishes to identify the most potential leads, also known as ‘Hot Leads’.
    c.  If they successfully identify this set of leads, the lead conversion rate should go up.
    d.  As the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.
    e.  X Education wants to select the most promising leads, i.e. the leads that are most likely to convert into paying customers.


Company's Requirement:
    The company requires a prediction model wherein a value to be assigned to each of the leads, called lead scores, such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

Goals of the Case Study:
There are quite a few goals for this case study:

  1.  Needs to build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

  2.  There are some more problems presented by the company which this model should be able to adjust to if the company's requirement changes in the future so the predictive model should also able to handle those problems as well.

Steps Involved

  1.  Loading Required Liabraries

  2.  Setting View Options

  3.  Read Data Dictionary

  4.  Read and Understand the Data

  5.  Exploratory Data Analysis

        A. Univariate Analysis
    a. Data Cleaning and Sanity Checks
    b. Dropped columns based on number of unique values
    c. Dropped Columns unrelated to studies.
    d. Understand Target Varaible
    e. Missing value Treatment
    f. Count plot and Coversion rate plot
    g. Countplot for each Categorical Feature
    h. Outliers Treatment
    i. Distribution PLot: Contnious plot
    j. Capping and Trimming 2) Boxen PLot
    h. Capping and Trimming
    
        B. Bivariate Analysis
   a. Stacked Bar chart: Conversion Rate
   b. Correlation using chi-square between categorical Variable.
   c.  Heatmap CramersV: Correlation within Nominal Varaible
    
        C. Multivariate Analysis
   a. Heat Map Correlation Chart
   b. Pair Plot
    
 6. Modeling

A.  Data Preparation for modeling

   a. Create Dummy Varaibles
   b.Train Test Split
   c. Stndard Scaling
   
B.  Feature Elimination

   a.Check for Multicollinearity: Vif
   b.RFE
   
C. Making Models

    a. statsmodels.api.GLM
    b. Logistic Regression
    c. optimal cutoff
    d. roc
    e. precision recall trade off
    f. Model Evaluation
    g. Model Scores
    h. Ks statisatics and lift plot
    i. Cross validation scores
    j. Test Predictions and Evalusation
    k. Compares resilts for each Model

D. Relative information of final Parameters

E. Lead score bw 0-100 for each lead.

F. Final suggestion and insights
