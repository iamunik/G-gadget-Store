<h1 style="text-align: center; border-bottom: 1px dashed"> G-gadget Store Analysis</h1>
This project is a PowerBi project, A dataset <b>(Gadget.xlsx)</b> contains the data of a store that is based in Nigeria, the dataset contains the <b>order details, the Product name, Product subcategory, Product category, Promotion Name (for discounts), State, Cost of each Unit, Price of each unit and the Zone where each product was sold.</b> The task of this project is to make an analysis that bring out insights as it relates the geo political zones in the dataset.<br>Some extra values had to gotten to assist us with futher analysis: the derived value we got are explained below; <br>
<ul>
<li><b>Total cost</b>: The DAX expression written to derive the cost column is;<br>
<img src=pictures/total_cost.png><br>
The 'Unit Cost' and the 'Order Qty' column had to be multiplied to get the 'Total Cost' column as we did.
<li><b>Profit</b>: The DAX expression written to derive the profit column is;<br>
<img src=pictures/profit.png><br>
The 'Profit' column was derived by getting the difference between the product of the 'Unit Price' and 'Order Qty' and then the 'Unit Cost' and 'Order Qty' columns, getting the difference between the product of the above columns derived the 'Profit' column.
<li><b>Total Revenue</b>: The DAX expression written to derive this column is;<br>
<img src=pictures/total_revenue.png><br>
The 'Unit Price' and the 'Order Qty' columns needed to be multiplied to derive the 'Total Revenue' column.
</ul>
At the end of all the derivation we finally came up with the report below:<br>
<a href='https://www.novypro.com/project/g-gadget-store-analysis'>
<img src=pictures/report_1.png style="width: 70%; height:60%"></a><br>
<a href="https://www.novypro.com/project/g-gadget-store-analysis">Click to view dashboard</a>

<hr>

## SUMMARY OF THE REPORT
-	This data showed that of all 4 order channels the ‘Store’ channel received the most compared to other channels with a total of 142,000 orders and about $32.19 Million generated in revenue.
-	Even with the ‘Computers’ category generating the most in revenue ($21.63 Million) with a total of 69,000 orders, compared to other categories the ‘Cellphones’ category sold more with a total of 96,000 recorded orders but had a lower revenue ($5.92 Million) compared to the ‘Computers’ computers category.
-	Most customers purchased more goods during the times that promotions where not actively running bringing in a revenue of about $14.5 Million for that time frame.
-	The year 2012 was the best year for this business based on the data received, with a generated revenue of $21.32 Million and a profit of $12.28 Million, during that period they received a total of 81,000 orders most from the ‘Camera and Camcorders’ product category generating $7.6 Million in revenue that is about 13.53% of the total generated revenue for that year.
-	Of all the Geopolitical Zones the South East made the most profits with about $9.06 Million in profits about 27.9% of the total profit, while the FCT made the least profits of about $234,660 that’s less than 1% of the total profit made by Unik Stores.
<br>

## RECOMMENDATION FOR THE BUSINESS
-	Since the Cellphones product category has a lot of orders I would recommend to Unik stores to create a promotion targeted at Cellphones itself to boost revenue.
-	I would also suggest an increase of marketing activities either by Ads or other platforms to increase revenue from Zones that generate low revenue like the North East and the South West because those two generated less than 10% of the total revenue recorded.
-	Also promoting their online channel of placing orders, by adding a delivery discount to all orders made on specific dates or for first time customers.
-	Introduction of other channels of ordering to other Geopolitical zones will increase revenue also, the North West and North east uses only the walk in channel of placing orders, introduction of an online delivery channel would boost revenue in those zones.
- Since the South South brought in the most in terms of revenue, increasing marketing activities to target a larger audience will increase turnover rate.
<hr>
<b>Names of Project Files</b>:
<ul>
<li><b>Gadget.xlsx</b> (the dataset)
<li><b>pictures</b> (A folder containing the pictures used in this Readme)
<li><b>Report.pdf</b> (A pdf file containing a detailed explanation of the Dashboard per Geopolitical zone)
</ul>


## Technology used in this project
<ul>
<li> <b>PowerBi</b> (To build the report)
<li> <b>PowerQuery</b> (To create the derived columns)
</ul>
<hr>
<div style="text-align: center;">
<a href="https://oluwaseun-ogundeko.netlify.app/">Learn more about me!</a>
</div>
