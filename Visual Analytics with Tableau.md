# Visual Analytics with Tableau
This course consists of a series of visual analysis projects using Tableau, performed with various types of charts and graphs and different visualization techniques.

## Analysis on Customer Purchases
My company has tasked me with analyzing the customers' purchases and how much the company is profiting from each customer based on their [Sales data](https://github.com/yl5787/tableau-specialization/blob/main/data/Sales%20Superstore%20Dataset.xlsx). So I decided to create a scatter plot showing Customer Sales versus Customer Profit. The scatter plot is colorized by Profit Ratio with its circles sized by Discount. Tooltip with additional customer purchase information and a trend line have been added to show the correlation among the data more clearly. Filters on the right-hand side by Order Date, Segment, and Category drill down into different views and conditions quickly for an even detailed customer purchase analysis.

[Tableau visualization](https://public.tableau.com/app/profile/yl5787/viz/CustomerScatterplot_16364101257770/CustomerScatterplot)

![Customer Scatterplot](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Customer%20Scatterplot.png)

## Analysis on Shipping Details
My company has tasked me with analyzing their orders’ shipping status and how many shipments are completed per week in the 4th quarter of 2014 based on their [Shipping data](https://github.com/yl5787/tableau-specialization/blob/main/data/Shipping%20Superstore%20Dataset.xlsx). I decided to create an area chart showing the total number of shipments by Order Date with a new calculated feature called "Ship Status" showing whether the shipment was “Shipped on Time,” “Shipped Early,” or “Shipped Late.” As area charts show proportions in part-to-part and part-to-whole relatoinships, the areas show a total number of orders by Ship Status as well as their relative size to other Ship Status' areas. The area chart is colorized by Ship Status and filters by Ship More and Ship Status are added on the right-hand side. The tooltip shows additional information on Ship Status, Order Date, and the total number of shipments.

[Tableau visualization](https://public.tableau.com/app/profile/yl5787/viz/ShippingDetails_16364298111620/ShippingDetails)

![Shipping Details](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Shipping%20Details.png)

## Analysis on Total Sales
Spotlighting is a technique for showing discrete thresholds based on the values of a measure. Based on their [Sales data](https://github.com/yl5787/tableau-specialization/blob/main/data/Sales%20Superstore%20Dataset.xlsx), I am tasked with creating a sales spotlight table showing total Sales by Product category, broken down by Year and Month. So I created a new calculation titled “Sales Spotlight” that categorizes the Total Sales into “Good” if Total Sales are over $10,000, and “Bad” if Total Sales are lower than $10,000. The table is colorized by the new Sales Spotlight field and a Region filter and Tooltip with Profit information have been added. 

[Tableau visualization](https://public.tableau.com/app/profile/yl5787/viz/SalesSpotlight_16366910870870/SalesSpotlight)

![Sales Spotlight](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Sales%20Spotlight.png)

## Analysis on Geographic Data
My company has tasked me with creating a dual layer map based on their [Sales data](https://github.com/yl5787/tableau-specialization/blob/main/data/Sales%20Superstore%20Dataset.xlsx). So I created two maps - a field map shading on a region basis to indicate relationships and a symbol map/bubble chart with field circles to represent sales points - and combined them into one. The field map is used as a filter to drill into different regions and the bubble chart is used to represent the concentration of sales and their varied amounts. By layering bubble map on top of the field map, it is easy to interpret the geographical impact on sales performance quickly. Bubbles also inform about relative concentration of sales. The dual layer map shows Total Profit by Postal Code, colorized by Profit Ratio, and sized by Total Sales. The tooltip displays additional information about the location and sales profit, and filter controls on the right-hand side provide filters by Order Date, Region, and Profit Ratio.

[Tableau visualization](https://public.tableau.com/app/profile/yl5787/viz/SalesMap_16370342427440/SalesMap)

![Sales Map](https://github.com/yl5787/tableau-specialization/blob/main/visualizations/Sales%20Map.png)
