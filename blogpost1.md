# Water Leaks in NYC Residential Buildings
#### Introduction
Every day, New York City residents call 311 to record complaints about infrastructure and services. Many of those complaints, or service requests, are more frequent in one area of the city than the other. I am interested in examining the distribution of complaints of water leaks in residential buildings in the city. I specifically want to know which months have the highest numbers of water leakage complaints and whether such complaints are clustered in a particular borough.  

Complaints of water leakage are routed to the Department of Housing Preservation and Development. If a pattern of these complaints exists—and can be demonstrated—the department can use the knowledge to direct resources to resolve the issue efficiently and effectively. 

#### 311 Service Requests for Water Leaks in NYC Residential Buildings in 2011
The graph below shows 311 service requests (complaints) for “water-leaks” in residential buildings in New York City in 2011, disaggregated by borough. The vertical axis simply shows the number of complaints made (or records created). The horizontal axis shows months in 2011 from March through December, months in which the records were created. The line for each borough is color-coded differently; the legend can be consulted on the left-hand side of the graph. Each line contains nodes that indicate the total number of complaints filed each month. The highest and the lowest numbers of complaints for each borough are noted on the graph. 

{% include plot1.html %}

#### How to use the interactive tool

Totals for each month can be viewed by hovering the mouse over the line for the desired borough. A user can type a complaint description in the search box under the Descriptor tab to view the frequency of other complaints. More than one complaint can be selected. The user may also view the number of other complaints for the same time period and areas by clicking on the Descriptor dropdown menu and selecting either to include or to exclude the selected value(s). Similarly, the user may click on the legend for any borough to highlight or exclude the results of said borough.

#### Design decisions and room for improvement

I wanted to create a visualization that captured the pattern of the number of records created and the month in which the records were created, and to look at those patterns separately for each borough. I also explored the option of using a bar chart to visualize the information. However, the bar chart did not clearly convey the month-to-month different in number of records created within and across boroughs. The line graph provides the benefit of borough-by-borough comparison, which was my primary interest. It also shows the pattern for a given borough. To add a numerical perspective, I also inserted the highest and lowest numbers of records for each borough. 

I would foremost like to add one line that aggregates the total for all boroughs. I would then like to expand this project by adding more descriptors under a given complaint type. I believe a complaint type that has descriptors with higher frequency would be more conducive to visualization and comparison.


<<Back to [homepage](https://spoudyal1989.github.io/datavizsample)
