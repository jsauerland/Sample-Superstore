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
-  Set Data labels > Display units to thousands. This helps it look better. 7648 vs 7k
-  Set title to 'Sales by Segment'

![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/beb1a3f7-1501-4e3a-8d4b-51df4dee9fc8)


- **Viz 3**
- Create an Area Chart, and drag Month to X-axis, Sales to Y-Axis
- Under 'Format your visual' go to Lines > Colors > change Sum of Sales to one of the 'Theme color _ 60% lighter' options
- Set Data labels > Display units to thousands
- Add an Average Line based on Sales, color to White 50% darker, and line style to Dotted
- Turn Average Line Data Label on, set to 0 decimal places
- Set title to 'Monthly Sales'



![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/5d918b61-7cc5-4924-9021-0781cea13da1)

- **Viz 4**
- Create a Clustered Bar Chart, and add Product Name to Y-axis, Sales to X-Axis
- Under 'Filters', go to 'Product Name', select Top N = 10, drag sales to the 'Value' section
- Under 'Format your visual' go to Bars > Colors > change to one of the 'Theme color _ 60% lighter' options
- Set Data labels > Display units to thousands
- Set title to 'Top _ Products by sales' based on Top N value. Mine was 10
- Copy the entire visual, and paste it to the right of it to create next visual

  ![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/3ccc4ccb-088f-42f9-98e0-145d53a71427)


- **Viz 5**
- Simply replace Sales on the X-axis with Profit
- Replace the field in Top N filter with Profit instead of sales
- Adjust the title to 'Top 10 Products by Profit'
- Copy the entire visual, and paste it to the right of it to create next visual

![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/284384d9-9081-48a6-877f-536eb59f9282)

- **Viz 6**
- Replace Product Name on Y-axis with City
- Go to Filters > Top N and clear it out
- Set a new filter for Top N > 10 City by Profit
- Adjust the title to 'Top 10 Cities by Profit'

![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/df45b16e-ff3d-4899-9516-0d3ef1bd06d2)

##### Step 4: Formatting the Dashboard

- Adjust all the vizzes so they're the same size. Easy way to do this is to simply go to Format Visual > Properties > Size. Set them all exact same Height and Width
- CTRL+click the top 3 visuals and go to Format > Align > Distribute Horizontally. Do the same with the bottom 3. 
- Insert shape, choose a line. Drag to the middle of the dashboard and use it to separate top 3 from bottom 3
- Click the line and go to Format > Shape > Style > Border. Set it to White 60% darker, transparency 80%. Adjust to your liking. More transparency makes it grayer and more faded
- Insert another line (or copy the first), and change Rotation to 90 degrees so it's vertical, and use it to separate into columns. Two lines will be needed for this
- Fine tune and adjust the positioning

  
##### Final Result

![image](https://github.com/jsauerland/Sample-Superstore/assets/32148757/ff12ddf7-3c1f-4843-b457-48ba64c97264)

------


