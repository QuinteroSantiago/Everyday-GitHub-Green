# Everyday-GitHub-Green

## Purpose
This repository is designed to maintain a consistent daily commit record on GitHub, automatically creating a green activity box on my profile every day.

## How It Works
The workflow (`daily-commit.yml`) in this repository automatically runs every day, incrementing a counter in `counter.txt` and committing the updated count. This ensures a daily update to the repository, reflected as activity on my GitHub profile.

## Repository Structure
- `.github/workflows/daily-commit.yml`: The GitHub Actions workflow that runs daily.
- `counter.txt`: A simple text file that keeps track of the number of commits.
- `file.txt`: A log file that records each daily commit.

## Personalizing the Workflow
If you wish to use this workflow for your GitHub profile:
1. Fork or clone this repository.
2. Modify the `daily-commit.yml` file to include your GitHub username and email.
3. Enjoy your daily green GitHub box!

The primary purpose of this repository is to demonstrate GitHub Actions and automated commits. Also a good way to have more green boxes :)
