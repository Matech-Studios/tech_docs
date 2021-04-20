# Chapter 3: Execution

!!! abstract "Abstract"
    This chapter covers the execution of the work based on the previous definitions done, in terms of developing, testing, and validating the solutions based on the agreed acceptance criteria. (**X min read**)

## Development

<!-- Describe all the work done to develop the code for the solution, using proper sections based on the methodology implemented -->

### Data Analysis

In order to ensure the database of recipes and ingredients as proper quality to implement the given approach, we must conduct a Data Quality Control. Check the [How-to: Data Quality Control](how-to/data_quality_control.md) document for details.

!!! info
    To be filled soon...

### Modeling

Scoring recipes based on:
- ...
- ...

!!! info
    To be filled soon...


### Service

A script is provided, which runs a consumer connected to RabbitMQ with aio-pika. 

Using asyncio library to have asynchronous behavior

!!! info
    To be filled soon...

## Testing

<!-- Describe the implemented tests for the solution -->

Unit testing for the score functions implemented

The integration tests are performed with the backend

!!! info
    To be filled soon...

## Deployment

<!-- Document the work done to deploy the implemented solution in a testing environment for testing purposes -->

DevOps team configured an Azure pipeline.. We provided one Dockerfile for the Analytics service, and one for the RabbitMQ service.

!!! info
    To be filled soon...


