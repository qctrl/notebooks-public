# Q-CTRL Notebooks Public

This repository publicly exposes a curated set of Q-CTRL documentation notebooks. Its primary purpose is to make those notebooks available to the public through [Google Colab](https://colab.research.google.com/), rather than to serve as the primary source for notebook development.

The notebooks are copied from the [`qctrl/notebooks`](https://github.com/qctrl/notebooks) repository and published here for discoverability and execution. They contain [Jupyter](https://jupyter.org/) examples showing how to use Q-CTRL products to solve quantum control problems.

## Usage

Open the notebooks using your favorite [Jupyter](https://jupyter.org/) Notebook viewer/editor, or use the Google Colab links provided in the notebooks and their associated documentation.

## Automated Updates

Notebook changes are normally reviewed and merged in the source [`qctrl/notebooks`](https://github.com/qctrl/notebooks) repository. An automation account, Q-CTRL Robot, then copies the updated notebooks into this repository. The resulting commits are made by the robot, usually have an upstream pull request number in the commit message, and are marked `(notebooks update)`.

This means that a notebook update may appear here without a pull request in this repository. The repository grants the source repository write access through [`repository_access_permissions.json`](repository_access_permissions.json), so the automated update is an intentional publishing step rather than a manual contribution workflow. Changes to the publishing mechanism or to this repository's supporting files should still use the normal pull request process.

## Contributing

See [Contributing](https://code.q-ctrl.com/contributing).
