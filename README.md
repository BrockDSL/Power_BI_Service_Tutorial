![DSL Logo][dsllogo]


# Power BI Service
Power BI Service is the online version of Microsofts Power BI.  This version of the software is not as versatile as Power BI Desktop but it still provides powerful data visualization and analysis too and can be used to build both reports and dashboards.  Access to both the desktop version and online version of Power BI is available to Brock University students as part of their Office 365 subscription.  This tutorial will walk you through the following steps:
1. Importing Data
2. Creating a report with your data
3. Making visualizations with your data
4. Using Filters to focus on certain aspects of the data
5. Asking question of your data using the built in AI
6. Making a dashboard out of your visualizations
7. Using the Quick Insights tool
8. Editing your Dashboard with tiles
9. Saving your dashboard


### Setup
The first step for this tutorial is getting on to Power BI Service.  Navigate to [app.powerbi.com](https://app.powerbi.com/home) and login using your brock id to login.  Once you have logged in click on the "new look" slider at the top of the screen.  You are welcome to use the old look if you prefer but be aware that your screen may not look like the screenshots in this tutorial and the location of some menus are different.   Next, click on [This Link](Sample_Data.xlsx) and download the file to your computer.

### Getting Data
Click on the "Get Data" button at the bottom right of the scree.  Under the "Create new content" heading select "Get" under files.  Choose "Local File" and choose the sample dataset.  Click the "Import" button and your data will now be available in Power BI.

### Reports

Reports in Power BI are where you will spend most of your time building visualizations and looking at the data.  Navigate to your workspace by clicking "My Workspace" on the left menu.  Click on the "Datasets" tab and find your sample data.  To create a new report from your dataset, click on the bar graph icon under the actions header as seen below.

![Create Report Button][scrn1]

You should now be in the Report View with your data loaded.  On the right hand side you will see three menus: "Filters", "Visualizations", and "Fields".

Fields is the area where you determine wich columns of data will be included in your visualizations.  The Visualizations menu is where you add new visualizations to your report, change what type of visualization is being used in the selected tile, and edit the attributes of the selected visualization.  Filters are used to narrow down the focus in the selected tile so that you can look at data from select rows instead of entire columns.

![Adjustment Menu's][scrn2]

To create a visualization, select the type that you want to make from the visualizations menu, select the data that you want to be used in the visualization, and adjust the size of the newly created tile by dragging the corners of the box.  In the example below we created a pie chart containing the sales per country and resized it to be visible.  Another way to create a visualization is to select the data first and let Power BI decide what form is best suited to the type of data that you have selected.  To make another visualization, click on an empty space in your report so that nothing is selected, and the go through the steps again.  The contents of a visualization can be changed by selecting it (click on the white space in the tile) and then changing your selections in the Fields menu.

![First Visualization][scrn3]

To focus your visualizations on a more specific subject within the data selected from the Fields menu, we use the drop down lists in the Filters menu.  By using filters you can compare specific sections of your data more easily.

![Filtered Data][scrn4]

Another way to create visualizations in Power BI is to ask the built in AI to construct them based on keywords in questions.  To do this, select the "Ask a question" button from the top menu bar and type what you want the new visualization to show.  The AI can understand a reasonable level of correctly spelled terminology though best practice is to begin with the type of visualization you would like to see and then follow with the contents.  If you do not specify a type it will choose one for you.

![Question Visualization][scrn5]

Once you have created all of the visualizations that you need, adjust their apearance by selecting each tile, clicking on the paint roller icon in the Visualizations menu, and adjusting settings as needed.  Ensure that all labels are easily readable and that the colors used makes sense with your data.

![Adjust Settings][scrn6]

After adjusting your visualizations to your liking, save your report by clicking the save icon at the top right of the screen (above the Fields menu) and naming your report.  Once your report is saved you can start using the visualizations it contains in Dashboards.  To add a visualization to a dashboard click on the push-pin icon at the top right of that tile and either select an existing dashboard to add to or create a new dashboard.


![New Dashboard][scrn7]


Once you have added the tiles that you want from your report you can either go immediately to the dashboard or you can check for other useful tiles using the Quick Insights tool.  To access this tool click on the "My Workspace" option in the lefthand menu, go to the "Reports" tab, and click the "Quick Insights" button on your report (small lightbulb icon).
 
 ![Quick Insights][scrn8]
 

Quick Insights are an excellent tool for getting a brief overview of your data and potentially answering questions that you might have before you even ask them.  You can add a tile from your Quick Insights to your dashboard the same way you did in reports, the pushpin button at the top right of the tile.

Once you have added all of the tiles that you want to use for your dashboard, navigate to it by clicking "My Workspaces" and selecting the dashboard you created.  The primary purpose of a dashboard is to give a clean view of your data in an easy to navigate way.  Dashboards also give access to the "Ask Questions" tool.  This tool is a combination of the Quick Insights AI and the AI we used previously to build visualizations.  This allows you to ask questions of your data as well but it also suggests questions that you might ask.  Access it by clicking the "Ask a question about your data" button at the top left of the dashboard.

To enhance the experience of your dashboard add text and media tiles by clicking the "..." button on the top menu and selecting "Add tile" and then filling out the form for the tile you want.

Once the dashboard is set up how you like, you can print it or save it as a PDF by using the "Export" button on the top menu or share it if you have a Power BI Pro license by clicking the "Share" button.









<!--- Please use reference style images so that it is easier to update pictures later --->

[dsllogo]: dsl_logo.png
[scrn1]: pbi_img1.png
[scrn2]: pbi_img2.png
[scrn3]: pbi_img3.png
[scrn4]: pbi_img4.png
[scrn5]: pbi_img5.png
[scrn6]: pbi_img6.png
[scrn7]: pbi_img7.png
[scrn8]: pbi_img8.png
[scrn9]: pbi_img9.png
[scrn10]: pbi_img10.png
[scrn11]: pbi_img11.png
[scrn12]: pbi_img12.png
