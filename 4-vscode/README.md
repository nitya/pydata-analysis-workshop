# 04 | Visual Studio Code

## What You Learn
- Why use Visual Studio Code?
- What is a VS Code Profile?
- How do I create a Data Science Profile?
- What is Data Wrangler?
- How can I use Data Wrangler for Data Analysis?

###  1 | Why use Visual Studio Code?

1. It's the preferred IDE for use with GitHub Codespaces
2. It integrates seamlessly with Jupyter Notebooks
3. It supports rich extensions like Data Wrangler
4. It supports reusable configuration with VS Code Profiles


###  2 | What is a VS Code Profile?

 1. A [profile](https://code.visualstudio.com/docs/editor/profiles) capturing your custom settings, extensions and preferences.
 1. Can be easily shared (for consistency) and switched (to suit context)
 1. Can be created from base templates - including the [Data Science Profile Template](https://code.visualstudio.com/docs/editor/profiles#_data-science-profile-template)

 ### 3 | How do I create a Profile?

 1. Follow [these instructions](https://code.visualstudio.com/docs/editor/profiles#_create-a-profile) to create one from scratch, or by template customization
 1. [Export](https://code.visualstudio.com/docs/editor/profiles#_export) the profile to share it with others
 1. [Import](https://code.visualstudio.com/docs/editor/profiles#_import) a shared profile and switch to it, to use it

Note: The repository has [my exported profile](./../Python%20Data%20Analysis.code-profile) stored as a file in the root folder. Simply click the gear icon in the VS Code sidebar (left), go to `Profiles > Import Profile` and load this file into your editor, then switch to it (make it default) _to get my exact editor experience_.


 ### 4 | What is Data Wrangler?

 1. A code-cenrtic data-viewing and cleaning tool available [as an extension](https://code.visualstudio.com/docs/datascience/data-wrangler)
 1, Launch it from a data file, or from a dataframe within a Jupyter Notebook
 1. It provides a _sandbox_ for data cleaning & transformation (original data is not modified)
 1. It provides _rich operations_ you can apply interactively, to transform data (e.g., sort, filter, remove)
 1. It _auto-generates code_ for those operations, that you can now take back to your notebook

 This allows data wrangler usage to create _reproducible steps_ that others can follow, to get the same outcome.

 ### 5 | How can I use Data Wrangler?

Explore the notebook below to see Data Wrangler in action, in the context of a Pandas data frame.

| Notebook | Description |
| --- | --- |
| [VS Code Data Science Tutorial](./1-data-science-tutorial.ipynb)| Walkthrough Setup and Data Preparation for [VS Code Tutorial](https://code.visualstudio.com/docs/datascience/data-science-tutorial#_train-and-evaluate-a-model) - and [explore Data Wrangler](https://code.visualstudio.com/docs/datascience/data-wrangler#_data-wrangler-operations)  |
| | |

### #14DaysOfDataScience

This section contributed to the post on [Day 2 of #14DaysOfDataScience](https://30daysof.github.io/data-science-day/week-2/2-vscode/)) learning. Visit that site to view all posts from Data Science Fundamentals to Developer Tools.

![Read The Post](https://30daysof.github.io/data-science-day/_astro/DatatScienceDay-DevTools-2.IDWIV_F__1oytri.webp)
