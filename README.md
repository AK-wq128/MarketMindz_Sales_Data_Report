# MarketMindz Sales Data Report

This project reports on sample sales data from the fictional company MarketMindz. The reports are created using PowerBI. The PowerBI file and dataset are attached. For viewer use, please see the below narrative, which contains screenshots and explanations of each report.

This project is based off of sales data, and through various data transformations in the Power Query editor, was broken up into a STAR data model. Due to the nature of the STAR model, all reports created from this dataset are dynamically linked, meaning they can be used to filter other visualizations. The data model for this project is shown below.

![data_model](https://github.com/user-attachments/assets/0e997ff2-77e0-4ac1-9afa-c61e3ef483e8)

From this data model, a set of five PowerBI reports were created.

### Report 1: Campaign and Product Performance

![campaign_and_product_performance](https://github.com/user-attachments/assets/7df4094d-a0ab-4d3b-b421-b6e08aedf93d)

This first report displays information regarding individual marketing campaign and product performance. Sales information is displayed for the campaigns and products, and platform preferance is also visualized in the bottom two visualizations.

### Report 2: Worldwide Customer Demographics

![worldwide customer demographics](https://github.com/user-attachments/assets/f0a71196-78a9-4a8e-9df5-7801731c29de)

The second report displays information regarding customer demographics. MarketMindz is modeled off of a global company with customers from around the world. As a result, this report displays averages of worldwide demographic information against marketing campaigns, income, education, age, product, and family size. Due to the extensive amount of demographic data, customer tooltips were developed for two of the visualizations, which are described next.

#### Tooltips: Kids and Teens Visualizations
The first custom tooltip was created for the "Kids at Home" visualization, which displays the percentage of customers with 0, 1, or 2 young kids. Hovering over a section of the pie chart will reveal the custom tooltip. This custom tooltip contains visualizations regarding the income of those customers with the number of kids that the user hovered over in the pie chart.

![kid_tooltip](https://github.com/user-attachments/assets/212396b8-5a2b-492a-ab88-b7474125672b)

The second tooltip was created for the "Teens at Home" visualization, and follows the same format and filtering logic as the "Kids at Home" custom tooltip.

![teen_tooltip](https://github.com/user-attachments/assets/2a91982b-1651-4044-b12b-a38e2c5eb8fd)

### Report 3: Purchase Influencers

The third report presents information through the use of AI. Each visualization is of the "Key influencers" type in PowerBI. The first visualization uses AI to analyze features that could explain why some customers were influenced by marketing campaigns and why other customers were not. The second visualization examines features that could explain sales trends in the dataset. Finally, both of these AI visualizations can be filtered by individual products using a slicer at the top of the report.

![purchase_influencers](https://github.com/user-attachments/assets/a39d906a-5975-4a46-b91e-23fc34ebb2fe)

### Report 4: Purchase Platform Popularity

The fourth report displays information regarding the popularity of each purchasing platform, which consist of catalog, store, the web, and marketing deals. Sales distributions are given for each platform, and platform use is displayed by country and age.

![purchase_platform_popularity](https://github.com/user-attachments/assets/0f73b525-d086-4a34-ad5e-622b5d591df2)

### Report 5: Country Operations

The fifth report visualizes general information about the countries that MarketMindz operates in. The success of different marketing campaigns is displayed by country, along with average income, number of complaints, and sales. Additionally, all visualizations can be further filtered by age using the "Age" slicer in the center of the report. Finally, a "Country of Operations" map is displayed with the total sales amount for each country. By right-clicking on any country, a user can drill-through this report, which is discussed in greatly detail next.

![country_operations](https://github.com/user-attachments/assets/ea4c75a5-b153-4377-822d-1288656c40d5)
Uses a slicer to filter all visualizations by age.

#### Drill-Through Report: Country Deep-Dive

The below image shows a user right-clicking on the country USA and drilling through to the "Country Deep-Dive" page.

![drill_through](https://github.com/user-attachments/assets/b253b61f-7a68-4baf-9412-17faaf76a8af)

The below image shows the "Country Deep-Dive" report that was drilled-through to. Because this report was drilled-through from the map visual in the "Country Operations" parent report, all visualizations will be filtered based on the country right-clicked on. In this case, it is the country USA. Because all visualizations only show data from one country, users can focus on deriving sales, products, and campaign performance information specific to that country instead of viewing it globally. Finally, a back arrow is posted at the top of the page, which allows users to return to the "Country Operations" parent report.

![country_deep_dive_usa](https://github.com/user-attachments/assets/dbdfdf2b-40ae-4f75-8703-ab264c431803)

##### Tooltip: Purchases and Sales for Platforms
A custom tooltip was created for the "Country Deep-Dive" drill-through report. As seen below, this tooltip is connected to the "Number of Purchases by Platform" visualization, and shows the distribution of purchases and sales by age for each individual platform that the user hovers over. In the below example, the tooltip for the "Web" platform is displayed.

![purchases_and_sales_tooltip](https://github.com/user-attachments/assets/33979b82-b24d-4851-81c7-073d41525d02)










