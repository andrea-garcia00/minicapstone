# #algorithms | Minerva University


> Source: [https://my.minerva.edu/academics/hc-resources/hc-handbook/algorithms/](https://my.minerva.edu/academics/hc-resources/hc-handbook/algorithms/)


## #algorithms

### Apply algorithmic thinking strategies to solve problems and effectively implement working code.

**Please fill out this Google Form to submit suggestions for this page (i.e. typos, study guide contributions, useful applications, etc.). We are actively seeking feedback on anything big or small to make the HC Handbook as useful as possible.**

Using recipes to solve problems.

An algorithm defines a set of steps that lead a given input to produce the desired output. The steps of a proper algorithm are well-ordered, clear, unambiguous, and effective (doable). Additionally, the algorithm should be robust enough to handle a range of inputs, rather than a small set of specific cases. It should also be as simple and efficient as possible, avoiding redundancies. Lastly, a proper algorithm should terminate in a finite number of steps. These properties can be achieved by systematically incorporating conditional steps (in which a decision must be made) and iteration (repeated steps), usually requiring careful testing and troubleshooting (“debugging”). Familiarity with various algorithmic strategies, such as brute-force methods, greedy algorithms, and divide-and-conquer approaches, can certainly broaden one’s problem-solving repertoire. These algorithmic strategies can be used to efficiently solve many real­-world problems, from connecting individuals on social media, to controlling self­-driving cars, to sequencing DNA. Algorithms are the most powerful when they can be interpreted and run by computers. Thus, writing and explaining computer code helps to boost one’s algorithmic thinking and problem-solving capabilities.

Foundational Concept | Formal Analyses | Thinking Creatively | Solving Problems

**Class:** Formal Analyses | Semester One

**Unit:** Logical Thinking

**Big Question:** How is free choice manipulated?

You need to assign students to residence hall rooms. Roommates must have the same gender and should have some common interests but should not be from the same country and should not have identical interests (you want students to be exposed to new influences). You can manually assign students to rooms, but this is complicated and tedious. Worse, you would have to do it all again next year. To address this, you decided to develop an algorithm that can be automated by computer code. Firstly, the algorithm takes an input of relevant characteristics from students, including details about living preferences, habits, and interests. You decide to use drop-down menus for students to input their selections because a finite set of pre-defined inputs makes your algorithm more feasible to write compared to free-form student inputs. Based on the data and parameters, the algorithm generates a potential list of matches for each student and assigns rooms starting from the students with the least options, updating the number of available matches as rooms are being assigned. Ultimately, the algorithm generates a list of room assignments that satisfy the constraints; if it is impossible to do so, the algorithm returns a message to notify you. You implement the algorithm using a computer program, which assigns roommates effectively and efficiently and can be used for each year's room assignment given similarly-formatted data on student characteristics. The code is complete with thorough documentation and instructions for running, allowing your colleagues to understand the process.

***Footnote:*** *Having identified a problem that benefits from an algorithmic solution, an appropriate process is developed and explained to assign students to rooms. The details of the algorithm are identified, explained, and justified: input, internal logic, output, and error message*

Is #algorithms the right HC? If the answer to the following questions is yes, #algorithms could be useful:

1. Does the work present a clear, step-by-step process or procedure to solve a problem, including the inputs and outputs?
2. Does the work evaluate one or more algorithmic strategies to approach a problem?

However, depending on the focus of the work, there might be other applicable HCs to consider. Consult the following table listing possible related HCs.

The following HC might apply if the work:

- breaks down a big problem into subproblems; in the context of algorithms, can include creating functions that compartmentalize the code and analyzing how the subproblems might “come together” in the program

- uses a ‘short-cut’ or a ‘rule-of-thumb’ strategy to solve the problem.

- employs heuristics within the algorithm’s steps. For example, greedy algorithms typically use a heuristic to decide on the "best" action to take at each step (locally).

- uses an appropriate optimization process or technique to obtain an locally or globally optimal solution to a problem, which may be through algorithmic strategies such as greedy or brute force.

- uses a simulation (which could be an algorithmic process) to derive the implications or predictions of a model and pays particular focus to the assumptions of the model and the usefulness of the results. .

Try answering the questions on your own before checking the example answers.

What are the requirements for a good algorithm?

What does it mean for an algorithm to be clear and unambiguous? Why is this important?

What does it mean for an algorithm to be finite? Why is this important?

What does it mean for an algorithm to be generalizable? Why is this important?

What does it mean for an algorithm to have effectively computable operations? Why is this important?

What are some different ways to measure an algorithm's efficiency? Why is this important?

What are the following types of algorithms and are they guaranteed to always find the optimal solution? Give examples of problems that each algorithm type can solve: Brute-force, greedy algorithms, divide-and-conquer.

Does an application of #algorithms require code?

What does it mean to test an algorithm? What are different ways you can test an algorithm?

What are different ways you can describe an algorithm’s runtime?

List at least three strategies you can use to understand how a complicated algorithm works.

List at least 2-3 strategies to debug code that isn't working properly.

- Have you identified the input, output, and set of steps of the algorithm?

- Have you ensured that the steps adhere to desired properties of good algorithms, such as clarity, finiteness, robustness, termination, and efficiency, and included justification?

- Have you identified what type of algorithm is being used?

- Have you justified your choice of algorithm or type of algorithmic strategy, including the way that steps are ordered and broken down (possibly using functions)?

- Have you ensured that the algorithm fulfills its intended functionalities by demonstrating test cases, including possible edge cases?

- Have you included a sufficient amount of comments (using in-line coding comments and/or holistic explanations) to demonstrate that you have a deep grasp of the algorithm?

- Have you discussed the algorithm’s complexity or efficiency?

- Have you proposed or implemented changes to improve an algorithm’s efficiency? (e.g., utilizing iteration to avoid redundancy)

- Have you created a flowchart to visualize the algorithm, adhering to proper flowchart conventions?

- Have you justified the choice of data structures utilized in the algorithm?

- Have you adhered to conventions for readable algorithms, such as using appropriate variable names and comment styles?

- The application misidentifies or fails to identify the outputs and inputs.

- The steps of the algorithm are not specified in sufficient detail.

- The steps of the algorithm are vague, ambiguous, ineffective, or incomplete.

- The algorithm does not work as intended.

- The application does not include sufficient tests or does not account for edge cases when testing.

- The algorithm does not include sufficient comments to explain how it works.

- The efficiency of the algorithm has not been sufficiently considered.

- The algorithm uses inappropriate data structures.

- The application involves inappropriate or non-descriptive variable names.

- This HC is applicable to most CS core and concentration classes.

  - Across machine-learning concentrations, different algorithmic strategies are involved, such as supervised vs unsupervised.
  - Algorithms may be used in line with #modeling ([[modeling]]) to create simulations for a wide variety of real-world system, including traffic, flooding, and biological systems.

- The HC may be applicable in business contexts, as organizations and companies need to construct and implement algorithms to solve problems or perform tasks that occur on a regular basis. For example, consider a company’s customer service department. An algorithm for employees to follow would be helpful to ensure that they are dealing with questions from customers in a systematic and consistent manner. The algorithm’s input would be the customer’s questions or complaints, and the desired output would be some sort of resolution. Constructing such an algorithm would require deeply understanding the huge variety of customer inquiries. The algorithm would need decision nodes (like if-statements) that lead down different branches depending on the complaint. More thought would need to be given to various edge cases that fall outside the usual categories of inquiries and require a unique solution. The algorithm should have a guideline for addressing such unusual novel cases. Once the algorithm is developed to a sufficient level of detail and thoroughly tested out, even a computer can follow it! Does the company even need a human to handle customer service anymore?

- Algorithmic thinking is crucial in several aspects of daily life and across many different fields. Any time you are using a set of instructions to tackle a difficult problem, you are likely employing the principles of algorithmic thinking. Here are a few examples:

  - It can help you develop and follow recipes for cooking and baking.
  - It is used in industries like transportation, logistics, and supply chain management. In these fields, algorithms are used to optimize delivery routes, cut costs, and boost productivity.
  - Algorithmic trading is an approach in finance to evaluate the stock market and create transactions.

- In healthcare, algorithmic thinking is used to build clinical decision support systems that help doctors make diagnoses and plan treatments. For diseases that have a highly complex diagnosis, algorithms are especially valuable to establish protocols. This article in the National Library of Medicine provides one example: *A clinical approach to diagnosis of autoimmune encephalitis.* In this article, expertise from a large team of professionals has been used to construct an algorithm to provide autoimmune encephalitis diagnosis guidelines for medical practitioners. This flow chart contains a visualization of the algorithm, complete with several decision nodes (“if-statements”) that serve to handle the wide variety of factors that need to be considered in the process, and clear outputs for each case.

- An application of algorithms in music! Common algorithmic strategies, like brute force, are widely applicable outside of computer science. Musicians can even adopt algorithmic composition techniques! A famous example is in John Williams' score for the 1977 Steven Spielberg film, 'Close Encounters of the Third Kind.' The five tone sequence used throughout the movie was found through a brute force approach by listing all 130k+ permutations of 5 notes on the western musical scale. He didn't actually listen to them all, but rather to a subset of about 400, then selected the one he liked. Those interested in this can look up old interviews about. Here is one clip from the most famous scene.

- Check out the HC Handbook for #optimization ([[optimization]])for more real-world practical applications of algorithms in optimization settings, including picking what to eat, navigating the grocery store, and planning your schedule.

- Malan, D. J. (2013, May 20). \[TED-Ed\]. What's an algorithm? \[Video\]. YouTube. https://www.youtube.com/watch?v=6hfOvs8pY1k

  - A simple introduction to the concept of algorithms and how to use them to solve problems.

- DataCamp Team. (2023, Sept). What is an Algorithm? DataCamp. https://www.datacamp.com/blog/what-is-an-algorithm

  - A quick but comprehensive introduction to algorithms, providing a definition, examples, use-cases, and features of good algorithms.

- Walia, R. K. (n.d.). Algorithm & Flowchart Manual for Students. https://course-resources.minerva.edu/uploaded_files/mu/00306798-0780/algorithm-and-flowchart-manual-algorithm.pdf

  - This resource describes why flowcharts are helpful and supplies some best practices and conventions to follow.

- Zhang, A., Lipton, Z. C., Li, M., & Smola, A. J. (2022, Dec). Dive into Deep Learning. https://d2l.ai/chapter_introduction/index.html#

  - The first chapter of this text provides an exciting and accessible introduction to machine learning.

- Shafkat, I. & Terrana, A. (2022, Nov 26). Optimization Cornerstone Guide. Minerva University. https://course-resources.minerva.edu/uploaded_files/mu/00298160-6576/optimization-cornerstone-

  - The guide gives an in-depth overview of optimization and discusses optimization in algorithmic contexts.