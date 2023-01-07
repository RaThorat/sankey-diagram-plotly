# Sankey-diagram-plotly
An Alluvial diagram has been used to relate categories, subcategories of grant applications

The provided code is for generating a Sankey diagram using the Plotly library in Python. The code first imports various libraries and modules that are needed for the analysis, including xlsxwriter, scipy, numpy, os, tkinter, plotly, chart_studio, and pandas.

The code then uses the tkinter library to create a graphical user interface (GUI) that allows the user to import an Excel file containing data for the Sankey diagram. The user can do this by clicking on a "Import Excel File" button that is displayed in the GUI.

Once the Excel file has been imported, the code defines a function called genSankey that takes in the following arguments:

  df: a Pandas dataframe containing the data for the Sankey diagram
  
  cat_cols: a list of column names in df that contain the categories for the Sankey diagram
  
  value_cols: a column name in df that contains the values for the Sankey diagram
  
  title: a string that specifies the title for the Sankey diagram
  
The genSankey function then processes the data in df to create the Sankey diagram and returns the figure object that can be plotted using Plotly. The code also calls the plotly.offline.plot function to plot the Sankey diagram and display it in the GUI.
