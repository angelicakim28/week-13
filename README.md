# Week 13<br>Dashboarding with Panel and the PyViz Ecosystem

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/week-13/master?filepath=lecture-13.ipynb)

## Final Project

The final project is due by **5pm on Monday, May 13th**.

The final deliverable **must include all three of the below items**:

1. a web-based data visualization with a URL (public or private)
1. a document describing the project, the results, and the technical methods used in each step (collection, analysis and visualization)
1. all code/spreadsheets/datasets used

The materials for steps #2 an #3 above should be submitted to your own specific GitHub repository, which can be created using the link below:

https://classroom.github.com/g/b0HnnsVF

### Important

- The code for your web-based visualization (#1) can be either in the same repository or in a separate **public** repository. If it is in its own repository, be sure to link to it from the main, submission repository.
- Be sure to include the names of everyone who worked on the final project somewhere in the README, etc!

## Office Hours Poll

https://doodle.com/poll/uey3w7at5zvp4tmx

## Dashboard Examples

We'll walk through two examples of [Panel](https://panel.pyviz.org) dashboards that can serve as a reference for the final project.

1. [Visualizing recent shootings in Philadelphia using Altair, Folium, and Holoviews](https://github.com/MUSA-620-Spring-2019/philadelphia-shootings-app)
1. [Visualizing NYC taxi trips with Datashader and Altair](https://github.com/MUSA-620-Spring-2019/datashader-nyc-taxi-app)

## References

- Panel
  - [Documentation](https://panel.pyviz.org)
  - [User Guide](https://panel.pyviz.org/user_guide/index.html)
  - [Reference Gallery](https://panel.pyviz.org/reference/index.html)
    - Includes examples of different types of Panels, e.g., HTML, Markdown, Vega, etc
  - [Example dashboards from the PyViz team](https://github.com/pyviz-demos)
  - [Linking Altair charts to widgets](https://panel.pyviz.org/gallery/links/vega_heatmap_link.html#gallery-vega-heatmap-link)
- [Tutorial on a "dashboard workflow" with PyViz](http://pyviz.org/tutorial/A2_Dashboard_Workflow.html)
- [Datashader dashboard tutorial](http://datashader.org/dashboard.html)
  - Including a detailed walk-through of a Datashader-based dashboard
- [Holoviews Reference Gallery](http://holoviews.org/reference/index.html)
  - [Streams](http://holoviews.org/reference/index.html#streams)
  - [DynamicMap](http://holoviews.org/reference/containers/bokeh/DynamicMap.html#bokeh-gallery-dynamicmap)
- [Introduction to Python classes](http://www.jesshamrick.com/2011/05/18/an-introduction-to-classes-and-inheritance-in-python/)
- [Deploying Flask apps on PythonAnywhere](https://help.pythonanywhere.com/pages/Flask/)

## Updating your local environment

There is one new package that we'll need this week so we'll need
to update your Python environment.

### Option 1

From the Anaconda Prompt or Terminal, run

```
conda activate musa-620
conda install -c pyviz panel
```

### Option 2

The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.
