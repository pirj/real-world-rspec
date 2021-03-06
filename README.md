# Real-world RSpec

> Real-world open source codebases using RSpec for developers to learn from

Thank you to every developer who has worked on a project this repo links to,
your work is helping developers learn RSpec.

## Installation

```bash
# Clone this git repo:
git clone git@github.com:pirj/real-world-rspec.git

cd real-world-rspec

# This will take some time...
git submodule update --init --remote --checkout --single-branch --depth 1
```

### Updating

The repositories are linked as git submodules.

To check out the latest the revisions, run:

```bash
# This will take some time:
git submodule update --remote --checkout --single-branch --depth 1
```

## Other Real World codebase collections

 - Real World Ruby https://github.com/jeromedalbert/real-world-ruby-apps
 - Real World Rails https://github.com/eliotsykes/real-world-rails

## Contribute

Contributions are welcome! Reach out if you'd like some help.

### Is your repository the right fit?

- it is actively maintained
- it is covered with RSpec specs
- it is popular

Don't hesitate to submit a pull request if you meet the criteria!
Also don't hesitate to submit a pull request to remove a repository if it doesn't meet the criteria anymore.

### How to include a new repository

For a repo `fooser/baretory`:

```bash
git submodule add --depth 1 -- git@github.com:fooser/baretory.git
```

## Contributors

Phil Pirozhkov https://fili.pp.ru
