# rubicon-nl
This branch contains guidelines, scripts and templates for managing this organization and its repositories

## Repository guidelines
To ensure a way of working and a level of code quality newly created repositories must have at least the following settings;

### Default branch
Master is the default branch for the repository

### Branch protection rules
The following protection rules must be enabled en configured
* Require pull request reviews before merging. *At least 1 approving and code owners review is required*
* Require status checks to pass before merging
* Require branches to be up to date before merging
* Restrict who can push to matching branches

## Issue templates
When your repository will be used by users outside the organisation its useful to set up issue templates.
For now you can use the default *Bug* and *Feature* template given by github.

## Action templates
In the [action-template](https://github.com/rubicon-n/rubicon-nl) folder you can find action templates for the following project types
* Dotnet Core
* Dotnet
* Angular
* Typescript
