# Datathons
## Overview
This is a web-based application designed to efficiently track participant and team data for a recurring data hackathon event. The system allows organizers to manage and monitor teams, participants, their progress, and other key metrics throughout the duration of the hackathon. The web service provides a clean and intuitive interface to handle various aspects of the event, including registration, team formation, task tracking, and performance evaluation.

## Tech stack
- React
- Tailwind
- Django
- PostgreSQL
- Docker

## How to Contribute

We welcome contributions to the Datathons web app! If you're interested in improving the project, please follow these guidelines:

### Forking the Repository

1. **Fork the repository**: Click on the "Fork" button on the top right of the repository page to create your own copy of the project.
2. **Clone your fork**: Once you've forked the repository, clone it to your local machine by running the following command:
   ```bash
   git clone https://github.com/your-username/Datathons.git
   ```
   if you use **HTTPS** or:
   ```bash
   git clone git@github.com:your-username/Datathons.git
   ```
   if you use **SSH**.

### Branching Strategy

Our project uses a strict branching strategy to maintain a stable codebase.

- **Main Branch (`main`)**: This is the stable version of the project. It contains production-ready code, and only merged pull requests from the `development` branch are allowed.
  
- **Development Branch (`development`)**: This is where ongoing development happens. New features, bug fixes, and enhancements should be implemented in feature branches, which are merged into `development` after review.

- **Feature Branches**: When working on a new feature or bug fix, create a new branch from `development`. Branch names should be descriptive of the work being done (e.g., `feature/add-user-authentication` or `bugfix/fix-leaderboard-update`).

### Contributing Process

1. **Create a feature branch**: Create a new branch for your feature or bug fix based off of the `development` branch.
   ```bash
   git checkout development
   git pull origin development
   git checkout -b your-feature-branch
   ```

2. **Make your changes**: Implement the feature or fix and write tests to cover your changes.

3. **Commit your changes**: Make sure to write clear and descriptive commit messages.
   ```bash
   git add .
   git commit -m "Add feature to track team progress"
   ```

4. **Push your changes**: Push your feature branch to your forked repository.
   ```bash
   git push origin your-feature-branch
   ```

5. **Create a Pull Request (PR)**: Once you're ready to submit your changes, open a pull request (PR) to the `development` branch of the main repository. In the PR description, provide a summary of the changes and any additional context for reviewers.

6. **Review Process**: PRs will be reviewed by the project maintainers. If your PR passes code review and tests, it will be merged into the `development` branch.

7. **Keep your branch up-to-date**: If your branch has been open for a while, make sure to pull the latest changes from `development` to resolve any merge conflicts.
   ```bash
   git checkout development
   git pull origin development
   git checkout your-feature-branch
   git merge development
   ```

8. **Merging**: Only project maintainers will merge pull requests into the `development` or `main` branches. Ensure your code is thoroughly tested and passes all checks before submitting a PR.

### Setting up the Project Locally

To get started working on the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Datathons.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Datathons
   ```

---

Thank you for contributing to the Datathons!