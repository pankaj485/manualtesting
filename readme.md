# [learning resource](https://www.youtube.com/watch?v=QJqNYhiHysM&t=724s)

[why testing is required](#why-testing-is-required)

[types of testing](#types-of-testing)

[STLC(Software Testing Life Cycle)](#stlcsoftware-testing-life-cycle)

[v model](#v-model)

[Verification](#verification)

[validation](#validation)

[Review, Walkthrough and Inspection](#review-walkthrough-and-inspection)

[Review](#review)

[walkthrough](#walkthrough)

[Inspection](#inspection)

[Validation, Dyanamic Testing(More focus on Software)](#validation-dyanamic-testingmore-focus-on-software)

[System Testing (Black box testing)](#system-testing-black-box-testing)

[Automation testing includes](#automation-testing-includes)

[Functional Testing and Non-Functional testing](#functional-testing-and-non-functional-testing)

[Test Design techniques](#test-case-contents)

[BVA](#bva)

[ECP](#ecp)

[Decision table](#decision-table)

[Stage transition](#stage-transition)

[Error guessing](#error-guessing)

[Testing Terminologies](#testing-terminologies)

[Software Testing Life Cycle(STLC)](#software-testing-life-cyclestlc)

[Test Plan Document](#test-case-contents)

[Use case, Test Scenario & Test Case](#use-case-test-scenario--test-case)

[Test case contents](#test-case-contents)

[Requirement Traceability Matrix (RTM)](#requirement-traceability-matrix-rtm)

[Test Enviornment](#test-enviornment)

[Test Execttion](#test-execttion)

[following criteria has to be prepared before test execution](#following-criteria-has-to-be-prepared-before-test-execution)

[Activities](#activities)

[guidelines for test execution](#guidelines-for-test-execution)

[Defects/Bugs](#defectsbugs)

[Defect Report contents](#defect-report-contents)

[defects categorization](#defects-categorization)

[Defect Resolution](#defect-resolution)

[Bug life cycle](#bug-life-cycle)

[Defect Metrics](#defect-metrics)

[Test Cycle closure](#test-cycle-closure)

[test matrics](#test-matrics)

[test efficiency vs test effectiveness](#test-efficiency-vs-test-effectiveness)

---

- project => made specifically for particular organization or person

- product => can be used by alot of people i.e for marketing purpose

- STLC => software testing life cycle

- testing is done to find bug and resolve so that all the features are woking up to the mark as expected by client.

- If any functionality isn't working or any bug arises then it has to be resolved which is done by testing

- Q.A stands for Quality Assurance

### **why testing is required**

- testing doesn't require exprience in developement

- Developer does unit testing and integration testing but not entire testing process which deals with internal working like logics of the program and flow of data from one page to another or relation of one page to another.
  It's also reffered as white box testing

- Q.A testing involves execute files or also called as build files which on executing gives the enviornment of the actual product but not the acutal codes for testing.

- But before getting that even tester has to know and understand about customer requirements and features the project/product is going to carry so that they can write test cases.
  It's also reffered as black box testing

### **types of testing**

1. white box testing
   - unit testing
   - integration testing
2. Black box testing
   - system testing
   - UAT (User )

### **STLC(Software Testing Life Cycle)**

All companies use agile model nowdays but the life cycle was started with V model.

### **v model**

Isn't used nowdays.
It mas main 2 phases

1. Verification
2. Validation

Verification is done in the document and validation is done in software

### **Verification**

Process of reviewing the main documentation.
Verification should be done before software is ready.
Also called as static testing

Phases

1. BRS/CRS/URS docs
2. SRS: software requirement specification
3. HLD: high level design
4. LLD: low leel design
5. coding

whole project is divided into models and submodels.
devleoper starts coding based on LLD.

### **validation**

it's actual process of testing.
Integration and Unit testing comes under white box testing.
System Testing, User acceptacnce Testing.
Also called as dynamic testing.
Mainly focused on the codes part.

### **Review, Walkthrough and Inspection**

It comes under the verification/static testing part.
It has 3 main phases:

1. Review
2. Walkthrough
3. Inspection

### **Review**

once we will have requirement we will have req review.
once we will have design we will have design review.
once we will have test plan we will have test plan review.
once we will have test case we will have test case review.

Review is mainly focused on verification of the documentation.
It's done individually

### **walkthrough**

Is formal review and can discuss the issues within team.
It can happen any time and conclude just like no schedule as such it can be done at any time.

It's done in team

### **Inspection**

Is formal process where all team members are present

Must have presons are:

1.  Author
2.  Writer
3.  Moderator
4.  Team(QA, Dev, Project management team)

### **Validation/ Dyanamic Testing(More focus on Software )**

Unit testing, integration, system testing, UA testing comes under this phase

Terms used on testing:

1. Q.A : Quality Assurance
2. Q.C : Quality Control
3. Q.E : Quality Engineering

Q.A is mainly realted process and related to quality. It defines the process. It's for prevention of defects. Those doesn't take part in the testing comes on this category like managers/product managers/Leads.

Q.C is mainly realted to testing process. It is detection activity. It follows the process of Q.A. All testers comes under Q.C i.e who takes part in testing

Q.E is to prevent defects. It is prevention activity. All automation testers comes under this category. It involves the testers writing code to automate testing

### **System Testing (Black box testing)**

Actual testing is done.
Understand Requirements.
Define more and more requirements.
Involves writing, executing test cases, find defects and report them to devs and participate review meetings which is main job.

### **Automation testing includes**

- writing automation scripts.
- Executing automation scripts.
- Generate reports.
- Status reports send to management team.

### **Functional Testing and Non-Functional testing**

### **Test Design techniques**

testing technique helps to design better cases.
It helps to reduce num of test cases while increasing test coverage.
Helps to identify conditions that are otherwise difficult to recognize.

How to apply those techniques?

- Bundary Valule Analysis (BVA)
- Equivalence Class Partitioning (ECP)
- Decision table based testing
- State transition
- Error Guessing

### **BVA**

- is range check
- min, max , inside or outside of bundry test should be passed
- e.g length of password

### **ECP**

- is value check
- e.g characters used in phone number

### **Decision table**

- Also called cause-effect table
- Deals with combinations of inputs
- We take conditions as inputs and actions as outputs
- e.g for online transactin, if account is already is added, account is approved, otp matched, money is enough then money can be transferred, show messages and other actions based on past activities/inputs
- we have list of conditions and actions. Any numbers can be present. e.g ,condition1, condition2, Action1, Action2
- Actions are based on inputs

### **Stage transition**

- changes in input conditions change the state of the Application Under Test(AUT)
- Allows the tester tto test the behavior of an AUT
- Testing team provides positive as well as negative input test values for evaluating the system behaviour
- e.g on providing wrong pin for 3 consecutive times, it's locked for particular times but if input right inside of particular range, it allows to widthdraw

### **Error guessing**

- technique to find bug based on testers prior exprience
- e.g submiting form without entering values, entering invalid values like alphabets inside numeric field
- knowledge of the typical implementation error is necessary
- Evaluation of historical data and test results are involved

### **Testing Terminologies**

1. Sanity testing vs Smoke testing

   - Sanity testing verifies new functionality, bug fixes in the build. It's done in initial phases
   - Smoke testing verifies critical functionalities like Application starts successfully ?
   - After passing these tests System and Regression testing is done. It's done in later phases

2. Re-testing vs Regression Testing

   - Re-testing is testing of already tested program after modification to discover new defects. It deals with old freatures only
   - Regression testing is testing of the new functionalities added. It deals with new features only
   - It's done in following cases
     - New functionalities are added
     - Change requirement
     - Defect fixing
     - Perfomance issue fix
     - Enviornment change (updating DB from sql to oracle )

3. Globalization Testing vs Localization Testing

   - Localization testing is process for checking localized version of product for particular culture or locale settings. Affects UI and Content. e.g website containing multiple langauges, date formats
   - Globalization testing is to ensure that application can functino in any culture or locale. Also called as internationalization testing.

4. End-To-End Testing

   - Testing overall functionalities of the system including data integration among all the modules

5. Exploratory Testing

   - It's about discovery, investigation and learning of the platform just to get knowledge of the platform
   - test cases aren't created in advance bu testers check system on the fly
   - no documentation is included
   - is more on testing as a "thinking" activity
   - when to use?
     - when test team has exprienced testers
     - when early iteration is required
     - when there is critical application
     - when new testers entered into the team and learning

6. Adhoc testing

- doesn't include proper plan or flow of testing
- is informal testing with aim to break the system
- main purpose is to find as much bug as possible
- prior knowledge in testing is included
- randomly testing is done without any requirement documentation, design documentaion

7. Adhoc Testing vs Monkey Testing vs Exploratory Testing
   - All testing are quite similar to each other
   - similar points are:
     1. no documention included
     2. is informal testing
     3. no planning included
     4. Random testing
     5. Intention is to break application and find out corner defects
   - Adhoc testing:
     1. Any appications can be tested
     2. Tester should know Application functionality
   - Monkey testing:
     1. Gaming applications are tested
     2. Testers doesn't know Application functionality
   - Exploratory testing:
     1. Any application new to tester is tested
     2. Testers doesn't know application functionality

### **Software Testing Life Cycle(STLC)**

02:58 in course

Steps included in STLC

Recommended to watch videos for better understanding

1. Requirement Analysis
2. Test planning
   - what to test
   - how to test
   - when to test
3. Test designing
4. Enviornment setup
5. Test execution
6. Defect Reporting & Tracking
7. Test Closoure/Sign-Off

### **Test Plan Document**

- Test plan is document containing scope of the testing
- About timelines, introduction, peoples involving, functionalities to test, objecteive, test method, documentation

### **Use case, Test Scenario & Test Case**

1. Use casae describes functional requirement and is prepared by Buisness Analyst(BA)

Use case contains:

- Actor
- Action/Flow
- Outcome

2. Test Scenario is the possible area to be tested (What to be tested)

- It's more of what to be tested

3. Test Case contains test steps and procedures and is prepared by Test Engineer

- It's more of how to be tested
- It's derived from test scenario
- Describes test steps, expected results and actual results
- it includes set of input values, execution precondition, expected Results and executed post

e.g scenario for login and cases of inputs on various conditions

#### **Test case contents**

following are test case contents

1.  Test case id
2.  test case title
3.  description
4.  pre-condition
5.  priority(p0,p1,p2) - order
6.  requirement id
7.  steps/actions
8.  expected results
9.  actual result
10. test data

- every test case and defect has unique id with particular format (e.g prjname_moudle_testcase_num)
- title should be readable. are one line
- description is explaination of title
- preconditions are test conditions to execute in particular order (priority of test cases).p0 and p1 are most important
- every document has requirement ids
- steps test cases has steps and actions to follow
- expected result and actual result are self explainatory
- test data are data used while testing

### **Requirement Traceability Matrix (RTM)**

- test design phase also need to include the RTM
- it captures all requirements proposed by the client
- it maps and traces user requirement with test cases
- it's main purpose is to see that all test cases are covered so that no functionality should miss while doing testing
- it includes
  - requirement id
  - test case id
- it confirms 100% test coverace
- it highlights any requirements missing or document inconsistenties

### **Test Enviornment**

- is setup of software and hardware for testing teams to execute test cases
- it supports execution with hardeare, softeare and network configured
- is enviornment to test the application without affecting the live production
- test bed/enviornment is used ony by testers not devs
- envolves both hardware and software

### **Test Execttion**

- provides defect and test case execution report with completed results

### **following criteria has to be prepared before test execution**

1. test cases
2. test data
3. test plan
4. test strategy

#### **Activities**

1. Test cases are executed based on planning
2. status of test cases are marked like passed, failed, blocked, run and others
3. Documentation of failed test cases are assigned bug ids
4. All the blocked and failed test cases are assigned bug ids
5. Reseting once the defects are fixed
6. Defects are tracked till closure

### **guidelines for test execution**

- build has to be deployed to the quality assurance enviornment is most important part
- test execution is done in QA enviornment
- test exectuion happens in least two cycles
- contains executing test cases + test scripts(if automation)
- exploratory tests are carried out once the build is ready for testing

### **Defects/Bugs**

- any mismatched functionality is called defect/bug/isse
- test engineers report defect to developers through templates or tools
  - defect reporting tools are
    1. Clear Quest
    2. DevTrack
    3. Jira
    4. Quality Center
    5. Bug jilla
- failure, error and defect/bug/issue aren't same to each other
  - error happens in programing
  - defect/bug/issue is related to mismatch to functionality
  - failure is related to customer prespertive. defects lead to failure

### **Defect Report contents**

1. Defect ID
2. Defect Description
3. Version
4. Steps
5. Date Raised
6. Reference
7. Detected By
8. Status
9. Fixed by
10. Date closed
11. Severity
12. Priority

- severity and priority is provided by testers openion acc to impact of the defect

### **defects categorization**

- to determine seerity and priority of the cases is very important and critical skill

1. Severity

   1. Critical (can't move further without resolving it e.g authentication checking)
   2. High
   3. Medium
   4. low (mostly ui falls here)

2. Priority
   1. p1 (have to check fist )
   2. p2
   3. p3

### **Defect Resolution**

- after reciving defect report from the testing team developement team conduct a review meeting to fix defects.
- they send Resolution type to testing team for further communication

- Resolution Types:
  1. Accept
  2. Rejcet
  3. Duplicate
  4. Enhancement
  5. Need more information
  6. Not Reproducible
  7. Fixed
  8. As designed

### **Bug life cycle**

- contains all the phases/stages bugs goes on throught the project

### **Defect Metrics**

- is important since it gives the data about info of effectiveness of the testing done and perfomance
- we have 2 important matrics

  1.  defect rejection ratio
  2.  defect leakage ratio

- defect rejection ratio = (num of defects rejected / total defects raised)\*100
- defect leakage ratio = (num of defect missed/ total defects of the software)\*100

### **Test Cycle closure**

- afer all testing done the test certification is done
- activities

  1.  evaluate cycle completion criteria based on Time, Test coverage, Cost, Software, Critical Buisness Objectives, Quality
  2.  Prepare test metrices based on above parameters
  3.  document the learningout of the porject
  4.  prepare test clouser report
  5.  qualitative and quantitative reporting of quality of the work product to the customer
  6.  test result analysis to find out defect distribution by type and severity

- Deliverables

1.  test closoure report
2.  test metrics

### **test matrics**

- is evaluated after all the project is been done
- various input data is needed to calculate the matrics
- inputs are:

  1.  % of test cases executed
  2.  % of test cases not executed
  3.  % of test cases passed
  4.  % of test cases not passed
  5.  % of test cases blocked
  6.  defect density
  7.  defect removal efficency (is calculated after post production)
  8.  defect leakage
  9.  defect rejection ratio
  10. defect age (duration of fixing)
  11. customer satisfaction(num of complaint per period of time)

- missed defects: defects found my customers

### **test efficiency vs test effectiveness**

- efficiency is resource consumed in order to achive their goal. It's about effectiveness resouce utilization
- effectiveness is about how well user achives goal they set out to achive using the system(process). It's about process utilization
