## Magento 2 Demo

1.	Introduction
   
     1.1.	Project Objective
  	
         1.1.1.	Application web site:
    
         1.1.2.	Documentation:
     
     1.2.	Functionalities in scope
   
    1.3.	Functionalities and tests out of scope
   
2.	Test process
   
     2.1.	Test planning
  
          2.1.1.	Roles and responsibilities
    
          2.1.2.	Entry criteria:
    
          2.1.3.	Exit criteria:
    
          2.1.4.	Risks:
    
     2.2.	Test analysis
  
     2.3.	Test design
  
     2.4.	Test implementation
  
     2.5.	Test execution
  
     2.6.	Test closure
  
     2.7.	Test monitoring and control
  
3.	Test deliverables
   
     3.1.	Test plan
  
     3.2.	Test conditions
  
     3.3.	Test cases
  
     3.4.	Daily/Weekly/Monthly test summary report
  
     3.5.	Traceability matrix
  
     3.6.	Test case results
  
     3.7.	Bugs report
  
     3.8.	Test completion report
  
     3.9.	Schedule
  


### Revision History
| Date       | Description              | Author         |Comments    |
| ---------- | ------------------------ | -------------- |------------|
| 28.02.2024 | Test Plan for Magento 2  | Dăneasă Mihai  |Version 1.0 |

### 1.	Introduction
Welcome to the next generation of the world’s leading digital commerce platform! Built on open-source technology, Magento Commerce provides online merchants with unparalleled flexibility and control over the look, content, and functionality of their online stores. Magento’s intuitive Admin features powerful marketing, search engine optimization, and product management tools that give you the power to create sites that are tailored to your unique business needs. Robust and scalable, Magento offers you a stable, secure, and customizable solution for your growing business.

#### 1.1.	Project Objective
We try to raise the trust in the quality of the project as high as possible by finding new possible defects and propose them for solve to the development team.

#### 1.1.1.	Application web site: 
•	Frontend: https://osc-ultimate-demo.mageplaza.com/ 

•	Backend: https://osc-ultimate-demo.mageplaza.com/admin/admin/dashboard/ 

#### 1.1.2.	Documentation: 
•	https://inchoo.net/ux-ui-design/magento-2-luma-theme-under-the-scope/  

•	https://www.mageplaza.com/kb/magento-2-demo.html#undefined 

•	https://docs.mageplaza.com/magento/one-step-checkout/standard/ 

•	chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://docs.magento.com/m2/pdf/ce/Magento-Community-Edition-2.1-User-Guide.pdf

•	chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://commercemarketplace.adobe.com/media/catalog/product/magewares-module-mwcartreminder-1-2-0-ce/user_guides.pdf

#### 1.2.	Functionalities and test in scope
•	All features/functionalities/capabilities of Frontend module will be tested using the following testing types: functional testing, localization testing, acceptance testing, component testing, compatibility testing.

•	The Magento 2 application will be tested on latest versions of Mozilla Firefox, Chrome and Microsoft Edge. 

#### 1.3.	Functionalities and tests out of scope
•	Non-functional testing like stress testing, performance testing, usability testing, portability testing, compliance regulatory testing, security testing, load testing, volume testing, spike testing, scalability testing, reliability testing, system testing, and maintenance testing is beyond scope of this project.

•	Automation testing is beyond scope.

•	QA of the module on the Mobile application is beyond scope.

•	All features that are not under Frontend module.

### 2.	Test process.
#### 2.1.	Test planning.
##### 2.1.1.	Roles and responsibilities
| Function              | Roles and responsibilities                             |
|-----------------------|--------------------------------------------------------|
| Mihai -QA junior      | will test: User Management, Job, Qualifications        |
| QA Senior             | will test: Organization, Nationalities, Configuration  |

#### 2.1.2.	 Entry criteria:
•	Smoke test passed (being the most basic type of test, this is a very important entry criterion in the process of testing)

•	Testing environment is up and running.

•	Roles and responsibilities for the project are allocated. 

•	Functional business specifications are defined.

#### 2.1.3.	 Exit criteria:
•	100% of tests are executed. 

•	90% of tests are passed.

•	No Critical defects have Open status.

•	User Add functionality tests are 100% passed.

•	Exploratory testing was performed on Frontend Module.

#### 2.1.4.	 Risks:
•	Stability risks (crashes, disconnects, etc.).

•	One of the browsers might have performance issues.

•	The web page pagination could be impacted when opened on mobile devices.

•	New browsers might not be supported.

### 2.2.	Test analysis. 
•	Analyze the business requirements to make sure that we have all the details for creating the test conditions.

•	Write test conditions (What?)

•	We plan on running a full regression test on the current version.

### 2.3.	Test design.
•	All the test cases (How?) are written and reviewed. 

•	All test cases are created in Jira as test management tool.

### 2.4.	Test implementation.
•	All the test data is available and reviewed (test data = email examples, password examples, users).

•	This test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority.

•	Create the test suites (Cycle Summary) (grouped by release version or testing type)

### 2.5.	Test execution.
•	The tests will be executed on the latest versions of browsers: Chrome, Mozilla Firefox and Microsoft Edge. If time will be available, we will extend tests on other browsers. 

•	Bugs (defects) will be created based on the failed test cases. 

•	The full regression testing will be done after new application changes.

•	Retesting will be done after a bug fix.

### 2.6.	Test closure.
•	At least 90% of tests are passed.

•	No Critical issues have Open status.

### 2.7.	Test monitoring and control.
•	Status reports will be generated to reflect the status of testing process.

•	In case of major problems, control measures will be taken. 

## 3.	Test deliverables.

### 3.1.	Test plan. 
https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20plan.pdf

### 3.2.	Test conditions. 
The test conditions will be created based on the business requirements validated in the test analysis phase and will represent the features to be tested and transformed into test cases.

•	test conditions will be exported from Jira and added here. 

### 3.3.	Test cases.
https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20cases.pdf

### 3.4.	Daily/Weekly/Monthly test summary report
![Imagine 1](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20summary%201.jpg)

![Imagine 2](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20summary%202.jpg)

### 3.5.	Traceability matrix
https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Traceability.xlsx

https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Traceability.pdf

### 3.6.	Test case results.
https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Taste%20cases%20results.pdf

### 3.7.	Bugs report.
https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Bug%20reports.pdf

### 3.8.	Test completion report.
![Imagine 9](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20execution.jpg)

![Imagine 3](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20execution%20Daily.jpg)

![Imagine 4](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20execution%201.jpg)

![Imagine 5](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Test%20execution%202.jpg)

![Imagine 6](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Execution%20list%201.jpg)

![Imagine 7](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Execution%20list%202.jpg)

![Imagine 8](https://github.com/mihaidaneasa/Magento-2-Demo/blob/main/Execution%20list%203.jpg)



