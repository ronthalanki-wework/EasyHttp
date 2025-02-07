# How to Contribute

We're excited you're interested in contributing to Marquez! We'd love your help, and there are plenty of ways to contribute:

* Fix or [report](https://github.com/MarquezProject/marquez-java/issues/new) a bug
* Fix or improve documentation
* Pick up a ["good first issue"](https://github.com/MarquezProject/marquez-java/labels/good%20first%20issue), then send a pull request our way

We feel that a welcoming community is important and we ask that you follow the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md) in all interactions with the community.

# Submitting a [pull request](https://help.github.com/articles/about-pull-requests)

1. [Fork](https://github.com/MarquezProject/marquez-java/fork) and clone the repository
2. Make sure all tests pass locally: `./gradlew test`
3. Create a new branch: `git checkout -b my-cool-new-branch`
4. Make change on your cool new branch
5. Write a test for your change
6. Make sure `.java` files are formatted: `./gradlew spotlessJavaCheck`
7. Push change to your fork and [submit a pull request](https://github.com/MarquezProject/marquez-java/compare)
8. Add the ["review"](https://github.com/MarquezProject/marquez-java/labels/review) label to your pull request
9. Work with project maintainers to get your change reviewed and merged into the `master` branch
10. Delete your branch

To ensure your pull request is accepted, follow these guidelines:

* All changes should be accompanied by tests
* Do your best to have a [well-formed commit message](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html) for your change
* [Keep diffs small](https://graysonkoonce.com/stacked-pull-requests-keeping-github-diffs-small) and self-contained
* If your change fixes a bug, please [link the issue](https://help.github.com/articles/closing-issues-using-keywords) in your pull request description

# Resources

* [How to Contribute to Open Source](https://opensource.guide/how-to-contribute)
* [Using the Fork-and-Branch Git Workflow](https://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow)
* [Keep a Changelog](https://keepachangelog.com)
