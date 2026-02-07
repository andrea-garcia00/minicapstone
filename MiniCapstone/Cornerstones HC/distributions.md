# #distributions | Minerva University


> Source: [https://my.minerva.edu/academics/hc-resources/hc-handbook/distributions/](https://my.minerva.edu/academics/hc-resources/hc-handbook/distributions/)


## #distributions

### Identify different types of distributions and make inferences based on samples from distributions appropriately.

**Please fill out this Google Form to submit suggestions for this page (i.e. typos, study guide contributions, useful applications, etc.). We are actively seeking feedback on anything big or small to make the HC Handbook as useful as possible.**

The powerhouse of probability and statistics.

The distribution of a variable is a function that maps all possible values of the variable to how often they occur (the frequency of occurrence). There are several types of distributions, but the most commonly used in statistics is the familiar bell curve, called a “normal” or “gaussian” distribution. When distributions are used to describe data, one must distinguish between population data (all possible values or elements of interest) and sample data (a subset of the population). Drawing statistical inferences about a population from sample data often requires a “sampling distribution,” a theoretical distribution of the values of a specified statistic (i.e., mean, proportion) over all possible random samples of a specific size that can be made from a given population. The shape of the sampling distribution is ensured by the Central Limit Theorem when certain criteria are met. However, statistical analyses often require assumptions about the underlying distributions, requiring one to state those assumptions and analyze their limitations. Considering distributions can help one recognize phenomena such as regression to the mean.

Foundational Concept | Formal Analyses | Thinking Critically | Analyzing Data

**Class:** Formal Analyses | Semester One

**Unit:** Probability and Statistics

**Big Question:** What does it mean to be random? & How can data help us discover what is true?

You are an engineer, hired to construct elevators for a shopping mall. Your manager asks you to determine the probability that the elevator will be over the threshold safety weight (700 kg) when there are 9 people in it. Past research shows that the shoppers at the mall have a mean weight of 55 kg and a standard deviation of 12 kg. While you don’t know the shape of this underlying distribution of weights, you realize that as long as it is somewhat symmetric, you can employ the Central Limit Theorem to conclude that the sampling distribution of the sample mean (with sample size 9) is approximately normal, with a mean of 55 kg and a standard error of 4 kg (SE = SD/sqrt(n)). This allows you to accurately compute, using z-scores, the probability that the mean weight of 9 randomly selected mall shoppers is over 78 kg (700 kg / 9) as the area under the upper tail of the sampling distribution. However, you realize that perhaps the original distribution is very skewed to the left, with mostly adults at the mall but a few babies as well. In this case, since the small sample size of interest is only 9, the sampling distribution would still be skewed to the left, meaning that the probability you computed under the assumption of normality is an underestimate. You deliver these results to your manager with all caveats laid out.

***Footnote:*** *The sampling distribution of the sample mean was explained and used to compute the probability of the elevator being overweight. The normality of the sampling distribution was justified using the Central Limit Theorem, with the assumptions and effects of the underlying distribution clearly stated.*

Is #distributions the right HC? If the answer to the following questions is yes, #distributions could be useful:

1. Are you applying properties of probability distributions to solve a problem or analyze a situation (e.g., using normal distributions to find percentiles, using binomial distribution to determine probabilities)?
2. Are you evaluating the features of a distribution of a quantity or dataset to provide useful insights for your purpose (e.g., checking shape of sample distribution to meet conditions for inference, noticing skew in a distribution and discussing implications)?
3. Are you using properties of distributions to make statistical inferences about a population (e.g., sampling distributions, checking conditions)?
4. Are you analyzing the implications of drawing samples from a distribution (e.g., regression to the mean, sampling with vs without replacement)?

However, depending on the focus of the work, there might be other applicable HCs to consider. Consult the following table listing possible related HCs.

The following HC might apply if the work:

Try answering the questions on your own before checking the example answers.

What is a Probability distribution? What ‘rules’ do they satisfy?

What is a Probability Density Function?

What is the difference between a continuous and a discrete distribution? Why does it matter?

Explain Population data vs sample data. Explain how their distributions might differ.

What does it mean to sample from a distribution?

Describe the following distributions by describing it, providing a formula (if appropriate), the parameters, describing the shape, and examples of where it’s used.

Under what conditions is the binomial distribution approximately normal?

What is a percentile?

What is a Z-score? A T-score?

How do you convert between z-scores and percentiles? What about converting between t-scores and percentiles? How would this work for other distributions other than the normal distribution and t-distribution?

When does the t-distribution approach normal distribution?

When would we use t-scores instead of z-scores for circumstances like calculating confidence intervals?

What is the difference between the standard deviation and the standard error?

Distinguish between the population distribution, the sample distribution, and sampling distribution.

What is the mean and the standard deviation of the sampling distribution of the sample mean equal to? What is the shape of the sampling distribution?

What is the Central Limit Theorem? What is its relationship with the sampling distribution?

Why does sampling from a distribution without replacement imply that sampling is not independent? What does this have to do with the “10% rule” that is often quoted when verifying the conditions for inference?

Describe the concept of regression to the mean. How does this phenomenon rely on properties of distributions?

What is the Finite Population Correction factor? When is it needed? What quantity is it used to 'correct'?

For **more** practice with this HC, refer to the exercises suggested in the Formal Analyses study guides. See the key resources for sources of practice questions.

- Have you identified an appropriate distribution for your purpose and justified why?

- Have you utilized or applied specific properties of an appropriate distribution to obtain relevant insights that advance your work?

- In the context of statistical inference, have you clearly distinguished between the sample distribution, the population distribution, and the sampling distribution?

- Have you listed and thoroughly evaluated any conditions for the underlying distribution or sampling process that may be required by your statistical analysis (e.g., the conditions for the central limit theorem)?

- Have you stated any assumptions that are needed about the underlying distribution or how the distribution was sampled from, and explained the impacts of those assumptions on your analyses?

- Have you discussed the implications of drawing samples from a distribution (e.g., regression to the mean, sampling with vs without replacement) in a way that’s relevant to your analysis?

- Have you effectively utilized graphs or other visualizations (e.g., histograms or probability density curves) to support your analysis?

- The application uses an inappropriate distribution for the given context.

- The distribution was applied incorrectly, leading to errors in probability calculations (e.g., incorrect conversions of z-scores to percentiles), possibly resulting from neglecting to draw the distribution and identify the area under the distribution that corresponds to the desired or relevant probability.

- The application does not adequately identify and distinguish between the sample, population, or sampling distribution.

- The required conditions on the distributions were simply listed and assumed, instead of thoroughly evaluated for the given context and data.

- The application fails to recognize potential limitations of the analysis arising from problematic assumptions on the underlying distribution or sampling process.

- The application confuses regression to the mean with the gambler’s fallacy.

- The application focuses on evaluating sampling methods without mentioning implications on the analysis of distributions (this would fall more in the purview of #sampling).

- This HC is introduced in Formal Analyses by focusing on a limited set of types of distributions (e.g., normal, binomial, uniform, t-distribution), but students should note that there are many other types of distributions (e.g., poisson, geometric, gamma), some of which will be encountered in Cores and Concentrations, and all of which rely on the foundations of #distributions.

- Distributions are involved when making any kind of statistical inference across all disciplines, ranging from natural sciences to social sciences. For example, when conducting significance testing, you may need to examine the distribution of sample data to observe whether conditions for tests (e.g., normality, independence) are met, but analyzing the underlying distributions and evaluating any required assumptions is a fundamental step in statistical analysis.

- In physics and chemistry, particularly statistical mechanics and thermodynamics, tools from statistics and probability theory are essential. In these fields, we are interested in understanding systems with a large number of microscopic entities. It’s intractable to characterize the exact properties of each particle, but we can describe their properties probabilistically. For example, consider molecules in a gas. We can’t determine the precise speed of each molecule, but further, the molecules won’t all have the exact same speed. However, the *distribution* of molecular speeds is predictable (the speeds in an ideal gas follow the Maxwell-Boltzmann distribution), and this distribution is tightly connected to the temperature of the system and other thermodynamic quantities. Properties of this distribution can help one understand thermodynamic processes like condensation and evaporation.

- In finance applications, probability distributions are often used in risk management. It’s impossible to know the exact return on an investment, but distributions can be used to determine the probability of losses or estimate the expected value of returns. Distributions can be constructed using historical market data and may also be based in finance theory, and in particular, lognormal distributions are commonly used in finance to model asset prices. This means that the natural logarithm of the asset price follows an approximately normal distribution. The validity of this model stems from the central limit theorem but rests on certain assumptions about the distribution of continuously compounded returns.

- This HC can give you a useful perspective and way of modeling many real-life quantities. For example,

  - Numerous variables can be well-approximated by a normal distribution, such as heights, IQ, birth weights, and the sum of numbers on two dice. Even when the quantity of interest is not approximately normally distributed (e.g., income in the population is commonly skewed by a small number of very wealthy individuals), the central limit theorem guarantees that the sampling distribution of the sample mean is approximately normal, allowing one to make well-reasoned statistical inferences about the population. This theorem allows us to make reliable estimations despite not having access to the complete population data and thus not knowing the exact shape of its distribution.
  - Uniform distributions are used whenever all possible outcomes are equally likely, like flipping a coin, rolling a die, or using Python to generate a random number between 0 and 1.
  - Binomial distributions are useful in any situation in which we are interested in how many items in a sample satisfy a certain criteria (commonly termed“success”), such as determining the probability of obtaining five CS majors in a group of ten randomly selected students, or the probability that the number of passengers that show up to their flight on time is equal to the number of seats on the plane.In the examples above, recognizing the most appropriate distribution to model the situation is essential. We can then use properties of the corresponding distribution to characterize the scenario, understand the quantity of interest, and make inferences and predictions. For example, if you know a distribution is normally distributed, you can make valid claims such as “68% of the data is within 1 standard deviation of the mean.”

- Regression to the mean is a common phenomenon that can arise in situations that involve both skill and luck (random chance). It shows up with test scores, athletic performance, movie sequels, social science research studies, and more. Simply put, when something weird or extreme happens, we shouldn’t expect it to happen again. For example, if a group’s performance (on a test, in sports, or some other way) is extraordinarily good or bad, we should expect their average performance to be less extreme on the next try. The OnlineStatBook reading by Lane in the Key Resources might refresh your memory on this phenomenon. This HC offers a valuable perspective to understand regression to the mean as a pattern that results from random sampling from distributions. See the associated self-study question above for more details.

- Terrana, A. (2022). *What is Statistical Inference?*. Minerva University. Retrieved from https://my.minerva.edu/academics/hc-resources/cornerstone-custom-hc-guides/

  - This resource provides a visual overview of where distributions are used within statistical inference, clarifying the relevance of the population distribution, the sample distribution, and the sampling distribution.

- Diez, D., Barr, C., & Cetinkaya-Rundel, M. (2015). Sections 2.1.4, 2.4, 2.5, 3.2 3.3.1, and 3.4, 4.1, 4.4, 5.1. *OpenIntro Statistics* (3rd ed.). Retrieved from https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view

  - The following chapters include in-depth explanations and practice questions for many foundational concepts related to #distributions mentioned within the handbook.

- Khan Academy. (n.d). Sampling distributions. AP Statistics. https://www.khanacademy.org/math/ap-statistics/sampling-distribution-ap#what-is-sampling-distribution

  - These videos introduce essential concepts for understanding the basis of the central limit theorem. Conceptualizing the "sampling distribution" and how it differs from the population distribution is an important concept within this HC. This unit covers sampling distributions for both means and proportions. There are numerous beneficial practice questions throughout and at the end to test your understanding.

- Kunin, D. (n.d.). Probability distributions: Central limit theorem. Seeing Theory. https://seeing-theory.brown.edu/probability-distributions/index.html#section3

  - This interactive website allows you to visualize the central limit theorem in action. Read the paragraph under Central Limit Theorem and change alpha and beta to alter the population distribution's shape. Try different sample sizes and number of draws. Checking the Theoretical box displays the sampling distribution after an infinite number of draws. Notice: how does its shape compare to that of the population distribution?

- Lane, D. (n.d.). Regression toward the mean. OnlineStatBook. http://onlinestatbook.com/2/regression/regression_toward_mean.html

  - This resource provides an introduction to regression to the mean, providing examples and common misunderstandings. You may be interested to skim through the New York Times Article linked at the bottom of the page.