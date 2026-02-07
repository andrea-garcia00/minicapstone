# #regression | Minerva University


> Source: [https://my.minerva.edu/academics/hc-resources/hc-handbook/regression/](https://my.minerva.edu/academics/hc-resources/hc-handbook/regression/)


## #regression

**Please fill out this Google Form to submit suggestions for this page (i.e. typos, study guide contributions, useful applications, etc.). We are actively seeking feedback on anything big or small to make the HC Handbook as useful as possible.**

Taking the “line of best fit” to new powerful levels.

Regression is a statistical method that allows one to estimate the average value of the dependent (or “response”) variable conditional on one or more independent (or “predictor”) variables. A regression function is formulated for this purpose and represents a model for the relationship between the variables. The strength of the relationship (the extent to which the model can be used for prediction) is quantified by the coefficient of determination, more commonly known as R-squared. This quantity indicates how much of the variability in the dependent variable can be explained by the regression model. Multiple regression enables one to make predictions about the response variable conditional on values of more than one predictor variable, and make inferences about the relationship between a single predictor and the outcome variable when holding all other predictors constant. Regression analyses are most often used to make predictions and to classify or categorize information, but one should be cautious about using regression to infer causal relationships.

Foundational Concept | Formal Analyses | Thinking Critically | Analyzing Data

**Class:** Formal Analyses | Semester One

**Unit:** Probability and Statistics

**Big Question:** What does it mean to be random? & How can data help us discover what is true?

You are a public health consultant striving to combat child obesity by changing policies in high schools across the country. To determine how to allocate your resources, you wish to find the variables that are the strongest predictors of body mass index (BMI), a numerical measure that can indicate obesity, derived from one’s height and weight. You have considerable amounts of historical data at your disposal. As a first step, you investigate how well BMI (dependent variable) can be predicted from the time spent exercising (independent variable) for your target population. You create a simple linear model and find that the coefficient of determination (R-squared), indicating the amount of variation in BMI explained by the variation in exercise, is 0.4. Thus, the predictive strength of your simple model is not so convincing, leading you to explore more variables. In addition to exercise, you extend the model to include other predictor variables, including the intake of carbohydrates, protein, and fiber. The revised model has an increased R-squared of 0.89. You also examine the regression coefficients which, for a given variable, indicate the expected change in BMI per unit change in the selected variable, holding all other predictors constant. Comparing these coefficients, you note that carbohydrate intake has by far the largest influence on BMI, with time spent exercising being second most important. Further examination of the relationships between the independent variables reveals strong multicollinearity between carbs, protein and fiber intake, leading you to realize that you can ignore the least helpful variables (protein and fiber intake) and still predict BMI with reasonable accuracy. While these findings may not indicate a causal connection, the relationships are compelling enough to help you decide how to invest your resources: provide more low-carb alternatives in school cafeterias and invest in programs involving youth fitness, physical education, and athletics.

***Footnote:*** *Two regression models, one simple and one multivariate, are compared based on their explanatory power, quantified by R-squared. The most impactful predictors of BMI are revealed by interpreting the coefficients in the regression equation and the relationship among predictors, allowing for an appropriate allocation of resources.*

Is #regression the right HC? If the answer to the following questions is yes, #regression could be useful:

1. Are you constructing a regression equation or function to describe the relationship between variables?
2. Are you using a line or curve of best fit to describe trends between variables in a dataset?
3. Are you interpreting a regression model, including the parameters of the regression function and the coefficient of determination?
4. Are you utilizing a regression model for prediction?

Depending on the work product, there might be other HCs to consider. ….

The following HC might apply if the work:

Try answering the questions on your own before checking the example answers.

What is a predictor and a response variable?

What is a residual?

What is a least-squares regression line?

What are the conditions or assumptions needed to validate a simple linear regression equation? How does one evaluate them?

What are the parameters of the least squares regression line and what do they tell you? For example, suppose that we have a regression equation to predict the top running speed of a cat, s, in km/h from its body mass, m, in kg: s = -2.2m + 35. What do the parameter values -2.2 and 35 mean?

Explain how to interpret R-squared, the “coefficient of determination.”

How can regression equations be used for predictions?

How can regression equations be used for inference?

What are some limitations of using regression models for predictions?

What quantity does a simple linear regression equation minimize? What is this quantity? How does this relate to R-squared, the “coefficient of determination”?

Explain what is needed when conducting multiple regression, compared to a simple bi-variable regression.

What are some methods to find the best multiple regression model?

Why do we need to be cautious about multicollinearity and overfitting in multiple regression models? How do we identify them?

Why might one use a nonlinear regression model? What would such a model look like?

For **more** practice with this HC, refer to the exercises suggested in the Formal Analyses study guides. See the key resources for sources of practice questions.

- Have you clearly outlined your process of constructing the regression model?

- Have you evaluated whether the conditions needed to validate the regression model are satisfied?

- Have you stated any assumptions that are needed for using the regression model and explained the impacts of those assumptions?

- Have you correctly interpreted what the regression equation means in your context, including explaining the interpretation of parameter values of the equation (e.g., slope and intercept)?

- Have you correctly quantified and interpreted the strength of the regression model (e.g., R-squared) in a way that’s relevant to your specific context?

- Have you explained the usefulness and limitations of your model regarding prediction and/or inference that are relevant to your purpose?

- Have you effectively utilized data visualizations (e.g., scatter plots, residual distributions) to support your analysis?

- An inappropriate regression model is used for the context.

- The regression equation is calculated or interpreted with incorrect or unidentified units for the variables.

- The application does not sufficiently evaluate whether the conditions for using the regression equation are satisfied.

- The application provides interpretations that simply restate definitions rather than truly applying them to the variables and context under study.

- The application does not sufficiently describe the usefulness of the regression model and how it serves the purpose of the work.

- The application neglects to identify limitations of the regression model, possibly overlooking common issues such as overfitting, multicollinearity, or extraneous variables.

- The application falsely assumes a causal relationship based on the regression model.

- The application extrapolates the regression model beyond the range of observed data without sufficient justification.

This HC is introduced in Formal Analyses by focusing on simple linear regression and multiple linear regression, however, there are many other types of regression models, and all of them require the basic principles of #regression! For example, there are various types of nonlinear regression models and several different classes of regression for working with different types of variables. The choice will depend on the variables involved and the purpose of the model. Each type of model comes with its own benefits, assumptions, and limitations.

Generally speaking, this HC can be relevant in both interpreting regression results and using regression in prediction or causal inference. Regression analysis is used across many fields from social sciences to machine learning. In general, regression analysis can be used in 4 different contexts:

- Prediction: Even though simple, many data science experts believe that regression models fit in the description of machine learning methods. A simple regression model learns the behavior of a system by finding the parameters. Using training data, a regression model can learn to predict the outcome variable (dependent variable) using the explanatory variables (independent variables).

- Classification: A special form of regression model, called logistic regression, can be used in classification. You can think of a classification problem when the outcome variable is binary, or in general, categorical.

- Causal inference using observational data: In causal inference, one of the ways we can find the causal effect of the treatment variable on the outcome variable is to control for other variables. This task can be simply done using regression models. In the context of causal inference, if we properly control for confounding variables, the coefficient on the treatment variable gives us the causal effect of the treatment variable on the outcome.

- Causal inference using randomized experiments: You may think that in randomized experiments we do not really need to use regression analysis to capture the treatment effect because we do not have to worry about confounding bias. However, you will be surprised to know that even in randomized settings, especially in small sample sizes, the treatment and control groups often end up being imbalanced when it comes to the covariates. This means that the distributions of the covariates across control and treatment groups are often not similar. In this case, a simple linear regression that comprises the treatment variable and the unbalanced confounders on the right-hand side of the regression should help improve the imbalances.

- The statistical modeling course explores how regression can be used in the settings mentioned above, particularly focusing on regression as a prediction technique. For instance, imagine you want to predict your performance at a course at Minerva. You want to be able to somehow predict your final grade using certain information such as hours of study per week, your performance in prerequisite courses, and the total number of absences. To perform such analysis, you first need to “train” your regression model. You need to collect data on previous students who took the same course and given that you know their overall score in the course, you can find the coefficients for each of the variables above. Something like this:\_Final grade = 0.05 \* Hours of study per week + 0.9 \* Grade in a pre-requisite course - 0.03 \* Number of absences_This function is simply a linear regression model! Now, to predict your own final grade, you can insert the information pertaining to you and find the predicted score.

- This HC is also extensively discussed in econometrics, in which regression models are used for causal inference. This course explores regression models with different types of outcomes (logistic, regression with count data, multinomial logit, ordered probit), as well as regression models with nonlinear terms (logarithmic, quadratic, cubic, and interaction terms). Constructing and interpreting such advanced models requires extra care. In particular, it’s important to understand the assumptions that have to be met for regression results to be valid such as normality, no-multicolinearity, and no-autocorrelation assumptions.

- In finance, students may explore the Capital Asset Pricing Model (CAPM) model, which is used to project the expected returns for a stock in terms of its risk, commonly used to evaluate whether a stock is fairly valued. It’s a simple linear regression model, ERi = Rf + ꞵi(ERm - Rf), where ERi  is the expected return on investment, Rf is the risk-free rate, ꞵi is the beta coefficient of the investment (which captures the asset's sensitivity to non-diversifiable risk), and ERm is the market risk premium. The principles of #regression can help us understand the uses and limitations of this model. This model can be useful to determine if a stock is fairly valued relative to risk in simplified scenarios, but it’s important to understand the idealized assumptions about the market and the investor that limit its real-world applicability.

Are you trying to make a prediction or classification? If so, one of the simplest approaches to start with is regression. A regression analysis will use training data to predict/classify the outcome in the test set. Regression analysis is usually preferred to more complicated models because they are simple to interpret and they are less likely to fall into the overfitting trap. Here are some specific use cases:

- Imagine your role as a data scientist at your company is to estimate how much you should compensate employees for their ride shares. You can use a regression model that includes variables such as distance, time of the day, weather conditions, Uber vs. Lyft, or any other relevant variables. You use prior data to train a model that predicts the price of a ride based on these characteristics. Now you can use this model on the employees’ data (given that you know when they usually use ride share, the distance between their home and work, etc.) to be able to predict fares for each employee and eventually estimate the total compensation that should be allocated in the company’s budget.

- Imagine a medical study in which you as the researcher are interested in finding the effect of sleep apnea on memory in a group of 1,000 patients. You are given data on patients' characteristics such as gender, age, race, other conditions, and whether they have apnea or not. You also have patients' scores from a memory test done at your lab. First off, this is a causal study since you clearly have a treatment variable (having apnea or not) and an outcome variable (memory performance). Since your study uses observation data, it likely suffers from confounding bias. If you think the set of variables above is enough to get rid of confounding bias, you can use a regression model and control for these variables. The resulting coefficient on the variable apnea should give you the effect of having apnea on memory performance.

- Regression is used in machine learning, especially supervised learning. Depending on the types of variables you are dealing with, different regression models should be employed. For example, if the dependent variable is continuous and the resulting model has collinearity, then you might opt for the ridge, lasso, or elastic net regression models (SSLA, n.d.).

- Logistic regression is a commonly used type of regression in which the dependent variable is binary (a dummy variable with two levels/classes). The model outputs the probability of the outcome being in one of the levels. An example is text classification applications, such as toxic speech detection, topic classification, or email sorting. Text data are preprocessed to be suitable for logistic regression beforehand.

- This HC is likely to be useful in any scientific research context, even studying African wildlife! This example is adapted from an M25’s summer research project that aimed to study the impact of a new porous fence model on a wildlife reserve. The main purpose of the fence is to safely enclose black rhinos to ensure their security and improve ease of monitoring, but it can have impacts on other species in the region too, and studying these impacts is important to inform decisions about fence features and placement. In this study, a logistic regression model was developed with the underlying question: what behaviors predict an animal’s probability of crossing the fence, given they are observed near it? A logistic regression model was most appropriate given that crossing behavior can be measured as a binary variable: did the animal cross the fence or not? Predictor variables, measured using camera traps, included factors related to animals’ motion and activities and the distance to the nearest settlements. Analyzing the multicollinearity and statistical significance of the predictors can help identify the most important factors for predicting crossing behavior. From this analysis, we can visualize the relationship between the probability that an animal will cross the fence and the predictor variables, as depicted in the image below.

  ![Population Standard Deviation](https://www.dropbox.com/scl/fi/782gor4xkpljaz3peml0v/regression1.png?rlkey=3xeq1fld5619wu5xacyb3il3r&raw=1)
  

- Terrana, A. (2020, Dec). Inference for the Population Slope in Linear Regression. Minerva University. https://my.minerva.edu/academics/hc-resources/cornerstone-custom-hc-guides/

  - Why/use: This paper outlines the steps to perform tests of statistical significance and construct confidence intervals for simple linear regression. It also contains practice questions at the end to test your understanding.

- Diez, D., Cetinkaya-Rundel, M., & Barr, C. (2015). Sections 7 and 8 in OpenIntro Statistics - Third edition. Open Textbook Library. Retrieved from https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view

  - Why/use: These textbook sections provide in-depth explanations about the concepts regarding regression and have practice problems you can solve to test understanding.

- Simon, L., Young, D., & Pardoe, I. (2018). Penn State Stat 501: Regression Methods. https://online.stat.psu.edu/stat501/

  - Why/use: This resource provides real-life example applications of multiple linear regression as well as an in-depth intuitive explanation of the concepts. Lessons 1-7 cover the fundamentals of simple linear regression and multiple linear regression, while 8-13 cover more advanced topics.

- Khan Academy. (n.d.). Unit 5: Exploring two-variable quantitative data and Unit 15: Advanced regression (inference and transforming). https://www.khanacademy.org/math/statistics-probability

  - why/use: This resource provides video tutorials on simple linear regression and more advanced regression, as well as useful exercises to practice your learnings.

- B. Foltz. (n.d.). Playlist: Statistics PL15 - Multiple Linear Regression. Retrieved from:

  - why/use: This resource provides video explanations on both basics and advanced concepts regarding multiple linear regression.