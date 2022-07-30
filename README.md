# Explain For All Repos:

## The overall flow of is:

* A dev branch is created from main
* Feature branches are created from dev
* When a feature is complete it is merged into the dev branch
* When finish development, need to create release branch
* A release branch is created from dev
* When the release branch is done it is merged into develop and main
* If an issue in main is detected a hotfix branch is created from main
* Once the hotfix is complete it is merged to both develop and main

[explanation with git syntax](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

![image](https://user-images.githubusercontent.com/86562519/181935345-22a3ed6a-9fef-4191-951d-05a33f03f75d.png)

