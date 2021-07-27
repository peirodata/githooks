# githooks

Scripts run by git at critical moments.

- Complements the pre-commit hooks done with [pre-commit](https://pre-commit.com/)
- Update secrets after each `git pull` and `git checkout`

## Installation

Copy the scripts into the hooks directory of each desired project:

```bash
cp ./post-* /path/to/project/.git/hooks/
```

## Pre-commit

```bash
# Recommended: Install pipx

python -m pip install pipx

# Install black

pipx install black

# Install isort

pipx install isort

# Install flake8

pipx install flake8
mkdir -p ~/.config

# Copy flake8 configuration
cp ./flake8 ~/.config

# Installing pre-commit
# use pip if pipx is not available

pipx install pre-commit
```

## Links

<https://calmcode.io/pre-commit/the-problem.html>

<https://pre-commit.com/>

<https://pre-commit.com/hooks.html>

<https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/>

<https://stackoverflow.com/a/37293198>

<https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks>

<https://stackoverflow.com/a/18191639>
