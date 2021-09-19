# Contributing to USO Questions

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to questions for the USO ("Utilizarea sistemelor de operare") course.
These are mostly guidelines, not rules.
Use your best judgment, and feel free to propose changes to this document in a pull request.

## Pull Requests

The process described here has several goals:

* Collect interesting and good quality questions.
* Forward relevant questions to USO quizzes.
* Make it easy for maintainers to review contributions.

Please add the following information in the description of your PR:
* Number of questions added
* Topics used in questions

Working on your first Pull Request?
You can learn how from the free series [How to Contribute to an Open Source Project on GitHub](https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github).

## Contributing Steps

Preparatory phases:

1. Create a fork of this repository.
1. Clone your fork locally or update your local clone with the upstream repository updates.

Adding new questions:

1. Think of a nice and interesting question (or more) you want to add as a contribution.
1. Create a new branch for the new question(s).
1. Locate the file(s) where the question(s) will be added, based on question(s) topic.
1. Use the [human-readable format](#question-format) to develop a new question in the appropriate file.
   You can start from the [`template.hr`](template.hr) file.
   See sample questions in [`sample.hr`](sample.hr).
1. Commit changes to your branch.
1. Push changes to your fork.
1. Create a pull request (PR).
1. Answer to requests from the reviewer on the PR.
1. Once the reviewer approves the PR, your contribution will be integrated.

## Question Format

We use a custom format (named *human-readable format*, or *hr*) to easily create new questions.
The format is documented in the [Quiz Manager repository](https://github.com/systems-cs-pub-ro/quiz-manager/blob/master/README.md#question-format).

Topics for USO questions are listed in the [`topics.txt`](topics.txt) file:

* `admin`: administration-related questions, usually related to services and system configuration
* `app_dev`: application development, build automation, build phases, development tools
* `basic`: basic / common sense questions on operating systems and Linux
* `boot`: bootstrapping, bootloaders, the boot process
* `cli`: using the shell, shell operators, one liners
* `data`: data storage and processing
* `embedded`: embedded systems
* `file_system`: file operations, filesystem hierarchy
* `general`: question covering multiple topics
* `hardware`: hardware, drivers, physical computing resources
* `netiquette`: Internet etiquette guideliness
* `networking`: network configuration, network parameters, Internet, Internet services
* `process`: working with processes, process inspection, process hierarchy
* `regex`: regular expressions
* `security`: data protection, data integrity, encryption, password management
* `shell_scripting`: shell scripting, automation
* `user`: users, groups, user management, access control, filesystem permissions
* `vm`: virtual machines, containers

Choose one topic per question.
For questions with tuples (i.e. `Which of the following matches the (security, filesytem, networking) tuple`), use the `general` topic.

For difficulty use a numeric value between `1` and `3`, as shown in the [`difficulty.txt`](difficulty.txt) file.

USO questions may fall under one of the categories:

* questions with 4 answers in total, 1 correct answer
* questions with 5 answers in total, 2 correct answers
* questions with 7 answers in total, 3 correct answers

## Style Guides

### Git Commit Guidelines

* Use the present tense ("Add feature" not "Added feature").
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
* Prefix each question commit message with the topic name.
* Limit the first line to 72 characters or less.
* Reference issues and pull requests liberally after the first line.

[Sign-off](https://docs.pi-hole.net/guides/github/how-to-signoff/) your commits.

Take a look in [these guidelines](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53) for your Git commit messages.

## Attribution

This CONTRIBUTING.md is adapted from [Atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md), [ember.js](https://github.com/emberjs/ember.js/blob/master/CONTRIBUTING.md), [Node.js](https://github.com/nodejs/node/blob/master/CONTRIBUTING.md), [Nayafia's Template](https://github.com/nayafia/contributing-template/blob/HEAD/CONTRIBUTING-template.md).
