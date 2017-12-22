# Goby template for Platform.sh

![Goby](http://i.imgur.com/ElGAzRn.png?3)
=========

**Goby** is an object-oriented interpreter language deeply inspired by **Ruby** as well as its core implementation by 100% pure **Go**. Moreover, it has standard libraries to provide several features such as the Plugin system. Learn more on http://goby-lang.org 

**[https://platform.sh](Platform.sh)** is a second-generation Platform-as-a-Service built especially for continuous deployment. It allows you to host web applications on the cloud while making your development and testing workflows more productive.

This project provides a minimalistic starting point for building and deploying a Goby application on Platform.sh. It is only a basic Hello-World level example, but can be used as the basis for an actual project.

## Starting a new project

To start a new project based on this template, follow these 3 simple steps:

1. Clone this repository locally.  You may optionally remove the `origin` remote or remove the `.git` directory and re-init the project if you want a clean history.

2. Create a new project through the Platform.sh user interface and select "Import an existing project" when prompted.

3. Run the provided Git commands to add a Platform.sh remote and push the code to the Platform.sh repository.

That's it!  You now have a working "hello world" level project you can build on.

## Using as a reference

You can also use this repository as a reference for your own projects, and borrow whatever code is needed. 

The most important parts are the `.platform.app.yaml` file and the `.platform` directory, which define how a Platform.sh project will be configured.