# #probability | Minerva University


> Source: [https://my.minerva.edu/academics/hc-resources/hc-handbook/probability/](https://my.minerva.edu/academics/hc-resources/hc-handbook/probability/)


## #probability

### Apply and interpret fundamental concepts of probability, including conditional and Bayesian probabilities.

**Please fill out this Google Form to submit suggestions for this page (i.e. typos, study guide contributions, useful applications, etc.). We are actively seeking feedback on anything big or small to make the HC Handbook as useful as possible.**

Making progress in the face of imperfect predictability.

A probability specifies how likely it is that a specific event will occur. There are different interpretations of probability, which provide different frameworks for understanding claims about the probability of various events. In addition, a conditional probability is the probability of an event occurring given the occurrence of another event. One important type of conditional probability is the "posterior probability" (the degree of belief, conditional on new data, in a hypothesis) based on a “prior probability” (the baseline or the degree of belief in the hypothesis prior to the new data). The posterior probability is updated as new data are obtained. One must take care to identify the appropriate method to calculate the probability of an event and to properly interpret probabilities.

Foundational Concept | Formal Analyses | Thinking Critically | Analyzing Data

**Class:** Formal Analyses | Semester One

**Unit:** Probability and Statistics

**Big Question:** What does it mean to be random? & How can data help us discover what is true?

You have your annual physical, and they take some blood. They have randomly been testing people for meningitis. They believe that 1 in 10,000 people in your city has this disease. The sensitivity (true positive) and specificity (true negative) of the blood test are both 99%. Your test comes back positive. Before you panic, you start analyzing the situation. Assuming that the probability of you catching meningitis is the same as the city population, the prior probability is P(Sick) = 0.0001. The posterior probability is calculated based on the prior probability and the sensitivity and specificity of the test: P(Sick|+) = P(+|Sick)\*P(Sick) / \[P(+|Sick) + P(+|¬Sick)\] = 0.99\*0.0001 / (0.99\*0.0001 + 0.01\*0.9999) — which is just under 1%. The low prior probability of being sick and the possibility of a false positive explain this relatively low chance of having the disease even in light of its high accuracy. It is also noted that the calculation depends on the assumption of prior probability. If instead you worked in a clinic and knew that one out of ten providers contracted the disease, you would use P(Sick) = 0.1 in the probability calculation, yielding a much higher probability. Luckily, you work a corporate job, so you don’t stress about it too much.

***Footnote:*** *Information is appropriately interpreted and represented as various types of probabilities: prior, posterior, conditional. Competing assumptions are considered and the most relevant is selected. Bayes Theorem is used to calculate the result, which is then interpreted with sufficient details.*

Is #probability the right HC? If the answer to the following questions is yes, #probability could be useful:

1. Are you calculating and/or interpreting the probability of an event?
2. Does your work involve randomness or outcomes that are not perfectly predictable (and thus, can only be described probabilistically)?

However, depending on the focus of the work, there might be other applicable HCs to consider. Consult the following table listing possible related HCs.

The following HC might apply if the work:

Try answering the questions on your own before checking the example answers.

What is the difference between expected value and a probability?

What does it mean for events to be independent? Provide examples.

What does it mean for events to be mutually exclusive? Provide examples.

Define prior and posterior probability.

Explain the difference between marginal, conditional, and joint probabilities.

Explain the General Multiplication Rule. How does this rule simplify when events are independent?

Explain the General Addition Rule. How does this rule simplify when the events are mutually exclusive?

Provide the formula for calculating conditional probabilities.

How does the independence of events A and B simplify the calculation of conditional probability, P(A|B)?

What is a Bernoulli random variable? Provide an example.

When might using conditional probability be helpful? Give an example.

What are some fundamental differences between frequentist and Bayesian interpretations of probability?

What are the conditions for events where the frequentist interpretation could apply?

Relate the concepts of probabilities to some common fallacies (Gambler’s fallacy, base-rate fallacy, confusion of inverse) arising due to misinterpretation of probabilities.

What is the Bayes theorem and its formula?

For **more** practice with this HC, refer to the exercises suggested in the Formal Analyses study guides. See the key resources for sources of practice questions.

- Have you considered within which framework (i.e., Bayesian or frequentist) your probability analysis lies and interpreted it correctly within this framework, providing a sufficient explanation?

- Have you accurately calculated an appropriate probability with clear and detailed steps?

- Have you interpreted the implication of probabilities on your research question?

- Have you ensured your probabilities are correct by conducting a sanity check (e.g. between 0 and 1)?

- Have you double-checked your calculations and/or used multiple calculation methods to verify correctness?

- The resulting probabilities are incorrect or nonsensical (negative quantities or greater than 1).

- The application does not sufficiently outline the steps or formulas used to derive the answers.

- The application does not sufficiently state and justify the assumptions underlying the calculations.

- The application lacks sufficient interpretation of the probabilities for the given context or fails to capture useful insights from the probabilities for the desired purpose.

- The application confuses the concept of expected value with probability.

- The application commits a fallacy associated with probability, like the gambler’s fallacy or base-rate fallacy.

- The application adopts frequentist approaches to perform the analysis but uses Bayesian language to interpret the results (e.g., incorrectly interpreting a p-value as the probability of the null hypothesis being true).

- In business and finance, where uncertainty and risk are inherent, probability plays a crucial role. Outcomes in this field are rarely perfectly predictable and can only be described probabilistically. Probability can be used to model and assess investment risks, estimate future market trends, and make informed decisions based on probabilistic forecasts.

- In statistical physics and thermodynamics, #probability is essential. The systems studied in these fields have an enormous number of degrees of freedom. Even for a simple system of gas particles in a box, the number of possible “microstates” (the positions and velocities of the gas molecules) becomes intractable. The characteristics of these systems can only be described statistically. We cannot precisely predict the exact locations or velocities of every gas molecule, but we can use #probability and #distributions to describe the macroscopic thermodynamic properties of the system.

  - Relatedly, but more specifically, we can view the second law of thermodynamics as a statement about #probability. This law states that the total entropy in the universe always increases, but there are several other formulations of the law as well. One formulation states that the direction of spontaneous change in a system is from an arrangement of lesser probability to an arrangement of greater probability. Regardless of the formulation, this law is inherently statistical in nature. There’s no physical force that forbids entropy from decreasing, but for any macroscopic system, the probability of this happening is so unimaginably small that it’s essentially impossible. Students taking courses in the physics track may encounter calculations that demonstrate this! These probability calculations require knowledge of combinators and fundamental probability rules.

- Most things in life are not perfectly predictable! We need to understand the principles of #probability to describe most real-life problems, systems, and decision-making scenarios.

  - In medicine, for example, probabilities can help determine the likelihood of a patient developing a certain disease based on their genetic history, lifestyle, and other factors.
  - In finance, probabilities can be used to measure the risk associated with investments and inform decisions about portfolio management.
  - In sports, probabilities can be used to analyze player performance and predict the outcome of games.
  - In quality control systems, the probability of defects or errors occurring in a production line can be calculated.

- Understanding this HC can help mitigate common fallacies such as gambler’s fallacy or base rate fallacies in real life. As an example of the base-rate fallacy, let's consider a hypothetical medical diagnostic test scenario where a certain disease affects 1% of the population. This 1% prevalence would be the “base rate.” Given this information, we know that in a population of 10,000 people, 1% (100 individuals) have the disease, and the remaining 99% (9,900 individuals) do not. If the test’s false-positive rate is 5%, it will produce false positives in 5% of the 9,900 disease-free individuals, which amounts to 495 false positives. One might commit the base-rate fallacy here if they perceive a positive test result to be ‘95% accurate’, without considering the base rate. The probability of having the disease after a positive test result is actually much lower than one might originally think due to the large number of false positives which stems from the tiny base rate of the disease. Assuming there are no false negatives, the probability of actually being infected after one is told that one is infected is only 17% (100/(100+495)).

- Diez, D., Barr, C., & Cetinkaya-Rundel, M. (2015). Section 2.1: Defining probability (special topic). OpenIntro statistics (3rd ed.).

  - This resource includes a wide range of practice questions for probability, as well as in-depth explanation about concepts.

- Wilkins, J. (Oct, 2020). Interpreting probabilities. Minerva University. https://my.minerva.edu/academics/hc-resources/cornerstone-custom-hc-guides/

  - This resource explores frequentist and Bayesian perspectives on probability in detail.