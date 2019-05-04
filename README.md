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
We initiated a story - **'Have we done enough?'**, to provide a seamless flow to the observations and underlying message. We divided the story into three 'Story Points', each describing a unique aspect of the data.
- Title: We added a title to the story - 'Is There Anything Else That We Can Do Make This Program Even Better?' to integrate all the story points together.

### Story Point-1: No. Of Violations Over The Years
In order to study the variation in number of violations over the years, we filtered the data as per safety zone categories - 'Parks' & 'Schools'. Then, we studied the variation for each camera location and also for each category over the years separately. We did that in the following way:
![image](https://github.com/agrasonal/Data_Analysis-Chicago_Speed_Enforcement/blob/master/Images/Story_Point-1.png)

**Camera-Zonewise-Distribution**
<ul>
<li>Data Source: (https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)</li>
<li>Chart Type: Heat Map, which divided the camera locations between two categories - 'Parks' & 'Schools'. Since camera locations were almost equal, the size of the boxes were also almost equal and hence, was used for a better presentation on the story.</li>
<li>Title: A brief title (font size of '11' and 'bold') was added to introduce the purpose of the graph to the reader.</li> 
<li>Marks:</li>
    <ul>
      <li>Color: Distinct count of cameras for each category, where Orange - 'Parks' & Blue - 'Schools'.</li>
      <li>Size: Distinct count of cameras for each category, with both boxes of equal size since distribution of cameras in each category was almost equal.</li>
      <li>Label: Zone category was added as a label in order to signify each category. Also, distinct count of cameras for each box was used as a label to indicate the number of cameras in each category. These labels were customized to a font size of '11', 'bold' and 'Top Center' aligned for a better presentation.</li>
    </ul>
<li>Filter: A filter was added which will be used in the following graphs for connection and insight generation.</li>
<li>Caption: It indicates an almost equal allocation of speed cameras  under each category and the data sources.</li>
</ul>

**Camera-Zonewise-Violations**
<ul>
<li>Data Source:( https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data ), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)</li>
<li>Rows: Added the lattitude of each camera location.</li>
<li>Columns: Added the longitude of each camera location.</li>
<li>Title: A brief title(font size of '11' and 'bold') was added to introduce the purpose of the graph to a reader.</li>
<li>Marks:</li>
    <ul>
      <li>Color: Safety zone category has been used to differentiate between parks(orange) and schools(blue) on the map.</li>
      <li>Size: It varies as per the sum of violations at each camera location.</li>
      <li>Label: Sum of violations and address for each camera location has been displayed as labels for easy understanding.</li>
    </ul>
<li>Filter: We used 'Camera-Zonewise-Distribution' as a filter by clicking on 'Use as a Filter' and 'Apply to worksheets' and selecting 'Camera-Zonewise-Distribution' worksheet to link the two worksheets, in order to study variation in violations for each safety zone category, across different camera locations on the map.</li>
<li>Caption: It indicates the difference between no. of violations recorded for each camera location. Also, it highlights a fact that the number of violations recorded are higher around parks compared to schools. It also provides links for the data sources.</li>
</ul>

**Violations-Parks-vs-Schools**
<ul>
<li>Data Source: ( https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data ), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)</li>
<li>Rows: Added sum of violations for all cameras together.</li>
<li>Columns: Added the year of violations.</li>
<li>Title: A brief title(font size of '11' and 'bold') was added to introduce the purpose of the graph to a reader.</li>
<li>Marks:</li>
    <ul>
      <li>Color: Category was added as color to divide the total observations into two categories, where Orange - 'Parks' & Blue - 'Schools'.</li>
    </ul>
<li>Filter: We used 'Camera-Zonewise-Distribution' as a filter by clicking on 'Use as a Filter' and 'Apply to worksheets' and selecting 'Violations-Parks-vs-Schools' worksheet to link the two, in order to study variation in violations for each safety zone category, over the years.</li>
<li>Caption: It indicates the change in the no. of violations over the years for each of the safety zone categories - 'Parks' & 'Schools'.</li>
</ul>

We combined all these three worksheets in one dashboard - 'Snapshot-Program', and used the floating layout to fit each of these worksheets in a clean layout. Any of these worksheets can be resized by dragging the edges along right, left or at the right corner.

Finally, we dragged this dashboard into the first story point for our story. We also did the following:
- Story Caption: Added a caption to introduce the underlying message of this dashboard.
- Observation: After studying this dashboard, we observed that with 81 cameras around 'Parks' and 82 cameras around 'Schools', speed enforcement program has been significantly effective in reducing the no. of speed violations between 2014-2019. We added this observation to our story by 'Drag to add text' feature on the left menu bar. After adding the text, we formatted it by changing it's background color and border color to make it look nicer.

So, since we connected 'Camera-Zonewise-Distribution' worksheet with the other two worksheets, we can click on any one of the category to see filtered data trends for both graphs.

### Story Point-2: Avg. Monthly Violations-Parks vs Schools
In order to study the variation in average number of violations, we filtered the data as per safety zone categories - 'Parks' & 'Schools'. Then, we studied the average monthly variation for each category separately. We did that in the following way:
![image](https://github.com/agrasonal/Data_Analysis-Chicago_Speed_Enforcement/blob/master/Images/Story_Point-2.png)

**Avg-Monthly-Violations**
<ul>
<li>Data Source: (https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data), (https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)</li>
<li>Chart Type: Box Plot, which indicates the distribution of violations within different quartiles for each month over the years.It also highlights any outliers that might be present in the data.</li>
<li>Y-axis: represents the month when a violation was issued.</li>
<li>X-axis: represents the average number of violations issued.</li>
<li>Title: A brief title (font size of '11' and 'bold') was added to introduce the purpose of the graph to the reader.</li>
<li>Marks:</li>
    <ul>
      <li>Color: Blue, Grey & Black, which is suitable for color-blind friendly people.</li>
      <li>Detail: Dates were added for adding further detailing to the graph.</li>
      <li>Label: Dates were added as labels for better understanding of the key observations.</li>
    </ul>
<li>Filter: We used 'Camera-Zonewise-Distribution' as a filter by clicking on 'Use as a Filter' and 'Apply to worksheets' and selecting 'Avg-Monthly-Violations' worksheet to link the two, in order to study average variation in violations for each safety zone category, across different months of the year.</li>
<li>Caption: With the help of filter applied on Schools & Parks, this chart indicates the change in average number of violations across months. It indicates some peaks during holidays around parks when schools are not in session.</li>
</ul>

We added the worksheets-'Camera-Zonewise-Distribution' and 'Avg-Monthly-Violations' to a new dashboard - 'Violations-Around-Holidays', and used the floating layout to fit each of these worksheets in a clean layout. Any of these worksheets can be resized by dragging the edges along right, left or at the right corner. Finally, we dragged this dashboard into the second story point for our story. We also did the following:
- Story Caption: Added a caption to introduce the underlying message of this dashboard.
- Observation: After studying this dashboard, we observed that average no. of violations peak around the holidays(New Year, Independence Day & Christmas) in case of parks compared to schools. This might be due to speed camera enforcement during holidays when children are not around, defying the key underlying guideline of the program. We added this observation to our story by 'Drag to add text' feature on the left menu bar. After adding the text, we formatted it by changing it's background color and border color to make it look nicer.

So, since we the two worksheets are connected, we can click on any one of the category to see filtered data trends for each category.

### Story Point-3: Violation-Weekends-Parks vs Schools
In order to study the variation number of violations on each day of the week, we filtered the data as per safety zone categories - 'Parks' & 'Schools'. Then, we studied the variation for each category separately. We did that in the following way:
![image](https://github.com/agrasonal/Data_Analysis-Chicago_Speed_Enforcement/blob/master/Images/Story_Point-3.png)

**Weekday-Zone-Violations**
<ul>
<li>Data Source: (Ref-https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4/data)
(Ref-https://www.chicago.gov/content/dam/city/depts/cdot/Red%20Light%20Cameras/2018/Chicago_Active_Camera_Schedule_090518.pdf)</li>
<li>Chart Type: Discrete Line Chart, which indicates the variation in violations across the week.</li>
<li>Y-axis: represents the each day of the week when a violation was issued.</li>
<li>X-axis: represents the sum of violations issued on a particular weekday.</li>
<li>Title: A brief title (font size of '11' and 'bold') was added to introduce the purpose of the graph to the reader. </li>
<li>Marks:</li>
    <ul>
      <li>Color: Category column was used as a color differentiator, where Orange - 'Parks' & Blue - 'Schools'.</li>
    </ul>
<li>Caption: This chart indicates that no. of violations around parks increase over the weekend compared to rest of the week. Also, the number of violations around schools during the week are higher compared to the rest of the week.</li>
</ul>

We added the worksheet-'Weekday-Zone-Violations'to a new dashboard - 'Weekday-Variation'. This worksheet can be resized by dragging the edges along right, left or at the right corner. Finally, we dragged this dashboard into the third story point for our story. We also did the following:
- Story Caption: Added a caption to introduce the underlying message of this dashboard.
- Observation: After studying this dashboard, we observed that compared to schools, violations around parks increase over the weekend. This may be due to lack of awareness about the program, speed camera enforcement during these days, or confusing/ insufficient signage around parks. We added this observation to our story by 'Drag to add text' feature on the left menu bar. After adding the text, we formatted it by changing it's background color and border color to make it look nicer.

## Conclusion
The purpose of this story was to communicate the message that authorities need to revisit the program policies and installation locations in order to make sure that the the efforts are being directed in the right direction.

With the help of three story points, we broke down our key message and integrated it in the form of a story. This way it helps to communicate only one piece of information at a time, helping the reader to absorb and understand it in a better way.

Tableau Link for this project can be found here: 
