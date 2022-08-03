# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change.

Please note we have a code of conduct, please follow it in all your interactions with the project.

## General

* Be nice and respectful of maintainers and contributors time and viewpoints
* Be as descriptive as possible! More info is always better than not enough
* Be patient, there may be a lot of in-flight work, some of it across multiple projects not related to the repo being contributed to
* Have fun!

## Contributing

Contributing comes in many forms! I'm incredibly grateful to anyone who can do any of the following:

* Add new features
* Fix bugs
* Fix typos
* Improve docs
* Triage issues
* Review pull requests
* Share opinions and viewpoints on issues

## How do I make a contribution?
Never made an open source contribution before? Wondering how contributions work in the in our project? Here's a quick rundown!

1. Find an issue that you are interested in addressing or a feature that you would like to add.
2. Fork the repository associated with the issue to your local GitHub organization. This means that you will have a copy of the repository under your-GitHub-username/repository-name.
3. Clone the repository to your local machine using git clone https://github.com/github-username/repository-name.git.
4. Create a new branch for your fix using git checkout -b branch-name-here.
5. Make the appropriate changes for the issue you are trying to address or the feature that you want to add.
6. Use git add insert-paths-of-changed-files-here to add the file contents of the changed files to the "snapshot" git uses to manage the state of the project, also known as the index.
7. Use git commit -m "Insert a short message of the changes made here" to store the contents of the index with a descriptive message.
8. Push the changes to the remote repository using git push origin branch-name-here.
9. Submit a pull request to the upstream repository.
10. Title the pull request with a short description of the changes made and the issue or bug number associated with your change. For example, you can title an issue like so "Added more log outputting to resolve #4352".
11. In the description of the pull request, explain the changes that you made, any issues you think exist with the pull request you made, and any questions you have for the maintainer. It's OK if your pull request is not perfect (no pull request is), the reviewer will be able to help you fix any problems and improve it!
12. Wait for the pull request to be reviewed by a maintainer.
13. Make changes to the pull request if the reviewing maintainer recommends them.
14. Celebrate your success after your pull request is merged!

## Issues

* If your issue is security related, please follow the [SECURITY guide](https://github.com/komandar/.github/SECURITY.md)
* Before opening a new issue, check for existing issues that are related including closed ones
* Provide as much information as possible about the issue, how to reproduce the problem, and the expected behavior
* Don't needlessly bump issues

## Pull Requests

* Pull Requests should be accompanied first by an issue describing the reason a PR may be needed
* Don't make unrelated changes in your Pull Requests
* Pull Requests should be as small as possible
* Don't open a Pull Request if you don't plan to see it through, PRs submitted by individuals that cannot complete additional work to get a PR merged may get closed
* Adhere to the existing code style of the repo, even if it differs from your personal preference
* When applicable, add tests that provide ample coverage of the logic added or changed
* Pull Requests should come from branches and never the default `main` or `master` branch
* Pull Requests must pass CI including linting and testing
* Pull Requests must go through code review before they can be merged to the main branch
* Do not include "version bump" changes in the same PR as your code changes, these will be handled as a separate PR and releasing process
* Be as descriptive as possible in your PR description as to why these changes are being made and what the changes contain
* Make sure the `Allow edits from maintainers` checkbox is checked. That way I can make certain minor changes myself, allowing your pull request to be merged sooner.

## What does the Code of Conduct mean for me?
Our Code of Conduct means that you are responsible for treating everyone on the project with respect and courtesy regardless of their identity. If you are the victim of any inappropriate behavior or comments as described in our Code of Conduct, we are here for you and will do the best to ensure that the abuser is reprimanded appropriately, per our code.
