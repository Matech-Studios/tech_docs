# Preface

!!! abstract "Abstract"
    This section introduces the most relevant information of the solution detailed in the playbook.

## Goal

<!-- What is the purpose of the solution -->

Develop a service that is able to recommend a top of recipes for the ingredients entered by the user and the set of recipes available in the database.

## Scope

<!-- What the solution will do and what it will not do -->

The service will receive the ingredients selected by the user, and a connection to the database with the available recipes, and it will return a top selection of recipes based on the attributes of recipes and ingredients. 

The services will not use the users' behavior to select the recommended recipes in this version.

## Technologies

<!-- Show the most relevant technologies used, mentioning the version if possible. You can group them into sections if you want -->

These are the most relevant technologies used during the development.

### Languages

|Name   | Version  | Description |
|---|---|---|
|Python | 3.8   | Main development |
|Bash   | 5.0   | Util scripts     |


### Data Processing

|Name   | Version  | Description |
|---|---|---|
|Pandas | 1.1  | Tabular data manipulation |
|Scikit-learn | 0.23   | Columns processing for scoring  |

### Messages broker

|Name   | Version  | Description |
|---|---|---|
|Aio-pika | 6.7  | Connection to RabbitMQ with asyncio |

### Testing 

|Name   | Version  | Description |
|---|---|---|
|Pytest | 6.2 | Unit and System testing of service |

## Team

<!-- Tag the users of team members, mentioning the adopted roles and the main responsibilities taken -->

- **Leandro Ferrado** ([@leferrad](https://github.com/leferrad)) - Data Scientist & Backend developer
    - Implement algorithm to recommend recipes
    - Data quality control of recipes stored in database
    - Develop services for recipes recommender
