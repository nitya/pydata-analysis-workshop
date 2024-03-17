# Python Data Analysis

## 1 | Introduction

This repository provides the source code and documentation for a **Python Data Analysis** workshop based on some version of these talks:

| Talk | Description | Slides |
| ---- | ----------- | ------ |
| [Simplifying Data Analysis with GitHub Codespaces, Jupyter Notebooks & Open AI](https://www.youtube.com/watch?v=wVMwKy1QmTM) | PyData NYC (Nov 2023) | [Slides](https://speakerdeck.com/nitya/simplifying-data-analysis-with-github-codespaces-jupyter-notebooks-and-open-ai) |
| [Simplifying Data Analysis  (with Developer Tools & AI (for non-Python devs)](https://www.youtube.com/watch?v=scvDXfCMHYU) | Data Science Day (Mar 2024) | [Slides](https://speakerdeck.com/nitya/simplifying-data-analysis-and-visualization-with-developer-tools-and-ai) |
| ||

## 2 | Workshop Roadmap

The slide shows a high-level roadmap for what we want to cover in this workshop. The goal is to help someone who is familiar with development - but not with data science or Python - skill up quickly on topics related to data science, analysis and visualization using developer tools and AI assistance.

![2024 Roadmap](https://30daysof.github.io/data-science-day/_astro/DataScienceDay-Roadmap.ixBAXxDK_1SuePL.webp)

The actual roadmap for the workshop may switch steps up in sections, or combine exercises for efficiency to align with the Week 2 schedule on [#14DaysOfDataScience](https://30daysof.github.io/data-science-day/week-2/). Click the "Day" entry to read the post, and the "Details" entry to visit the exercise, once series is complete.

| Day | Description | Details |
| ---- | ----------- | ------- |
| [1️⃣](https://30daysof.github.io/data-science-day/week-2/1-codespaces/) | Setup a Consistent Development Environment with Dev Containers (GitHub Codespaces) + Jupyter Notebooks. Run sample notebooks. | [Setup Dev Environment](./2-jupyter/README.md) |
| [2️⃣](https://30daysof.github.io/data-science-day/week-2/23️⃣-vscode/) | Create a Data Science driven Visual Studio Code Profile for productivity. Do the VS Code Data Science Tutorial, use Data Wrangler. | [Setup Custom VS Code Profile](./4-vscode/README.md)|
| [3️⃣](https://30daysof.github.io/data-science-day/week-2/3-github-copilot/) | Install the Copilot extension and use it to create Notebooks, explain code, or debug issues inline (or in chat mode). | Install & explore GitHub Copilot |
| [4️⃣](https://30daysof.github.io/data-science-day/week-2/4-open-datasets/) | Learn about open datasets on Kaggle, Hugging Face, Azure, Open ML etc. Explore sites to learn from community & experiment.| Pick a dataset, do EDA, build Model|
| [5️⃣](https://30daysof.github.io/data-science-day/week-2/5-responsible-ai/) | Learn about Responsible AI principles & explore the components of the Responsible AI Toolbox for assessing these in practice. | Debug Models & Decision-Making |
| [6️⃣](https://30daysof.github.io/data-science-day/week-2/6-project-lida/) | Learn about Project LIDA and how you can use Large Language Models to summarize and visualize data, using natural language prompts | Visualize Data using LLM & NLP|
| [7️⃣](https://30daysof.github.io/data-science-day/week-2/7-azure-ai/) | Learn about the paradigm shift from MLOps to LLM Ops and how to use the Azure AI SDK (Python) to build, evaluate, & deploy, AI apps. | Explore LLM Ops with Azure AI|
| | |

## 3 | Pre-Requisites
  - Familiarity with GitHub and Visual Studio Code
  - Familiarity with at least one high-level programming language
  - Access to an OpenAI or Azure OpenAI key - optional, for Project LIDA
  - Access to a GitHub Copilot enabled account - optional, for AI-assisted learning
  - Knowledge of Python and Jupyter Notebooks is a plus
  - Having a specific data set or data analysis problem to work on is a plus

## 4 | Learning Objectives

By the end of this workshop, you will be able to:

 - **Describe** what the various tools do, and why they matter
 - **Setup** a reusable development environment - with GitHub Codespaces
 - **Document** your learning with code - with Jupyter Notebooks
 - **Generate** notebooks and explore unfamiliar code - with GitHub Copilot
 - **Discover**, analyze and visualize open datasets - from Kaggle, Hugging Face or Azure
 - **Train & debug** models for responsible AI practices - with Responsible AI Toolbox
 - **Build intuition** and explore data visualizations - with Project LIDA
 - **Explore paradigm shift** to LLM Ops - with Azure AI Studio

## 5 | Developer Tools

Here are the main tools we will cover, with links to relevant documentation and a short description on why they are useful.

| Tool | Description |
| ---- | ----------- |
| [Jupyer Notebooks](https://jupyter.org/) | Interactive development environment for sharing code with documentation, for collaborative learning & debugging |
| [GitHub Codespaces](https://docs.github.com/codespaces) | Reusable and reproducible development environments based on development containers for configuration-as-code. |
| [Visual Studio Code](https://code.visualstudio.com/docs/datascience/overview) |  Visual Studio Code extensions for Data Science, with [Data Science Profile Template](https://code.visualstudio.com/docs/editor/profiles#_data-science-profile-template)|
| [GitHub Copilot](https://github.com/features/copilot) | AI-based assistance for developers - from code explainers to code creation and debugging|
| Open Datasets | Jumpstart exploration with curated public datasets for machine learning - from [Kaggle](https://www.kaggle.com/datasets), [Hugging Face](https://huggingface.co/datasets), and [Azure](https://learn.microsoft.com/azure/open-datasets/dataset-catalog)|
| [Responsible AI](https://responsibleaitoolbox.ai/) | Responsible AI Toolbox includes tools for identifying, diagnosing, and mitigating, issues in data. |
| [Project LIDA](https://microsoft.github.io/lida/) | Automated generation of visualizations with LLM, with user customization and suggestion options |
| [Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/) | Unified platform for building generative AI applications from model exploration to API deployment |
| | |

## 6 | Python Libraries

Developer tools will streamline your learning journey, but you will need to skill up on a few core Python libraries, to be productive. Start with these libraries, in the recommended order. For each, start by creating a new notebook in your fork of this repo - then try to walk through the quickstart tutorial step-by-step, to get a sense of what the library does and how it works.

> **Important** | To start using these libraries, you will first need to install them in your development environment. Look for installation instructions that use `pip` - and add those libraries to the [requirements.txt](requirements.txt) file if absent. Rebuild container - and you should be ready to go.

| Library | Description | Quickstart |
| ------- | ----------- | ---------- |
| [NumPy](https://numpy.org/) | Numerical computing with Python | [Quickstart Tutorial](https://numpy.org/doc/stable/user/quickstart.html) |
| [Pandas](https://pandas.pydata.org/) | Data manipulation and analysis | [Getting Started](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html#getting-started) |
| [Matplotlib](https://matplotlib.org/) | Data visualization (static + interactive) | [Quickstart](https://matplotlib.org/stable/users/explain/quick_start.html) - [Depth](https://matplotlib.org/stable/tutorials/index.html) |
| [Seaborn](https://seaborn.pydata.org/) | Data visualization (matplotlib-based) | [Quickstart](https://seaborn.pydata.org/installing.html#quickstart) - [Depth](https://seaborn.pydata.org/tutorial.html) |
| [Scikit-learn](https://scikit-learn.org/stable/) | Machine learning in Python (Core) | [Quickstart](https://scikit-learn.org/stable/getting_started.html) - [Depth](https://scikit-learn.org/stable/user_guide.html) |
| [TensorFlow](https://www.tensorflow.org/) | Machine learning in Python (E2E) | [Quickstart](https://www.tensorflow.org/tutorials/quickstart/beginner)  - [Depth](https://www.tensorflow.org/tutorials)|
| [PyTorch](https://pytorch.org/) | Machine learning in Python (CV, NLP) | [Quickstart](https://pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html) - [Msft](https://learn.microsoft.com/training/paths/pytorch-fundamentals/) |
| [Bokeh](https://bokeh.org/)  |  Interactive visualizations in Python | [Quickstart](https://docs.bokeh.org/en/latest/docs/first_steps.html) - [Depth](https://docs.bokeh.org/en/latest/docs/user_guide.html)|
| | |

This is not a comprehensive list - feel free to add more to the list as you skill up, based on the goals you are driving towards in usage.


## 7 | Learning Resources

These are resources I recommend for skilling up on these topics. Note that _open access_ editions of published books are often made available by the authors, on their sites, for supporting learners - and not for commercial use. Please read and honor the author's usage requirements when exploring content or code.

| Resource | Description |
| -------- | ----------- |
| [2024: Data Science Day Collection](https://bit.ly/2024-datasci-collection) | My curated collection of Microsoft Resources for Data Science development |
| [2024: Responsible AI for Developers](https://aka.ms/rai-hub/collection) |My curated collection of Microsoft Resources for Responsible AI usage|
| [2024: Generative AI Code-First on Azure](https://aka.ms/ai-studio/collection) |My curated collection of Microsoft Resources for Generative AI with the Azure AI Platform |
| [Python Data Science Handbook - Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/) | O'Reilly book made available online with MIT license and [tutorial notebooks](https://github.com/jakevdp/PythonDataScienceHandbook) on GitHub|
| [Python for Data Analysis 3E - Wes Mckinney](https://wesmckinney.com/book/) | O'Reilly book made available online with MIT-licensed [code examples](https://github.com/wesm/pydata-book/tree/3rd-edition) on GitHub |
| [Introduction to Machine Learning with Python -  Andreas C. Müller & Sarah Guido](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/) | O'Reilly book covering `scikit-learn` usage with notebooks on [GitHub](https://github.com/amueller/introduction_to_ml_with_python). Book content is not online.|
| | |

## 8 | Feedback Welcome

Have questions or comments, or found areas for improvement in the coede or documentation? [File an issue](https://github.com/nitya/pydata-analysis-workshop/issues/new) to let me know.