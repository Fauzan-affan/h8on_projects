# RCT 2 // Ecommerce Website

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

In the _Ecommerce_ project, you'll create an ecommerce website that able to display the goods in a list, add to cart, add to wishlist, search goods by its name and filter goods by category. When you add goods to cart, the cart page should contains the every goods you add before. The project emphasizes using React to build the app and Redux to maintain the state of every component. 

#### Get the Project

You have a few options to start developing this project:

* forking and cloning the start repository
* starting from scratch with make your own file

#### Starter Code

If you'd like to work locally on your own computer, fork and clone the starter repository.

The code in the starter repo contains all the CSS and HTML markup that may be used but omits the React and Redux code that is required to complete the project. This can save you some time if you don't wish to write all the CSS and HTML from scratch. The provided code will demonstrate a static HTML page of the finished application, but with no interactive functionality.

#### Starting from Scratch

If you'd like to start completely from scratch, you can make your own using the Create React App.

#### App Functionality

In this application, you will have 3 pages: main page, detail page, and cart page. The main page displays some component such as:

* Title
* Wishlist Button and Badges
* Cart Button and Badges
* Search Bar
* Dropdown to filter by Category
* List of Items containing Detail and Add to Cart button
* Add new Items at the bottom of page

The homepage allows you to search items quickly, add items to wishlist or cart, and filter item based on its category. The static home page \(and your completed app\) should look something like this.

Each item has a control that lets you select the item to wishlist or add to cart. When you select an item to wishlist, wishlist badges count should increase and when you click the wishlist button, it should display a dropdown/modal containing all items on your wishlist.

When you select an item to cart, cart badges count should increase and when you click the cart button, it should redirect you to cart page. The Cart page contains every items you added before in a list and remove button to remove items from cart. Also at the bottom of cart page we can see the grand total price of the items in cart.

The detail page should contains Title, Wishlist and Cart Button, item images, item description, price, add to cart and wishlist button with same functionality as referred above.

The main page also has a search form that allows you to find items based on its name.

The search form has a text input that may be used to filter the items quickly. As the value of the text input changes, the podcast that match that query are displayed on the page, along with a control that lets you view the detail of your items or add the items to cart.

When you click add new items button, it should launch a modal box containing new item form such as title, description, price, etc. You can click the save button and should redirect to homepage and see the new items you added in the list.

#### Submission Requirements

Your submission should include all of the files necessary to launch your web application on a browser. You can assume that your reviewer will have browser installed on their machine.

#### Considerations

The focus of this project is on writing functional React code, not on making the page beautiful. Feel free to spend some time working on your layout and CSS if you want to, but the goal for this project is correct functionality.

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

**Step 1 - Break The UI Into A Component Hierarchy.**

**Step 2 - Build A Static Version in React; including the search form, and every component needed.**

**Step 3 - Build Add new items form.**

**Step 4 - Identify The Minimal \(but complete\) Representation Of UI State.**

**Step 5 - Identify Where Your State Should Live.**

**Step 6 - Store all State in Redux.**

**Step 7 - Add Inverse Data Flow.**

**Step 8 - Make sure that everything works as expected.**

**Step 9 - Add navigation to / \(root page\).**

**Step 10 - Add finishing touches and make sure the project meets the rubric.**

Remember, this is just a template. As you build more projects, you'll modify this template to suit your needs. You may also find it more intuitive to use a different approach. Regardless of the approach you take, however, planning out your app is imperative to success.

### Projects Submission

#### Instructions

Please verify that your project adheres to our HTML, CSS, JavaScript, and Git style guidelines.

If you chose to develop on your local machine \(by either starting with the starter project or starting from scratch with Create React App\), you will need to:

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
| Is the application easy to install? | The application could be installed by executing npm install. |
| Does the application include README with clear installation and launch instructions? | An updated README that describes the project and has instructions for managing and launching the project is included. |

| Main Page |  |
| :--- | :--- |
| CRITERIA | SPECIFICATIONS |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |

| Detail Page |  |
| :--- | :--- |
| CRITERIA | SPECIFICATIONS |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |

| Cart Page |  |
| :--- | :--- |
| CRITERIA | SPECIFICATIONS |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |

| Code Functionality |  |
| :--- | :--- |
| CRITERIA | SPECIFICATIONS |
|  |  |
|  |  |
|  |  |
|  |  |
| Does the code run without errors? | The code runs without errors. There are no warnings that resulted from not following the best practices listed in the documentation. All code is functional and formatted properly. |

