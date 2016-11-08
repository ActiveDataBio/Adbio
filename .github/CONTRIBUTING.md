#Contributing to Adbio
This project was created with [Spring Tool Suite](https://spring.io/tools) with the goal of allowing proteomic research scientist to:
* Analyze data visually and collabritivly through a web site like environment.
* Use Git and its built in versioning system to track all changes to the data and statistical tests.
* Use Docker to make it easy for users to install and run.

####Table Of Contents

[What should I know before I get started](#gettingStarted)
* [Code of Conduct](#gettingStarted_conduct)

[How Can I Contribute?](#contribute)
* [Reporting Bugs](#contribute_bug)
* [Suggesting Features](#contribute_features)
* [Do the work](#contribute_work)

[Style Guides](#styleguides)
* [Git Commit Messages](#styleguides_git)
* [Java Style Guide](#styleguides_java)
* [JavaScript Style Guide](styleguides_javascript)

Additional Notes



##<a name="gettingStarted"></a>What Should I Know Before I Get Started
###Requirements 
* [Spring Tool Suite(STS)](https://spring.io/tools/sts)
* [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* [R Script](https://www.r-project.org/)

###<a name="gettingStarted_conduct"></a>Code of Conduct

##<a name="contribute"></a>How Can I Contribute?
There are a few ways to contribute to Adbio.
* Reporting bugs because we can't catch everything.
* Suggesting features.
* Editing the code.

###<a name="contribute_bug"></a>Reporting Bugs
Report bugs by using Github issues but, before you do please search the issues board to check if the bug hasn't already but reported.
Please use this template and add the label bug when creating an issue for bugs
####<a name="contribute_bug_template"></a>Template For Submitting Bug Reports
```
[Short description of problem here]

**Expected behavior:**

[Describe expected behavior here]

**Observed behavior:**

[Describe observed behavior here]

**Reproduction Steps:**

1. [First Step]
2. [Second Step]
3. [Other Steps...]

**Screenshots and GIFs**

![Screenshots and GIFs which follow reproduction steps to demonstrate the problem](url)

**OS and version:** [Enter OS name and version here]

**Additional information:**

* Problem can be reliably reproduced, doesn't happen randomly: [Yes/No]
```
###<a name="contribute_features"></a>Suggesting Features
We welcome the submition of engancements to Adbio. Please use this as a guide to help maintainers and the comunity undersrtand your sugestion. Use Github issues to suggest enhancements to Adbio but, first check this list to be sure your suggestion isn't already there.
Please use this template and add the label enhancement.
####Template for suggesting features
```
[Short description of feature]

**Steps which explain the feature**

1. [First Step]
2. [Second Step]
3. [Other Steps...]

**Current and suggested behavior**

[Describe current and suggested behavior here]

**Why would the feature be useful to most users**

[Explain why the feature would be useful to most users]

[List some other applications where this enhancement exists]

**Screenshots and GIFs**

![Screenshots and GIFs which demonstrate the steps or part of Adbio the feature suggestion is related to](url)

**OS and Version:** [Enter OS name and version here]
```
###<a name="contribute_work"></a>Fixing Bugs or Adding Features
If interested in writing code for Adbio choose a bug or feature from the open issues. If you found a bug or want to add a feature that isn't listed please add it to Github issues before starting work on it. If fixing bugs clone the repository and make the necessary code changes to the *dev* branch. If adding features make a new branch using the name or shortened name of the feature. When finished editing the code create a new pull request for the branch. Any commits made should use the [git commit messages style guide](#styleguides_git). The code should be well commented and use the [Java style guide](#styleguides_java) or [JavaScript style guide](#styleguides_javascript). Write tests and be sure all tests pass before submitting the pull request.

##<a name="styleguides"></a>Style Guides
###<a name="styleguides_git"></a>Git Commit Messages
Use present tense e.g. fix bug not fixed bug

###<a name="styleguides_java"></a>Java Style Guide
All Java must comply with [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
###<a name="styleguides_javascript"></a>JavaScript Style Guide
