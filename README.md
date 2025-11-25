# Team-1-MIST4610-Project-2

## Team Members
1. Colten Lin cwl27381@uga.edu
2. Audrey Djunaidi ad04585@uga.edu
3. Claire Woehrman ctw49810@uga.edu
4. Max Trinh mlt22305@uga.edu
5. Nayan Magdum nm37036@uga.edu


## Dataset Description

Meteorite Landings

https://catalog.data.gov/dataset/meteorite-landings

Rows: 45,716

Columns: 10

Source: NASA

Column Names:

  Name: name of the meteorite
  
  Id: identification code of the meteorite
  
  Nametype: lists whether the meteorite is valid
  
  Recclass: class of the meteorite
  
  Mass (G): mass of the meteorite in grams 
  
  Fall: whether the meteorite has fallen or been found
  
  Year: what year the meteorite fell
  
  Reclat: the latitude where the meteorite was found
  
  Reclong: the longitude where the meteorite was found
  
  Geo Location: the exact geolocation where the meteorite was found

  Questions:

How has the number and mass of recorded meteorite landings changed over time?

Why it’s important:
Understanding how meteorite landings and their masses have changed over time helps reveal both scientific and observational trends. It can show whether meteorite activity has fluctuated across different decades or whether improvements in detection technology and record-keeping have influenced the number of documented landings. This question provides valuable historical context about how human observation and meteorite patterns intersect, helping researchers understand whether we’re truly seeing changes in meteorite activity or simply changes in how we record them.

<img width="1192" height="686" alt="image" src="https://github.com/user-attachments/assets/1443ee1d-e081-476a-ae8f-907e459bc24b" />
<img width="595" height="333" alt="image" src="https://github.com/user-attachments/assets/8c3477b1-15ac-4100-b4ea-78024ed77e9a" />

Can we predict which regions are most likely to experience future meteorite landings?

Why it’s important:
Predicting regions that are more likely to experience future meteorite landings can help identify geographical patterns and environmental factors associated with meteorite impacts. By analyzing past landing coordinates (latitude and longitude), researchers can determine if certain regions are statistically more prone to meteorite occurrences. This has implications for scientific monitoring, public awareness, and risk preparedness. From an analytical perspective, this question also highlights how spatial data can be used to make meaningful geospatial predictions using visualization and trend analysis in Tableau.

In theory, we could manipulate the data to produce a new calculated field using the built in geo-locations to estimate predictive analysis data on continents and regions based on frequency at which meteorites are recorded (listed as implication). Another example based on the classes of recorded meteorites were made by manipulating the data below, creating a new calculated field and interpreted data set as well:

<img width="530" height="290" alt="image" src="https://github.com/user-attachments/assets/29a75a9b-9a7f-4304-a011-2eb750cbe7cf" />
<img width="222" height="355" alt="image" src="https://github.com/user-attachments/assets/6042c6c8-b56f-42ed-9775-5d61a5a3256d" />

Based on the major 3 classifcations of Iron for recorded meteorite data, we organized them into the 3 to show frequency at which each type/composition are most comonly recorded. This data can be significant for developing the understanding of between fallen/found data, how types are depicted given a certain moment in time, and whether the location in which they are recorded have affect based on the atmospheric composition.

## Implications of Analysis: 

The following implications on the Analysis of our data predict certain measures to the collected dataset that could be hindered by external factors, and have potential assumptions based on future viability of the data being visualized. 

1. Because data is based on Regions, analysis could potentially vary due to developing nations and accessibility of investment into data collection for fallen/found meteorites.
2. Predicted data on Age of found Meteorites that were recorded, change in technology and instruments used to track meteorites over time
3. Nature of disintegrating meteorites falling can show variances in data for mass of recorded fallen meteorites versus tracked ones. 
4. Given the the geo-locations provided by dataset, Tableau could use geocoding and produce a calculated field to identify continents/regions based on coordinates. 


