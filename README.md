# CA2

# Analysis of Wheat Yields worldwide with a focus on Irish Winter Wheat Yields 

This is the code to my Continuous Assignment 2 in Semester 1 of the MSc in Data Analytics at CCT, September 2022 stream.

It includes some Jupyter notebooks at different points of progress. 
- the first Jupyter notebook was uploaded in December with progress in the initial data gathering stage. Most of this data was sourced from the FAO website with some data preparations and visualisations to take an initial look at the data;
- due to a laptop issue (with a recently acquired laptop becoming faulty and failing twice) I spent more time focusing on resolving the technical issues with the laptop than working on the assignment and hence no commits over that period. I was then focused on getting the assignment back on track which took longer than expected. Hence the gap between the first and second commit;
- the final upload/commit will be done prior to issue of the assignment due on 13th January 2023; and
- it will also include a Jupyter notebook which is used specifically for the Interactive Wheat Dashboard.

### Wheat Dashboard - Interactive visualization dashboard in Python with Panel

This contains the code used to run the Wheat Dashboard.  Once the notebook has run, the next step is to open the Anaconda prompt and type 'panel serve Wheat_Dashboard.ipynb'.  This will start to run, the first line will provide a date and statement saying 'Starting Bokeh server version...'. The URL at the end of the third line needs to be copied into a webbrowser for the interactive dashboard to work.  In my case the relevant line has text start with Bokeh app running at http://local.5006/Wheat_Dashboard, so I would copy http://local.5006/Wheat_Dashboard into a browser and hit return for it to run.

A slider is available to the left to move the year along and as the years increase, the data on the panels to the right will change.


