## Analysis - Chicago_Speed_Enforcement_Program

Children’s Safety Zone Program, initiated by Chicago Department of Transportation (CDOT) is a key initiative to ensure safety for children and pedestrians around schools and parks. It forces vehicles to slow down and obey speed laws around safety zones designated as a 1/8th of a mile boundary around any Chicago parks or schools.

With the help of automated safety cameras, speeding vehiles  are identified who are breaking the law by exceeding the speed limits and issued a speeding ticket as per the following rules specified under the program:
- The enforcement hours will be limited from 7 a.m. to 7 p.m. in safety zones around schools on school days (Monday-Friday).
- The enforcement hours around parks will be limited to only those hours parks are open (typically 6 a.m. to 11 p.m., 7 days a week) with a 30 mph speed limit.
- The City is capping the locations where speed cameras can be installed to 20% of the 1,500 safety zone locations allowed by state law (approximately 300).
- Camera locations are chosen based on available data regarding traffic, speeding, and crashes.

The first cameras were installed in the year 2013 and since then it has been effective in reducing the number of violations significantly around the schools and parks. However, in order to make it even better, it is important to lookback on the program performance and take any corrective timely measures, if needed. 

Therefore, to do so, we studied the speed violations data captured for these cameras and observed that there has been a significant drop in the number of violations between 2014-2019. However, to uncover deeper insights for each safey zone category and camera locations, we looked at the data from different perspectives.

## Story
We initiated a story to provide a seamless flow to the observations and underlying message. We divided the stody into three 'Story Points', each describing a unique aspect of the data.

### Story Point-1: No. Of Violations Over The Years
In order to study the variation in number of violations over the years, we filtered the data as per safety zone categories - 'Parks' & 'Schools'. Then, we studied the variation for each camera location and also for each category over the years separately. We did that in the following way:

**Camera-Zonewise-Distribution:**
Data Source: (https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)
Chart Type: Heat Map, which divided the camera locations between two categories - 'Parks' & 'Schools'.
Title: A brief title (font size of '11' and 'bold') for the graph was added to introduce the purpose of the graph to the reader. 
Marks:
- Color: Distinct count of cameras for each category, where Orange - 'Parks' & Blue - 'Schools'.
- Size: Distinct count of cameras for each category, with both boxes of equal size since distribution of cameras in each category was almost equal.
- Label: Zone category was added as a label in order to signify each category. Also, distinct count of cameras for each box was used as a label to indicate the number of cameras each category. These labels were customized to a font size of '11', bold and 'Top Center' aligned for a better presentation.
Filter: A filter was added which will be used in the following graphs for connection and insight generation.
Caption: It indicates an almost equal allocation of speed cameras  under each category and the data sources.
[](Image)

**Camera-Zonewise-Violations:**
Data Source:( https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data ), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)
Rows: Added the lattitude of each camera location.
Columns: Added the longitude of each camera location.
Title: A brief title(font size of '11' and 'bold') for the graph was added to introduce the purpose of the graph to a reader. 
Marks:
- Color: Safety zone category has been used to differentiate between parks(orange) and schools(blue) on the map.
- Size: It varies as per the sum of violations at each camera location.
- Label: Sum of violations and address for each camera location has been displayed as labels for easy understanding.
Filter: We checked 'Use as a Filter' option and 'Apply to worksheets' on 'Camera-Zonewise-Distribution' worksheet to link it with 'Camera-Zonewise-Violations', in order to study variation in violations for each safety zone category, across different camera locations on the map.
Caption: It indicates the difference between no. of violations recorded for each camera location. Also, it highlights a fact that the number of violations recorded are higher around parks compared to schools. It also provides links for the data sources.
[](Image)

**Violations-Parks-vs-Schools**
Data Source: ( https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data ), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)
Rows: Added sum of violations for all cameras together.
Columns: Added the year of violations.
Title: A brief title(font size of '11' and 'bold') for the graph was added to introduce the purpose of the graph to a reader.
Marks:
- Color: Category was added as color to divide the total observations into two categories, where Orange - 'Parks' & Blue - 'Schools'.
Filter: We checked 'Use as a Filter' option and 'Apply to worksheets' on 'Camera-Zonewise-Distribution' worksheet to link it with 'Violations-Parks-vs-Schools', in order to study variation in violations for each safety zone category, over the years between 2014-2019.
Caption: It indicates the change in the no. of violations over the years fo reach of the safety zone categories - 'Parks' & 'Schools' and links to the data sources.

We combined all these three worksheets in one dashboard - 'Snapshot-Program', and used the floating layout to fit each of these worksheets in a clean layout. Any of these worksheets can be resized by dragging the edges along right, left or at the right corner. Finally, we dragged this dashboard into the first story point for our story. We also did the following:
Caption: Added a caption to introduce the underlying message of this dashboard.
Observation: After studying this dashboard, we observed that with 81 cameras around 'Parks' and 82 cameras around 'Schools', speed enforcement program has been significantly effective in reducing the no. of speed violations between 2014-2019. We added this observation to our story by 'Drag to add text' feature on the left menu bar. After adding the text, we formatted it by changing it's background color and border color to make it look nicer.











