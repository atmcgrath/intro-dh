## Hands-on Data Visualization

### National Park Visits, 1979-2023

![parks linegraph](../static/parks-line.svg)


## Agenda

- Show in WTF
- RawGraphs - line graph
- Let's come up with a list of ways to visualize this information

---

## Getting started

- Download the data here: [National parks annual data](https://raw.githubusercontent.com/melaniewalsh/responsible-datasets-in-context/main/datasets/national-parks/US-National-Parks_RecreationVisits_1979-2023.csv) 
- Save it to a folder on your computer that you'll be able to find later
- Upload the dataset to [WTF CSV](https://databasic.io/en/wtfcsv/) to see some basic info about it

---

## V1: RawGraphs line graph

- Navigate to [RawGraphs.io](https://www.rawgraphs.io/)
- Click 'Use it Now'
- Upload the parks dataset
- Make sure the data in each row is categorized correctly
- Scroll down to 'Choose a Chart' and select 'Line Chart'
- Drag 'Year' onto the X axis
- Drag 'RecreationVisits' onto the Y axis
- Look at the result. What do you notice?
- Now drag 'ParkName' onto 'Lines'
- Try dragging things onto 'Color' and 'Series' and try swapping out other categories for 'Lines'
- When you have something you are satisfied with, scroll down to 'export'. Choose either `.svg` or `.png`
- Save this in the same folder as your csv.

---

## V2: Choose your own

- In pairs, create 2-3 other graphs to show different things with the original dataset or a stacked dataset. 
- Hint: try at least one graph that shows hierarchies
- Try using [Park visits by month](https://raw.githubusercontent.com/melaniewalsh/responsible-datasets-in-context/main/datasets/national-parks/US-National-Parks_Use_1979-2023_By-Month.csv), which also includes data on camping and other categories.
- Feel free to refer to the [RawGraphs documentation](https://www.rawgraphs.io/learning) for more detail on particular charts
- Save 2 graphs and post them to the Moodle Forum for today

---

## V4: Draw your data

- Think of two or more creative ways to represent your dataset

---

## Discussion
- What was most interesting or exciting? 
- What context or additional data could you bring in to build out a data story?

---

##  Excel Pivot Table

Now we're going to do some simple data transformations using Microsoft Excel. The PivotTable feature is designed to summarize and 'stack' your data so that it is easier to visualize. Learn more about [Pivot Tables in Excel here](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576).

- Locate the dataset on your computer and click to open the secondary menu. Select 'open with' and chose 'Microsoft Excel'.
- Once your spreadsheet is open, click the top left cell to select the whole active sheet
- From the top menu, select 'Data' > 'Summarize data with PivotTable'
- A window will open up prompting you to select where to place the pivot table. Select 'New worksheet'
- Under PivotTable Fields, select 'ParkName' and 'RecreationalVisits'
- What do you see?