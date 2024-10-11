
# COMP3104 DevOps Group Assignment

## Group Members
- **Kevin** (Student ID: 101418717) - [GitHub](https://github.com/KBTREY35)
- **Berlean** (Student ID: 101465969) - [GitHub](https://github.com/berleangregori)

## Project Description
This project is part of the COMP3104 DevOps course, focusing on practicing collaborative Git workflows, branching strategies, and setting up a Continuous Integration (CI) pipeline using GitHub Actions. The goal is to understand how to automate builds and tests as part of the DevOps lifecycle.

## Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourGitHubUsername/COMP3104_Group2_Assignment.git
   ```
2. **Switch to your branch**:
   ```
   git checkout 101418717-Kevin
   ```
3. **Install any dependencies** (if applicable).

## CI/CD Pipeline
The project uses GitHub Actions for Continuous Integration (CI). The workflow is triggered on every push to any branch and automatically checks for successful builds.

The workflow file can be found at `.github/workflows/ci.yml`.

## Branching Strategy
- Each member has their own branch named using the format `StudentID-Name`.
- All changes are merged into the `main` branch through pull requests.
- Conflicts are resolved before merging to ensure a clean history.
