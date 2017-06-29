# Artificial Intelligence Engineer Nanodegree
## Intro to Natural Language Processing
### Project: Build an Alexa History Skill

Here I created my own Alexa Skill!. In this project, I built a fully functional skill for [Amazon’s Alexa](https://developer.amazon.com/alexa) that provides year-dated facts from AI History.  Through this process, I got to use the [Alexa Skills Kit (ASK)](https://developer.amazon.com/alexa-skills-kit) - a current state of the art API for building voice systems.  
![Alexa skill process overview](images/skillOverview.png)

#### Getting Started

#### Files
Install your starter code locally.
* Download or clone or from GitHub
    - **speechAssets/IntentSchema.json**  - intents definition for the interactive model
    - **speechAssets/SampleUtterances_en_US.txt** - utterances for the interactive model
    - **src/index.js** - skill logic and handlers to be run in AWS Lamda
    - **src/facts.js** - a list of facts that the skill will use in responses
    - **tests/*.js** - various unit tests to be run locally with mocha; you do not need to change these

#### Environment

##### 1. Install [Node.js](https://nodejs.org/) per instructions on the website for your machine.

##### 2. Install dependencies for the project

* Navigate to the `AIND-VUI-Alexa/src` directory and open a terminal window.  
* The dependencies we need are listed in the `package.json` file and include the [alexa-sdk](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs) library for Alexa as well as  [mocha](https://mochajs.org/) test framework for Node.js along with [chai](http://chaijs.com/) and [aws-lambda-mock-context](https://www.npmjs.com/package/aws-lambda-mock-context) for local unit testing.  Install them all with the following command:
```shell
$ npm install
```
* There should now be a directory named `node_modules` within the `src` directory.  This is how Node.js attaches libraries for your code.

##### 3. Unit testing
* You can now run the provided unit tests from the command line within the `src` directory with the following command.  Try it now:
```shell
$ npm test
```
The test code is in four parts:  "Part 1", "Part 2", "Part 3", and "Starter Code". The tests should pass .  You may have to scroll up to see all the passing tests.  

##### 4. Run the Starter Code on AWS Lambda
* Deploy the code to verify that it works with your accounts in its simple form.