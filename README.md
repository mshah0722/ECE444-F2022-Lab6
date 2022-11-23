# ECE444-F2022-Lab6
This repository is a walkthrough of: https://github.com/mjhea0/flaskr-tdd

## My Heroku Deployment for flaskr-tdd part of lab
https://safe-shelf-35695.herokuapp.com/

## Tests Written by Myself
I wrote all the tests for testing valid and invalid student reviews scenarios:
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-8-8ball/blob/main/Education_Pathways/tests/test_app.py#L174-L276

This includes verifying length constraints for review title and review body, verifying various counts for the review fields, and etc.
Overall, the goal is to make sure that the review meets the overall standards for all fields and checking positive and negative scenarios.

## Pros of TDD
There are several benefits to test-driven development (TDD). One advantage of TDD is that it encourages good design principles since it results in the creation of modular code. TDD allows you to concentrate on the creation of one sub-feature at a time, allowing you to chip away at a larger feature/functionality one unit step at a time. Additionally, it facilitates the discovery of minor problems, reducing faults and bugs as you develop. This is amazing since considerable time is saved later when debugging becomes easier since problems are resolved as soon as they are discovered. TDD also limits developers to only writing essential code and only focusing on having all the required test cases passing. Furthermore, TDD makes collaborative coding easier since developers can modify other developers' code and instantly run the tests to determine the effects of their changes. Lastly, the tests can also be a part of incremental regression testing which can be used to ensure that the development of a new feature does not break an existing feature. Evidently, implementing a test-driven methodology is beneficial from the start of the development process to the end. 

## Cons of TDD
On the other hand, Test Driven Development also has certain drawbacks. Firstly, one of the main drawbacks to TDD is that it can be time-consuming and often slow down development. Before writing the actual code for any new project that you are assigned to, the tests must first be written. Another drawback is that the tests need to be updated. Before making changes to the implementation code, it is necessary to alter the tests linked to the requirements as they change for the product. In order for TDD to function properly and keep the system from failing, the entire development team must collaborate and keep up with their tests. It can be very challenging to implement TDD on legacy code or other people's code which you have a limited understanding of initially. This will cause lots of time to be spent following through existing code with examples to create effective tests to ensure standards are being met and tests are passing. Overall, these cons prove to be a roadblock for scenarios where one might want to implement TDD.