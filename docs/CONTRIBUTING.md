# Contributing

When contributing to PROJECT_NAME, please first discuss the change you wish via GitHub issue with the owners of this repository before
making a change. Please note we have a [code of conduct](), please follow it in all your interactions with the project.

## How To Contribute

### Bug Reports and Feature Requests

Have you found a bug, a mistake in the documentation, and want a new feature? You can help us by [submitting an issue on Github][issues].
Before you create an issue, make sure to search the issue archive, as your issue may have already been addressed.

### Submitting Pull Requests

1. Search the repository for open and closed [pull requests][pull_requests] that relate to your submission, as to avoid duplicate efforts.
2. Fork the project.
3. Create your feature branch: `git checkout -b <branch_name>`
4. Commit your changes: `git commit -m '<commit_message>'`
5. Push to the branch: `git push origin <branch_name>`
6. Open a [pull request][compare_changes].

> [!NOTE]
> PROJECT_NAME uses [conventional commits][conventional_commits], so please follow the specification in commit messages, branch names, and
> pull requests titles.

## Development Environment Setup

To step up a development environment, please follow the below steps:

1. Clone the repository:

    ```bat
    git clone https://github.com/kgreen1200/PROJECT_NAME
    ```

2. Install virtualenv:

    ```bat
    pip install virtualenv
    ```

3. Create and activate a virtual environment:

    ```bat
    virtualenv venv
    scripts\activate\venv
    ```

4. Install the required development dependencies:

    ```bat
    pip install -r requirements-dev.txt
    ```

<!-- URLs -->
[issues]: https://github.com/kgreen1200/PROJECT_NAME/issues
[pull_requests]: https://github.com/kgreen1200/PROJECT_NAME/pulls
[compare_changes]: https://github.com/kgreen1200/PROJECT_NAME/compare?expand=1
[conventional_commits]: https://www.conventionalcommits.org/en/v1.0.0/