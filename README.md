# Conventions
## My personal programming conventions

This repo contains a list about how I prefer to style and write my code, readmes, and basically anything related to programming/scripting.

Disclaimer: *This list is ever evolving and what you see here may not be what I follow all the time*

## Contents and how this list will work

This list of conventions will be seperated by language and topic

## General

### GitHub

This will contain a list of how I like to do things related to GitHub

1. Always include a README.md, .gitignore, and LICENSE.
2. Commit prefixes should follow [@frissyn](https://github.com/frissyn)'s prefixes: https://github.com/frissyn/commit-prefixes (I almost never follow this however lol)
3. Always include a description, topics, and check the required "Include in home page" boxes for the GitHub settings
4. In terms of a `.github` folder, I have never made one so I have no conventions related to that
5. Not exactly a GitHub thing but follow these guidelines for READMEs
	* Always have a title and description (title should be same as repo name and description/subtitle should be what is in GitHub settings panel for description)
	* Always include a developers/contributers list
	* Try to include a "made with" list highlighting what libraries were used to make the project
	* Always include a License section

### Programming/Scripting/Markup/Coding

This is a list of conventions I use for ALL coding regardless of what language

1. Indents are tabs
2. Indents are 4 spaces in length
3. Try to use command line rather than IDE defaults for configuration and testing. Use IDE if required.
4. In curly brace langs, always type space before adding a `{`

### Editors

1. Max line width depends on editor and free space for editor
2. Line wrap always

## Java

* Use the latest OpenJDK/AdoptOpenJDK LTS release of java (As of July 2021, Java 11. Switch to Java 17 expected to be released on September 2021)
* Use Eclipse/Intellij for Java. Stronger machines should prefer intellij for its modern features but an older pc should prefer eclipse because intellij is much more heavy
* Use Maven over Gradle for build system

## ECMAScript (JavaScript) and NodeJS

* Always use modern *vanilla* JavaScript (ESM, promises, `let` and `const` (no `var` unless I specifically want function scoped variable))
* Use `() => { }` to declare functions rather than `function() { }`
* Keep libraries to a minimum

This repo is a Work In Progress.










