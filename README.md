# Weather Data Analysis Dashboard

Create a Weather Dashboard using visualizations from a previous project. 

create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. Design a landing page and a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### The website consist of 7 pages total, including:

* A landing page containing:
  * An explanation of the project.
  * Links to each visualizations page.

* Four visualization pages, each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.

* A Comparisons page that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Bootstrap grid was used for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.

* A Data page that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data was a `.csv` file that was exorted as HTML using Pandas.

* The website is deployed using Github