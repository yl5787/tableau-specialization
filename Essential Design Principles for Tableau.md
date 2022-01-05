# Essential Design Principles for Tableau

This course analyzes and applies essential design principles to Tableau visualizations including pre-attentive attributes, Gestalt principles, and decluttering visualization.

## Sales for Superstore

This visualization leverages pre-attentive attributes using size and color. The size of the circles represents discount and the colors represent profit ratio. Bigger circles indicate higher discounts have been offered and the color red indicates negative profit ratio. When analyzing sales performance, sales figures alone wouldn't tell as much as with sales ratio and discount data. If the salesperson offered a high discount and resulted in a negative profit ratio, they brought loss rather than profit to the company regardless of how high their total sales is. This visualization is designed to pop out those two relevant attributes other than sales figures using the pre-attentive attributes size and color. The users can clearly get this information without having to search around or learn the data themselves.

[Tableau dashboard](https://public.tableau.com/app/profile/yl5787/viz/SalesforSuperstore/Dashboard)

![Sales for Superstore](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Sales%20for%20Superstore.png)

## Anscombe's Quartet

The famous Anscombe's Quartet argues that just using statistical summary alone is not enough to understand the data, and that you have to visualize it. It comprises four different datasets with nearly identical average, variance, correlation, and linear regression slope, but once you visualize it, the four datasets produce very dissimilar graphs. This clearly proves that correlation is not causation. Here, visualization serves as an interesting way to understand statistics and shows the importance of exploratory work.

[Tableau visualization](https://public.tableau.com/app/profile/yl5787/viz/AnscombesQuartet_16281912403900/AnscombesQuartet)

![Anscombe's Quartet](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Anscombe's%20Quartet.png)

## Identifying Outliers in Superstore Orders

Tableau can also be used to identify outliers. The below dashboard consists of a strip plot and a histogram that visibly sort out outliers. Tooltip displays the exact values of the outliers when you hover over the records.

[Tableau dashboard](https://public.tableau.com/app/profile/yl5787/viz/IdentifyingOutliersinSuperstoreOrders/Dashboard)

![Identifying Outliers](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Identifying%20Outliers.png)

## Control Chart for Superstore Orders

A control chart is a great way to view the attribute's performance based on standard deviations. It's about finding errors and understanding the range of the data. As a result, it lets you see if things are going okay or if there's any problem. A control chart shows values that lie outside of standard deviations. The standard deviation slider lets users change standard deviation and see what's outside the standard deviation selected and what's inside.

[Tableau visualization](https://public.tableau.com/app/profile/yl5787/viz/ControlChartforSuperstoreSales_16281951129100/ControlChart)

![Control Chart](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Control%20Chart.png)

## Final Project: Superstore Sales Performance

The goal of this project is to create a visualization that will identify which three sub-categories are the worst performers by region, and show how much worse they perform than other sub-categories. Sylvia, a VP of Sales, will use this visualization to understand which product categories to cut, and in which regions. It is necessary to first review the [persona document for Sylvia](https://github.com/yl5787/tableau-specialization/blob/main/Sylvia%20Persona.pdf) to gain an understanding of her needs, goals, and abilities, then to create a visualization that shows the worst performing sub-categories in each region, and how those worst performers compare to other sub-categories in that region. It is also required to identify the three worst performing sub-categories overall. The visualization must demonstrate proper use of the design principles including "pop-out" or pre-attentive attributes, Gestalt Principles, cognitive load and clutter, and static or interactive format. [Answers](https://github.com/yl5787/tableau-specialization/blob/main/Superstore%20Sales%20Performance%20Project%20Answers.pdf) to the question prompts explain how my design choices fit the needs, goals, and abilities for the intended audience, Sylvia.

[Tableau dashboard](https://public.tableau.com/app/profile/yl5787/viz/SuperstoreSalesPerformance_16285589135620/Dashboard)

![Superstore Sales Performance](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Superstore%20Sales%20Performance.png)
