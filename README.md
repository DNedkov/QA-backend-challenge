# QA-backend-challenge
QA Deyan Nedkov

## Hi
Here is my prefered solution of the challange that includes postman collection with name doodle.json.

#### Conent:

1. [Setup](#Setup)
2. [How to](#How-to)
4. [Findings](#Findings)
5. [Test results](#Test-Results)


## Setup
<a name="Setup"/>

To execue the test suite via Postman, you need to install the ***[Postman app.](https://www.postman.com/downloads/)***.</br>
To execute the tests via command line collection runner for Postman, you need to isntall Newman. </br> 
To run Newman install ***[Node.js](https://nodejs.org/en/download/)*** as as prerequisite.
Execute the following command in the terminal to install Newman -> npm install -g newman.


## How to:
<a name="How-to"/>

1. Run collection from Postman -> From the app main menu select "Import". Pick up the task solution file and once imported open the runner menu then select run in order to execute the test suite.

2. Run collection from Newman -> newman run "collection file.json" </br>
NOTE: In the project there are no enviroment or global variables, so this should be enough.

3. Reslolve PowerShell Script Not Digitally Signed -> Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass </br>
NOTE: Error: "ps1 is not digitally signed. The script will not execute on the system", could happen when a user tries to run the collection.



## Findings
<a name="Findings"/>


## Test Results
<a name="Test-Results"/>
