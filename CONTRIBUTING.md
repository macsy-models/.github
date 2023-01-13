# How to contribute

Welcome! By visiting this page, 
you've taken the first step toward becoming a contributor to macsy-models!

*macsy-models* is an umbrella organization to centralize, organize, share models for MacSyFinder. 
The models in *macsy-models* can be easily managed using the macsydata tool (shipped with macsyfinder).

## What skills do I need?

* Have biological knowledge on a macromolecular system.
* Be able to create hmm profiles.
* Some very basic knowledge on xml and git.


## How Can I Contribute?

We use Github to host the project, to submit an issue or a pull request,
you have to create a GitHub account.

There are mainly 2 ways to contribute:

1. contribute to an existing models repository
2. create a new models repository

## Contributing to an existing repository

### You want to ask/alert the maintainers of a problem

Go to the desired repository,
and pleaser ensure before submitting a new issue that the problem has not already been reported. 
If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

> **Note:**
> If you find a **Closed** issue that seems like it is the same thing that you're experiencing, 
> please open a new issue and include a link to the original issue in the body of your new one.

To open a new issue: click on Issues > New issue > Open a blank issue

### You have a proposal to fix/enhance the repository

* Fork the repository you want to contribute to
* Do the modifications
* Ask for a pull request

The acceptance of pull requests is the responsibility of the maintainers of each repository.

## Creating a new repository

If you want to create a new model package that you want to share with the MacSyFinder community

1. read the [modeller guide](https://macsyfinder.readthedocs.io/en/latest/modeler_guide/index.html) 
   to ensure that your model matches the recommendations 
2. ask for a new macsy-model repository by 
   [openning a new issue](https://github.com/macsy-models/.github/issues/new?assignees=bneron%2C+saphia&labels=ask+for+new+repository&template=ask-for-new-repos.md&title=%5BNew+Repos%5D).
   You'll own the repository, with all management rights (allow new contributors, implement changes...)
   By asking a repository in the macsy-models organization, you agree: 
   
   1. to follow the rules of a macsyfinder data package as described in the documentation.
   2. to follow the good practices to provide a package of good quality.
   3. to maintain the repository.

3. when your package is ready to be shared with the community, 
   tag it (for further details [read the modeller guide](https://macsyfinder.readthedocs.io/en/latest/modeler_guide/publish_package.html).
   Your package is now available to the community for searching and installing via the *macsydata* utility. 

> **Note:** 
> the description of the tag will be by default the last message of your latest commit. 
> You may thus want to make it meaningful. However of course, the list of the different 
> tagged versions (with tag version numbers) can also be maintained with their desription 
> on the README.md file of the repo. 
