# FSD 2 // Vue Converter

## Projects Concepts

### Approaching a Project

Developing a large project is hard. Don't just dive in and try to tackle the entire thing all at once. As the famous saying goes:

A goal without a plan is just a wish.

Start with a plan! Here are some steps that I like to follow when building a project:

* outline the steps needed to build the project
* draw the application
  * what individual page would look like
  * how the page are connected to each other
* write down the pseudocode
* develop the page piece by piece

And just before submitting:

* squash all bugs
* check the rubric and make sure that your project meets all requirements

Take it slow and practice your newly acquired skills. You've got this! 🙌🏼

If you get stuck, take advantage of your mentorship services.

### Project Overview

In the _Vue Converter Apps_ project, you'll create an app that allows you to convert length such as kilometre to metre and view the formula. The project emphasizes using Vue to maintain the front-end of the apps.

#### Get the Project

You have a few options to start developing this project:

* forking and cloning the start repository
* starting from scratch with make your own file

#### Starter Code

If you'd like to work locally on your own computer, fork and clone the starter repository.

The code in the starter repo contains all the CSS and HTML markup that may be used but omits the Vue  code that is required to complete the project. This can save you some time if you don't wish to write all the CSS and HTML from scratch. The provided code will demonstrate a static HTML page of the finished application, but with no interactive functionality.

#### Starting from Scratch

If you'd like to start completely from scratch, you can make your own files you need.

#### App Functionality

In this application, the main page displays only one page to show how to convert length. The converter must able to convert from smallest length unit to the largest length unit \(eg. convert km into mm and vice versa\).

The long unit starts based on the level of the stairs in sequence from bottom to top. The unit of length starts from the bottom up, for example: mm \(millimeter\), cm \(centimeter\), dm \(decimeter\), m \(meter\), dam \(dekameter\), hm \(hectometer\), km \(kilometer\). 

The way to change the length unit is if it goes up divided by 10 and goes down multiplied 10. To make it easier to calculate the length unit, you can use the level from the bottom up as a reference. A simple example of calculating a unit of length, for example \(1 mm = 0.1 cm\), \(1 cm = 0.01 m\), \(1 km = 1000 m\).

#### Submission Requirements

Your submission should include all of the files necessary to launch your web application on a browser. You can assume that your reviewer will have browser installed on their machine.

#### Considerations

The focus of this project is on writing functional Vue and Node code, not on making the page beautiful. Feel free to spend some time working on your layout and CSS if you want to, but the goal for this project is correct functionality.

### Project Instructions & Rubric

#### Before Submitting

Make sure your code adheres to our HTML, CSS, JavaScript, and Git style guidelines.

* KODEgree's HTML Style Guide
* KODEgree's CSS Style Guide
* KODEgree's JavaScript Style Guide
* KODEgree's Git Style Guide

We recommend using Git from the very beginning. Make sure to commit often and to use well-formatted commit messages that conform to our guidelines.

#### How will this project be evaluated

Your project will be evaluated by a KODEgree Code Reviewer according to the rubric. Be sure to review it thoroughly before you submit. All criteria must "meet specifications" in order to pass.

The project rubric is your source of truth while building this project. Save it to your browser bookmarks so you can access it easily!

#### Submission Instructions

If you choose to develop on your local machine you will need to:

Push your project to GitHub, making sure to push the master branch. On the project submission page choose the option "Submit with GitHub" Select the repository for this project \(you may need to connect your GitHub account first\).

### Step by Step Guide For Building Travel Guide Website

#### Planning Stage 📐

**Step 1 - Draw All of the Page of the App** We need to determine the look and functionality of each view in your app. One of the best approaches is to draw each view of the app on paper so that you'll have a good idea of what information and data you're planning to have on each page.

Instead of paper and pencil, you can be a bit more digital and use software for creating mockups. If you were given project specifications, check your mock against them to make sure that you have all of the required features. For the exercises that follow, your can just draw what you're trying to create on paper.

**Step 2 - Break Each View Into a Hierarchy of Components** For this step,

* draw boxes around every component; and
* arrange our components into a hierarchy

**Step 3 - Determine the Data Each Component Needs** For each component, determine which data is the component accessing, getting, modifying, or showing.

#### Coding Stage🔨

**Step 1 - Prepare a html element. Create an input tag for input and result, create combobox for different label, and v-on for trigger the action.**

**Step 2 - Add a new blank property for the containers.**

**Step 3 - Create watch property which contains functions to change value in the textbox besides length unit label.**

Remember, this is just a template. As you build more projects, you'll modify this template to suit your needs. You may also find it more intuitive to use a different approach. Regardless of the approach you take, however, planning out your app is imperative to success.

### Projects Submission

#### Instructions

Please verify that your project adheres to our HTML, CSS, JavaScript, and Git style guidelines.

If you chose to develop your project in your Workspace, you can submit directly from your Workspace. When you're ready to submit, go to your Workspace and just click the "Submit Project" button. That's all there is to it!

If you chose to develop on your local machine you will need to:

* Push your project to GitHub, making sure to push the master branch.
* On the project submission page choose the option "Submit with GitHub"
* Select the repository for this project \(you may need to connect your GitHub account first\).

#### Project Submission Checklist

Before submitting your project, please review and confirm the following items.

* I am confident all rubric items have been met and my project will pass as submitted. \(If not, I will discuss with my mentor prior to submitting.\)
* Project builds correctly without errors and runs.
* All required functionality exists and my project behaves as expected per the project's specifications.

Once you have checked all these items, you are ready to submit!

### Project Rubric

| Application Setup |  |
| :--- | :--- |
| CRITERIA | SPECIFICATIONS |
| Is the application easy to manage? | The application was created with separate css and js inside of each folder and index.html as an entry point for the website |
| Does the application include README with clear installation and launch instructions? | An updated README that describes the project and has instructions for managing and modifying the project is included. |

| Code Functionality |  |
| :--- | :--- |
| CRITERIA | SPECIFICATIONS |
| Can it convert all units of length? | The application must be able to convert all units of length, doesn't matter if they have a lot of textboxes, as long as all conversions can be done. |
| Does the application use conditional vue like v-if? | The application must use v-if, at least to set the conditions for conversion changes |
| Does the application use 2 ways data binding or v-model? | The application must use 2 ways of data binding, not one data binding such as v-bind |
| Does the application use event handlers from vue? | The application must use v-on to trigger the calling of a method or watch property |
| Does the code run without errors? | The code runs without errors. There are no warnings that resulted from not following the best practices listed in the documentation. All code is functional and formatted properly. |

