# Web-Based Visualization Options for the Final Project

## GitHub Pages

- Template repository: [MUSA-620-Spring-2019/data-viz-template](https://github.com/MUSA-620-Spring-2019/data-viz-template)
- Supported tools: Embedded Observable cells, Folium, Altair, Holoviews, HTML files via IFrames
- Examples:
  - [Folium maps](https://musa-620-spring-2019.github.io/data-viz-template/folium-charts/)
  - [Altair, Holoviews, Observable](https://musa-620-spring-2019.github.io/data-viz-template/measles-charts/)
  - [Leaflet maps + widgets via Observable](https://musa-620-spring-2019.github.io/data-viz-template/shootings/)
- Pros:
  - Automatic deployment/hosting via GitHub
  - Easy text formatting/input via Markdown
  - Supports a variety of visualizations
- Cons:
  - Static rendering with no server support
  - Embedded visualizations cannot interact with each other

## Flask and Dash

- Examples:
  - [Flask + Altair](https://github.com/MUSA-620-Spring-2019/week-12/tree/master/flask-altair)
  - [Dash + Altair](https://github.com/MUSA-620-Spring-2019/week-12/tree/master/dash-altair)
  - [Dash + Altair](https://github.com/MUSA-620-Spring-2019/week-13/tree/master/dash-folium)
- See: [Deployment Options](./DeploymentOptions.md) for PythonAnywhere instructions
- Pros:
  - Server support
  - Access to easy and beautiful widgets from Python
- Cons:
  - Visualizations rendered via IFrames and cannot interact with each other
  - Still requires HTML/CSS knowledge

## Panel

- Examples:
  - [Visualizing recent shootings in Philadelphia using Altair, Folium, and Holoviews](https://github.com/MUSA-620-Spring-2019/philadelphia-shootings-app)
  - [Visualizing NYC taxi trips with Datashader and Altair](https://github.com/MUSA-620-Spring-2019/datashader-nyc-taxi-app)
  - See: [Deployment Options](./DeploymentOptions.md) for Binder instructions
- Pros:
  - Support for all main visualization libraries
  - Only option that allows for using same code in Jupyter notebook and deployment
  - Allows for interaction between dashboard components
- Cons:
  - Still relatively new and working through some issues
  - Deployment on Binder is not perfect
    - Constrained by Binder resources
  - Deployment to other options still challenging
