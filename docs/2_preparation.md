# Chapter 2: Preparation

!!! abstract "Abstract"
    This chapter covers the preparation in terms of the approach and architecture defined for the solution, as well as the setup of the development environment. (**X min read**)

## Approach

<!-- Document the approach taken to develop the solution based on the defined requirements and knowledge about the project -->

Based on the available data, the decision was to start with a simple approach of basic scoring, in order to accelerate integration and collect early feedback to justify the need for a more complex approach

!!! tip
    Following the [KISS principle](https://en.wikipedia.org/wiki/KISS_principle), it is suggested to always start with a very simple approach (even if it is not Machine Learning), and once it is implemented you can collect feedback and data about usage and then refine it.

### Assumptions

This approach was elaborated taken into account these restrictions and considerations

- This approach is intended for a ["cold start"](https://medium.com/yusp/the-cold-start-problem-for-recommender-systems-89a76505a7), where no users history is available
    - Therefore, recommendations are obtained only based on the recipes information, not from users

- Assuming that available recipes are received from input

### Idea
In this "naive" approach, the idea is to get the recipes with best score based on the following aspects:

- Matching of ingredients entered
- Ratings of recipes
- Cooking time required

By tuning the score functions of these aspects, as well as the way to aggregate them, we could have a very quick way to select the best recipes to recommend, in order to be able to start the integration with other services and then have the structure needed to try a better approach.

### Metrics
In order to assess if a set of recommended recipes is appropriate for a set of entered ingredients, these are the aspects to be evaluated:

- Quality of matched ingredients, by checking average matching ratio of ingredients > 0.5 
- Popularity of recipes, by checking average rating > 4.0
- Complexity of recipes, by checking average cooking time < 60

More details about approach in [this Jupyter notebook](https://github.com/Matech-Studios/starvapp_recipes_recommender/blob/main/notebooks/20201228_basic_approach_scores.ipynb).


## Architecture

<!-- Describe the architecture of the solution, including diagrams and proper details to understand the workflows at high level -->

!!! info
    To be filled soon...


## Setup

<!-- Describe all the needed steps to setup a proper development environment -->

#### Code Repository

From scaffold? List Dependencies

!!! info
    To be filled soon...


#### Environment

!!! info
    To be filled soon...

#### Continuous Integration

Github Actions, and Azure Pipelines

!!! info
    To be filled soon...





