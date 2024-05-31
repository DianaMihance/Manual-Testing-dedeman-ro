# Testing Project for dedeman.ro

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

## Application under test: dedeman.ro

Tools used: Jira, Zephyr Squad.

Functional specifications:

The below stories were created in Jira and describe the functional specifications of the modules named: "Contul meu", "Comenzile mele", "Favorite" ,"Abonari", "Setari", "Categorii produse", Search bar", "Authentification" for which the final project is performed upon.

![stories](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/ff625825-4db1-4b7b-a1e6-50daaf1291ce)


![authentification1](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/1911062f-dab4-42c9-95da-d0bb97ca5d88)


![authentification2](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/f9b2ee12-7517-43c9-bb3d-3acc0e90e176)


![search bar 1](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/81074e44-3721-4473-8735-0de3417cb2a9)



![search bar 2](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/6ecac75c-e954-4219-a073-62ad8fcf8ab7)



Here you can find the release that was created for this project:

![release](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/b18c3cba-75de-4f0e-87e4-b4c8e2beb708)


The test process was performed based on the standard test process as described below.

1.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

1.1.1. Roles asigned to the project and persons allocated


    Project manager: Iancu Irina
    Product owner : Ionescu Vlad
    Software developer : Pop Adela
    QA Engineer : Mihance Diana

1.1.2 Entry criteria defined

Testing can start when the following are fulfilled:
 
 Implementation of the feature is done and reviewed

 A pull request is opened on the ticket
 
 QA has all required info to test
 
 Stable Pull request environment was created
 
 Smoke test passed 

 Testing environment is up and running

1.1.3 Exit criteria defined

Testing can end when:

All acceptance criteria are met for a story

Defect is fixed and the change did not break something else

90% of tests are passed

No Critical issues have Open status

Update tests are 100% passed (update tests will not generate other new issues that impact the application)

1.1.4 Test scope

Tests in scope:

The tests are ment to determine the good function of some parts of the application .

Functional testing verifies that software features work as intended.

Functionalities in scope: uppdating the password, log in form, sorting the product list, add a product to favorite list, placing an order.

Functional testing, exploratory testing, positive and negative testing were used in this project.

Only Web applications will be tested.

Levels of testing:

● Component testing

Tests not in scope:

Non-functional testing like stress, performance is beyond scope of this project.
No QA support for mobile applications developed.
Automation testing is beyond scope.


1.1.5 Risks detected

Risks and mitigation:

a) Risk: Features are implemented with delay

Impact: Available testing time is reduced.

Action: Testing prioritization. Get help with testing from developers.

b) Risk: Unexpected PTOs / medical leave.

Impact: Possible delay of the release.

Action: Resources will be added to the testing team.

c) Risk: Non-functional environments

Impact: Available testing time is reduced. Possible delay of the release.

Action: Test on local environment if possible.


1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

1.2 Test Monitoring and Control

![test metrics](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/823a3dcf-1e2b-4316-b005-7e810ed525fa)

There are 7 stories and 15 tests executed. 4 bugs were found during the process.


1.3 Test Analysis

The testing process will be executed based on the application requirements. 

The following test conditions were found:

![teste 1](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/efe04438-39cb-4209-bf2f-7ca5dca1484b)

![teste 2](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/8fee7761-039f-4d8b-8891-fa27d565a83f)



1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. Here are some examples of test cases .

![test case 1](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/d921f967-ca96-41b8-b7d5-8395b7e6847b)

![test case 2](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/4ca545aa-3edc-49a8-a8e2-40ecd540cd6b)

![test case 3](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/e57651fa-83e9-419d-85c6-51bdbd46d577)

![test case 4](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/2914630a-1a85-4c0a-bf30-4c4dcf8dd588)


1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

The web site functionalities to be tested are ready .

1.6. Test Execution

Test cases are executed on the created test Cycle summary: "Project one"

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

![bug 1](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/38a6d0f1-41c8-4ac2-b7b4-25a2ded4eb7b)

![bug 2](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/81270584-e129-4699-921c-d42df60070e7)

![bug 3](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/fd2ff5b1-7d00-45c5-aacd-451cf40eb20a)

![bug 4](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/9cb0042a-509c-4423-87e2-5273d70e79ca)


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.


1.7 Test Completion 

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![matricea](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/0e8396ad-30a2-4720-8a66-639fd9a7ceee)


Test execution chart was generated and can be found below.

![dasboard nou](https://github.com/DianaMihance/manual_testing_jira_dedeman/assets/167775231/43a55cb4-df88-44b8-a420-bc8aabfe317a)

The final report shows that a number of 3 tests have failed of a total of 15 tests.

A number of 4 total bugs were found, from which the priority is:1 is high and 3 are medium.

15 tests were created and executed so far . There would be more tests to be created because the project is more complex and there are still some functionalities that were not tested yet. The bugs that were found have a small impact on the product launch and they can be fixed easily.


