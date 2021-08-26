# HubMap
## Implementation: 

Given the dataset of 19 csv files, I took around 10 csv files merged and formed a single dataset named " final_sheet.csv". This final_sheet.csv contains around 5k recodrs with the fields as "OBO Ontological Id" ,"Markers" (splitted based on Comma) and the Index. Code for this is available in "Data Visualisation.ipynb".

Next goal was to create the X and Y coordinates for the Network Graph. For this, two sheets were created "Bridge_file.csv" and "Graph_coords.csv" and these are used for linking the nodes with the target to form a network graph later in the Tableau workbook.Code for this is available in "Hubmap.ipynb"
After obtaining X and Y coordinated and the NodeName (as given in sheet Graph_coords.csv) I created a network graph using Tableau Software. The Source node for the graph is "OBO Ontological Id" and Target Node is the "Markers"  and the links are the indexes assigned to each "OBO Ontological Id".

Please find the link below for the workbook:
https://prod-useast-b.online.tableau.com/t/tableaudatavisualisation/views/Hubmap/Sheet1?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link

Output folder contains the output Image, data  and PDF .


