# Web Visualization Dashboard

## Summary

Data is more powerful when we share it with others! I create a dashboard showing the latitude analysis i have done in a different project. Tools are used here are mainly HTML, CSS and Bootstrap. 

![Images/landingResize.png](visualizations/landingResize.png)

In building this dashboard, i create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.


The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data come from exporting the `.csv` file as HTML. 

The website has a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website is deployed to GitHub pages.


### Screenshots

Screenshots of each page at varying screen widths:

#### <a id="landing-page"></a>Landing page

Large screen:

![Landing page large screen](visualizations/landingResize.png)

Small screen:

![Landing page small screen](visualizations/landing-sm.png)
￼

#### <a id="comparisons-page"></a>Comparisons page

Large screen:

![comparison page large screen](visualizations/comparison-lg.png)

Small screen:

![comparison page small screen](visualizations/comparison-sm.png)

#### <a id="data-page"></a>Data page

Large screen:

![data page large screen](visualizations/data-lg.png)


Small screen:

![data page small screen](visualizations/data-sm.png)

#### <a id="visualization-pages"></a>Visualization pages

I build four of these, one for each visualization. Here's an example of one:

Large screen:

![visualize page large screen](visualizations/visualize-lg.png)

Small screen:

![visualize page small screen](visualizations/visualize-sm.png)

#### <a id="navigation-menu"></a>Navigation menu

Large screen:
![nav menu large screen](visualizations/nav-lg.png)

Small screen:
![nav menu small screen](visualizations/nav-sm.png)

