# Denver Crime Analysis

### Introduction
<p>
It is seen that in many cities when crime is rampant, a dataset is generated to help authorities by bringing out insights and take better decisions for allocating resources. Here we try to analyse the occurrence of crimes in Denver a city in Colorado. We use this dataset to understand the pattern of crimes to possibly enable better action against them.
</p>

---
### Methodology
<p>
I conducted exploratory data analysis and generated various visualizations. These were done using python libraries including Seaborn and Folium. They were very helpful to draw insights from the data and also reach certain conclusions. Further insights are explained in following sections.
</p>

---
### Data
<p>
This <a href="https://www.kaggle.com/paultimothymooney/denver-crime-data">dataset</a> includes criminal offenses in the City and County of Denver for the previous five years plus the current year to date. It is based on the National Incident Based Reporting System (NIBRS). It is dynamic, which allows for additions, deletions and/or modifications at any time, resulting in more accurate and updated information in the database. 
</p>

---
### Exploratory Data Analysis(EDA)
<p>
I conducted descriptive analysis about these features, by their statistical values or distribution plots. Then I further explored the correlation between the features.
</p>

<ul>
  <li>
    Here is a Heatmap to show the correlation between different features:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/Capture.PNG">
  </li>


  <li>
    The features with Null values are visualised here using bar plots:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/geo.PNG">
  </li>


  <li>
    Year with the highest number of crimes:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/j.PNG">
  </li>


  <li>
    Month with the highest number of crimes:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/jj.PNG">
  </li>
  
  
  <li>
    Day of the month with the highest number of crimes:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/p.PNG">
  </li>
  
  
  <li>
    Most dangerous hours of the day:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/k.PNG">
  </li>
  
  
  <li>
    The district with the highest number of crimes till date:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/l.PNG">
  </li>
  
  
  <li>
    Which Precinct is most dangerous?<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/precinct.PNG">
  </li>
  
 
  <li>
    The number of crime precincts in different districts:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/line.PNG">
  </li>
  
  
  <li>
    Which crime is most prevalent in wich hour?<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/diff.PNG">
  </li>


  <li>
    Which crime is most prevalent on which day of the month?<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/pl.PNG">
  </li>
  
  
  <li>  
    Which crime is most prevalent in which month?<br> 
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/kl.PNG">
  </li>


  <li>
    Which neighborhood is most dangerous?<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/po.PNG">
  </li>


  <li>
    Which is neighborhood is the safest?<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/plo.PNG">
  </li>
  
  
  <li>
    Which crime category has the highest frequency?<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/lkj.PNG">
  </li>

  
  <li>
    All-other-crimes has the highest frequency of crimes, so we do in-depth analysis of All-other-crimes:<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/plkj.PNG">
  </li>


  <li>
    To conclude the Analysis we plot a heatmap using folium over the regions in Denver where crimes related to drug and alcohol are the most.<br>
    <img src="https://github.com/yashasvimisra2798/Denver/blob/master/Plots/fol.PNG">
  </li>
 </ul>
 
---  
### Conclusion
<p>
The whole analysis shows which specific year, day, month, district, precinct and neighbourhood is most prone to crimes. This can be very helpful to authorities to act in a specific and a smart manner by targeting those particular dangerous districts, hours, days, months and precincts. The comparisons and in-depth analysis gives a much better insight to the patterns of these crimes which may help in following and catching the criminals to stop more henious crimes that might take place in the future. 
The seaborn library of python was used to give synthetic visualisations and folium library was used in the end to give regional visualization of the crimes related to drug and
alcohol.
</p>



