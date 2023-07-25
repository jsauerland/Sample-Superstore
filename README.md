# Sample Superstore Data Project

One thing I really enjoy doing is visualizing data. In this project, I created a public dashboard for analyzing Sales Performance of the Superstore dataset from Tableau, but with a slight twist. I decided to do it in Power BI. Power BI and Tableau are very different yet both great environments for visualizing data, and I enjoy being able to utilize both regularly. 


##### Step 1: Acquiring and loading the data

The data for Tableau's Sample Superstore is hosted on [this website](https://datawonders.atlassian.net/wiki/spaces/TABLEAU/blog/2022/10/26/1953431553/Where+Can+I+Find+Superstore+Sales#Workbooks-and-Data-Sources). This website was provided by Tableau's community team, and is perfectly safe.

There's nothing crazy about this dataset, so it's easy to just open up Power BI, and load it in by importing it as Excel file

##### Step 2 (optional): Creating a mockup

Many data storytellers including myself like to plan out what their dashboard looks like before embarking on the arduous journey of creating it. This helps to clearly understand exactly how the dashboard should look, and what to include.

Figma, or PowerPoint is a great way to achieve this. Both allow you to create text, boxes, shapes, images, and then, drop them in place to create a 'mockup' of the design. 


##### Step 3: Creating the Dashboard

With the data loaded into Power BI, I set out creating the entire dashboard. 

I started out with a simple 'Monthly Orders' visual that would show orders per month, and would feature a neat average line. 

- **Viz 1**
-  Create a Clustered Column Chart, and drag Month of Order Date to X-Axis and Order ID to Y-Axis
-  Add an Average Line based on Order ID, color to White 50% darker, and line style to Dotted
-  Turn Average Line Data Label on, set to 0 decimal places
-  Set title to 'Monthly Orders'

![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/7356ec3d-2c2c-4af7-81c2-705a4f642483)

- **Viz 2**
-  Create a Stacked Column Chart, and drag segment to X-Axis, Sales to Y-Axis, Category to legend
-  Under 'Format your visual' go to Legend, and turn title off. Set alignment to center, font to Din 20, white 50% darker
-  Set title to 'Sales by Segment'

![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/beb1a3f7-1501-4e3a-8d4b-51df4dee9fc8)


- **Viz 3**
- Create an Area Chart, and drag Month to X-axis, Sales to Y-Axis
- Under 'Format your visual' go to Lines > Colors > change Sum of Sales to one of the 'Theme color _ 60% lighter' options depending on your design theme
- Add an Average Line based on Sales, color to White 50% darker, and line style to Dotted
- Turn Average Line Data Label on, set to 0 decimal places
- Set title to 'Monthly Sales'



![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/5d918b61-7cc5-4924-9021-0781cea13da1)


