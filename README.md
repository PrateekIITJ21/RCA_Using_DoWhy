#DoWhy¶
In this notebook, we are going to be using the DoWhy python library which allows us to do causal inference in a few simple lines of code. According to the documentation:

While many methods exist for causal inference, it is hard to compare their assumptions and robustness of results. DoWhy makes three contributions,

Provides a principled way of modeling a given problem as a causal graph so that all assumptions are explicit.
Provides a unified interface for many popular causal inference methods, combining the two major frameworks of graphical models and potential outcomes.
Automatically tests for the validity of assumptions if possible and assesses the robustness of the estimate to violations.
DoWhy also breaks this down into 4 steps:

Modeling: Create a causal graph to encode assumptions.
Identification: Formulate what to estimate.
Estimation: Compute the estimate.
Refutation: Validate the assumptions.

# RCA_Using_DoWhy
Root cause analysis (RCA) of latencies in a microservice architecture
In this case study, we identify the root causes of “unexpected” observed latencies in cloud services that empower an online shop. We focus on the process of placing an order, which involves different services to make sure that the placed order is valid, the customer is authenticated, the shipping costs are calculated correctly, and the shipping process is initiated accordingly. The dependencies of the services is shown in the graph below.
