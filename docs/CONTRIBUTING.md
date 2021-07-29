# Contributing

:+1::tada: Who's the rockstar? You are the rockstar! :tada::+1:

Thank you for considering contributions to this repository!

#### Table Of Contents

* [Code of Conduct](#code-of-conduct)

* [What should I know before I get started?](#what-should-i-know-before-i-get-started)

* [How Can I Contribute?](#how-can-i-contribute)

* [Styleguides](#styleguides)


## Code of Conduct

This project and everyone participating in it is governed by the [Code of Conduct](docs/CODE_OF_CONDUCT.md). By participating, 
you are expected to uphold this code. Please report unacceptable behavior at [this website](https://mikelynchgames.com/report-concern/).

## What should I know before I get started?

Begin with the [README.md](README.md) file in the root of the project. This has everything you need to get started, either directly in 
the file, or in the linked files found there that often link to ther doc files. Begin with the `Getting Started` section of the doc to 
find out how to get the code running locally.

## How Can I Contribute?

### Reporting Bugs

If you find a bug, you can simply create an issue in github for the repo. Before creating bug reports, please search the existing 
issues, just in case the issue is known or was already reported. 

#### What makes a Great Bug Report?

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining what you were attempting to do before you found the bug.
* **Provide specific reproducable steps to demonstrate the issue**. Include links to files or copy/pasteable snippets, which you use in those examples.
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. 
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Include details about your configuration and environment:

* **What's the name and version of the OS you're using**?
* **Are you running in a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?


### Suggesting Enhancements

Thank you for your awesome ideas! We appreciate it. Before creating an enhancement suggestion, please do search to see if it has already been requested.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined your enhancement suggestion, 
create an issue and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion, include the word, 'Enhancement'.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Explain why this enhancement would be useful** to most users.
* **Specify the name and version of the OS you're using.**

### Your First Code Contribution

Once you have read the docs, you may find you want to contribute code, the best ay to do that is to fork the repo, make a branch on your
fork and then create a pull request from that branch. If you are generally new to open souce contribtions, you may find this link helpful, 
[How to contribute to Open Source](https://github.com/FreeCodeCamp/how-to-contribute-to-open-source). Generally this is a small project that 
you are thinking about contributing too, and since it's small, its a great place to start! We love contributions, and would like to help you
to make them, so don't be afraid to try!

All contributions (pull requests) will be reviewed by a member of the project, and feedback will be sent via gitHub. If the contribution 
is accepted it will be merged and then merged to develop and main.  

### Pull Requests

The process described here has several goals:

- Maintain code quality
- Fix problems that are important to users
- Engage the community in working toward the best possible project
- Enable a sustainable system for maintainers to review contributions

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings

### JavaScript Styleguide

All JavaScript code is linted with [Prettier](https://prettier.io/).

* Prefer the object spread operator (`{...anotherObj}`) to `Object.assign()`
* Inline `export`s with expressions whenever possible
  ```js
  // Use this:
  export default class ClassName {

  }

  // Instead of:
  class ClassName {

  }
  export default ClassName
  ```
* Place requires in the following order:
    * Built in Node Modules (such as `path`)
    * Local Modules (using relative paths)
* Place class properties in the following order:
    * Class methods and properties (methods starting with `static`)
    * Instance methods and properties

### Specs Styleguide

- Include thoughtfully-worded, well-structured [Jest](https://jestjs.io/) specs.
- Treat `describe` as a noun or situation.
- Treat `it` as a statement about state or how an operation changes state.


### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown).
* Reference methods and classes in markdown with the custom `{}` notation:
    * Reference classes with `{ClassName}`
    * Reference instance methods with `{ClassName::methodName}`
    * Reference class methods with `{ClassName.methodName}`


Above all, thank you for your help!



