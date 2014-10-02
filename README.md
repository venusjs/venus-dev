Setup Your Venus Dev Environment
================================

The Venus.js core is quite small, with the majority of functionality implemented within plugins. Each plugin is developed in its own git repository.

To effectively work on Venus, you will need to clone multiple repositories. This script is designed to help you get started.

To bootstrap your environment, follow these steps:

1. Make sure you have the `git-run` npm module installed: `npm install -g git-run`.
2. Update the `repos` file to include each repo you will be working with. You'll want to replace `sethmcl` and `venusjs` to point at your github username (so that the script clones your fork of each repo).
3. Run `./setup.sh`. This will clone each repo specified in the `repos` file, install dependencies, and setup symlinks to local repos.
