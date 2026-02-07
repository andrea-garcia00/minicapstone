# #optimization | Minerva University


> Source: [https://my.minerva.edu/academics/hc-resources/hc-handbook/optimization/](https://my.minerva.edu/academics/hc-resources/hc-handbook/optimization/)


## #optimization

### Evaluate and apply optimization techniques appropriately.

**Please fill out this Google Form to submit suggestions for this page (i.e. typos, study guide contributions, useful applications, etc.). We are actively seeking feedback on anything big or small to make the HC Handbook as useful as possible.**

Always striving for the best, but first defining what “best” means.

The solutions to many problems rely on the concept of optimization. Formally, optimization is the process of determining the relevant local or global extrema within a set of solutions that satisfy the problem constraints. To clearly define an optimization problem, one must identify the quantity to be minimized or maximized and the variables that can be modified or changed in search of the optimal value(s). Once the problem is defined, an appropriate optimization process or technique that describes how to achieve the optimal solution must be chosen. Many common optimization techniques can be implemented algorithmically. It is important to define a process that will yield a feasible solution that can be reasonably implemented.

Foundational Concept | Formal Analyses | Thinking Creatively | Solving Problems

**Class:** Formal Analyses | Semester Two

**Unit:** Algorithms and Simulation

**Big Question:** How can we use machines to solve problems and make decisions?

As a college student on a limited budget, you want to create a list of core grocery items (milk, eggs, bread, etc.) that fulfills your daily recommended nutrition requirements. At first, it appears that you have multiple objectives to optimize, such as caloric count, protein quantity, cost, etc. Moreover, some of these objectives are in conflict with others (increasing caloric count may also increase your costs). After some deliberation, you identify cost as the objective function you wish to minimize, and frame all other values as constraints, in line with the USDA’s dietary recommendations for macro and micro nutrients for your demographic group (2800-3000 cal/day, 6-8 servings of grains, 3-5 servings of vegetables, 800mg calcium, etc.). With your constraints and objective function identified, you clearly articulate your decision variable: for each item at the store, what quantity of each should be on your list? Now that your optimization problem is well formulated, you identify a computational approach to solve the problem. Given the large search space, you settle on using a genetic algorithm, which is efficient but only produces a locally optimal (and not necessarily a globally optimal) solution. You accept this limitation, noting that you only want a grocery list that is “good enough” in terms of cost efficiency. You then follow the processes required to apply this specific algorithm (setting up a library of candidate solutions and defining a way for solutions to “recombine” and “mutate” to create new proposed solutions). You also modify the algorithm to be context-appropriate by ensuring that your custom mutation and recombination operators obey the constraints. The output produced by your algorithm is a list of items, and how many of each to purchase, to get the maximum value for your money while still being adequately nutritious.

***Footnote:*** *An optimization problem is identified and explained, including the quantity to be optimized (cost), the variables that can be altered (the quantity of each item to purchase), and the fixed constraints (e.g., calorie count). A genetic algorithm is applied to solve the problem, justifying this choice of technique. An acceptable solution is found even though it may not necessarily be the global optimum.*

Is #optimization the right HC? If the answer to the following questions is yes, #optimization could be useful:

1. Is there a notion of “optimal” or “best” in the context of your work?
2. Are you trying to find an optimal solution to a problem?
3. Is defining the task at hand as an optimization problem productive and relevant for your work?
4. Are you implementing and evaluating a technique to solve an optimization problem?
5. Are you comparing and contrasting different techniques to solve an optimization problem?

However, depending on the focus of the work, there might be other applicable HCs to consider. Consult the following table listing possible related HCs.

The following HC might apply if the work:

- Applies or analyzes a systematic step-by-step process to solve a problem, which can include optimization problems. There are several types of optimization techniques that can be implemented algorithmically.

- Identifies, describes, and classifies variables that are relevant to the problem or system under study; doing so is crucial for effectively defining optimization problems. One must be able to identify the quantity to be maximized or minimized, the factors that can change in pursuit of the optimum, and the factors that cannot change. Describing and classifying these quantities and factors relies on the principles of #variables.

- Applies utilities and utility functions to represent preferences and analyze decision-making scenarios. The principles of #optimization can be helpful in decision-making contexts since we can frame them as optimization problems: rational decision-makers will make the choice that maximizes their expected utility.

- Focuses on how to solve a problem by deconstructing it into tractable well-defined sub-problems. Optimization techniques, such as divide and conquer, may involve breaking down problems and solving the sub-problems before assembling them to find the final optimal solution.

- Focuses on characterizing key aspects of a problem, including its initial state, goal state, obstacles, and scale. Characterizing an optimization problem requires further specifications, including identifying the objective function, decision variables, and constraints.

- Focuses on identifying constraints and obstacles of a problem to place boundaries on what is possible, and uses constraint satisfaction to solve a problem. Identifying constraints is an important part of defining and solving optimization problems.

- Evaluates or applies simple rules to make decisions or solve problems. This includes using heuristics to solve optimization problems. Some optimization techniques, especially greedy approaches, are comprised of heuristics.

Try answering the questions on your own before checking the example answers.

What components are required to define an optimization problem? Describe each of the components.

What is the difference between a local (relative) optimum and a global (absolute) optimum?

Is it always necessary to find the global optimum? Why or why not?

For each of the following common optimization techniques, briefly explain how it works and give an example of where it could be used in real life: Brute-force, Greedy algorithm, Hill climber, Divide and conquer

What is overfitting and why is it important in optimization problems?

Consider some of the day-to-day challenges you face, such as planning your meals, preparing for class, cleaning your room, navigating back to res, and loading the dishwasher. Pick one that resonates with you and represent it formally as an optimization problem. Then consider what it would mean to take a “brute-force” approach to solve the problem. What about a “greedy” approach?

Consider some of the problems encountered in the computation sciences. For example, finding the regression line for a bivariate dataset, finding the best classification model, or sorting a list of numbers as efficiently as possible. Pick one that resonates with you and represent it formally as an optimization problem. Then describe one technique that can be used to solve it.

For **more** practice with this HC, refer to the exercises suggested in the Formal Analyses study guides. See the key resources for sources of practice questions.

- Have you clearly defined the optimization problem with a sufficiently detailed explanation for each component of the problem (i.e., objective function, decision variables, constraints)?

- Have you ensured that your objective function is a specific quantity that can be measured, and sufficiently described how this quantity would be measured and represented?

- Have you considered practical/real-world decision variables and/or constraints that are pertinent to your optimization problem?

- Have you justified why defining the task at hand as an optimization problem was relevant to your purpose? What insights did it offer and how did you use it productively?

- Have you chosen an appropriate technique to solve the optimization problem and effectively justified the choice?

- Have you described an optimization technique in sufficient detail, possibly by outlining its main steps?

- Have you effectively explained whether or not an optimization technique is expected to find the global optimum?

- Have you effectively compared and contrasted different optimization techniques for the problem at hand?

- Have you implemented an optimization technique (e.g., in code) with sufficient explanation to justify the implementation?

- Have you interpreted the results of applying an optimization technique to solve a problem in a way that’s relevant to the purpose of the work?

- Have you considered whether it’s important to find the global optimum in the context of your work?

- The application cites #optimization in a colloquial manner without attempting to formalize the situation by identifying what exactly is being optimized and how.

- The application misses key parts that are needed to comprehensively define the optimization problem.

- The objective function is not specified in sufficient detail, possibly as a result of trying to optimize multiple quantities, neglecting to identify its dimensions, or insufficiently explaining how it would be measured.

- The definition of the optimization problem misses relevant decision variables or constraints.

- The application does not sufficiently explain an optimization technique, perhaps missing its pros and cons, failing to outline its main steps, or neglecting to interpret its results.

- The application does not mention whether an optimization technique finds the global optimum, or does not sufficiently justify how.

- Justification for why the application of #optimization is relevant for the purpose of the work is missing.

- This HC may arise in business applications when you’re considering how to streamline operational processes. For example, you may identify that the current operational costs are too costly, and decide to minimize the objective function of operational costs. Decision variables may involve factors like packaging methods (e.g. using automation or using human labor) or labor costs. There may be numerous constraints, one of which could be the need to fulfill current customer orders even after optimizing.

- Optimization is likely to arise in mathematical contexts, especially calculus. Representing the objective function (the quantity to be maximized or minimized) of an optimization problem as a mathematical equation allows us to use analytical and algebraic tools, such as differentiation, to characterize the extrema of the function. Specifically, for continuous functions, one can determine all of its global and local extrema by finding the points at which its derivative is equal to zero. In this way, calculus tools offer an efficient way to solve optimization problems! However, not all mathematical functions are differentiable, and not all objective functions can even be easily represented by analytic expressions. In these cases, more sophisticated optimization techniques are required. Indeed, Minerva has an entire concentration course dedicated to advanced optimization methods!

- Optimization is key to machine learning, so it’s likely to come up in computational science classes. For example, to classify data, a learning algorithm is used to adjust the classification model's parameters (weights and biases) to produce the most accurate classification. The “most accurate” or “best” classification model can be measured using a few different quantities, such as the proportion of correctly classified data points. Other common metrics are described in this blog post by Bajaj (2021). It’s important to identify and understand this objective value as well as the decision variables and constraints for the task at hand, in order to choose an appropriate classification model, implement an effective learning algorithm, and produce the most accurate classification.

- The concept of optimization is relevant in the natural sciences. Nature tries to optimize its performance in numerous ways! For instance, in physics, one can characterize the behavior of physical systems based on their tendency to minimize their energy and maximize their entropy. In particular, the “Principle of Least Action” is one way to formulate the behavior of a mechanical system by stating that its motion will always minimize the “action,” which is typically a function of its kinetic and potential energies. So, of all possible trajectories, a particle will follow the trajectory that minimizes its energy. It’s interesting to adopt the perspective that nature is somehow optimizing its motion! Similarly, the Second Law of Thermodynamics is another way to describe the behavior of physical systems in terms of an optimization problem, stating that systems evolve to maximize the total entropy (a measure of disorder).

- We’re almost always trying to optimize something in our day-to-day life. Generally speaking, we want maximum quality yet minimal effort, cost, and time. Consider these specific daily life examples:

  - *Deciding on the best sandwich to eat*. The definition of “best” (the “objective function”) might vary from person to person. Perhaps you want the most delicious sandwich as measured by your tastebuds or one that maximizes some nutrition metric. The aspects of the sandwich that you can adjust (the “decision variables”) are the types of bread, fillings, spreads, and other ingredients. You might be working under certain constraints, such as limited amounts of ingredients, a budget, or an upper bound on portion size. Once the problem of creating the “best” sandwich is defined, you can start thinking of ways to solve it. A brute-force approach would require trying all possible combinations of bread and fillings and choosing the most delicious. This is different from a "greedy" approach that uses a heuristic to make the best sandwich (e.g., always pick the grainiest bread, whatever cheese is going to expire first, and one savory condiment).

  - Relatedly, one can also consider optimizing your entire nutrition intake. Check out the general example for this HC above.

  - *Picking up groceries*. Have you ever thought about the order in which you navigate the grocery store? You probably want to be as efficient as possible, meaning that you complete your shopping in the least amount of time. With “time” as the “objective function” that you want to minimize, you can adjust the order in which you pick up items in the store. For example, you could get the bananas first, then the milk, then the bread, or the other way around. Regardless of the order, you must use your grocery list as a constraint in the sense that you need to purchase all items on your list. There could be other constraints too. For example, if you know the milk is too heavy to carry while walking around the store, you might need to pick up that item last.

  - *Organizing your schedule*. Fitting a variety of tasks into your schedule is a challenge. When organizing schedules, you likely work under certain constraints (events or tasks that cannot be adjusted) but have a number of “decision variables,” such as when to study, how long to sleep in, when/where/how to exercise, whether or not to partake in city experiences, etc. Picking one “objective function” in this context is not straightforward. It’s likely not as simple as striving to maximize the number of different experiences you do or maximizing your free time. Nonetheless, by thinking through the factors that matter to you, the constraints you must adhere to, and the elements under your control to change, you can approach your scheduling more systematically. When trying to optimize it further, you could adopt a “hill climber” approach by making small changes and seeing if they lead to an improvement. If they do, adopt them and continue. If they don’t, revert the change and try something else.

  - *Purchasing flight tickets*. Read the first few pages of the Optimization Cornerstone guide.

- Businesses and companies are usually trying to solve optimization problems. Here are some specific examples:

  - Traveling salesman problems, in which one aims to minimize the length of a route connecting multiple specified nodes, are common in many domains such as package delivery, GPS navigation, school bus routes, meal service delivery, drone flight mapping, and circuit board planning. In all of these domains, one can adjust the order in which the nodes are “visited” but the constraints can vary between different contexts.
  - Just-in-time supply chains are commonly used to move materials right before they are needed in an effort to minimize the amount of inventory. Multiple other objectives are relevant in this context, such as costs, waste, product defects, processing time, waiting time, customer satisfaction, and employee satisfaction.

- AlphaOpt. (2017). Introduction to Optimization. \[Video\] *YouTube.* Retrieved from https://www.youtube.com/playlist?list=PLLK3oSbvdxFdF67yVxF_1FQO9SbBY3yTL

  - Why/use: This playlist includes definitions of basic optimization terms, as well as explanations of more advanced concepts such as simulated annealing.

- Shafkat, I. & Terrana, A. (2022). *Optimization Cornerstone Guide.* Minerva University. https://my.minerva.edu/academics/hc-resources/cornerstone-custom-hc-guides/

  - Why/use: This custom guide includes in-depth explanations regarding defining optimization problems, with both daily life practical applications and computer science applications.