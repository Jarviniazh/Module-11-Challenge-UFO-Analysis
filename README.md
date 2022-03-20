# UFOs Analysis

## Project Overview

### Purpose
This project aims to assist Dana, a data journalist, create a webpage about UFOs. Dana would like to introduce her hometown McMinnville Oregon to everyone, especially the famous sightings of UFOs. Dana came with a JavaScript file filled to the brim with sighting information, would ask us to put her article, the table of data to support her findings, and easy to use filters to fine tune the results together. Moreover Dana wants us to add not only one date filter, but four more (countries, cities, states, and type of sighting) to make a more in-depth analysis of UFO sightings.

## How To Use This Webpage

 - **Simple single search cirteria**  
The users can use each filter as an individual search box. The dataset contains 13 dates of sighting, 2 countries (us, ca), 35 states, 102 cities and 18 UFO shapes. To filter the UFO sighting data, just type the any desired search criteria into the specified search fields. For example, one user would like to get all sighting in Florida, then he/she typed "fl", the abbreviation of Florida. As the following image shows, the table will dynamically update and return qualified results after entering search fields.  

<p align="center">
 <img src="https://github.com/Jarviniazh/Module-11-Challenge-UFOs-Analysis/blob/main/Resources/single_search.png?raw=true" alt="Single Search"/>
</p> 

**Attention: make sure enter information in the exact same format as sample given. All words should be lowercase.**

 - **Multiple search criteria**
 - This dynamic table is also able to handle multiple search criteria. For instance, the user would like to deep dive the sighting in Florida, so he/she input "1/8/2010" as the Date criteria and "fireball" as the prefered shape. Comparing with the single search criteria, the additional criteria reduced the results from ten to only one entry.

<p align="center">
 <img src="https://github.com/Jarviniazh/Module-11-Challenge-UFOs-Analysis/blob/main/Resources/multi_search.png?raw=true" alt="Multi Search"/>
</p> 

**Attention: If there is no matched date found, the table will be empty.**


## Summary

#### Drawbacks
Though there are five filters in total, if users entered all the five search criteria, they may not get any qualified data popup in the table. And users need to spend extra time figuring out which one or more criteria need to be deleted in order to get at least one data. For example one user entered: "1/8/2010", "miami", "fl", and "circle", then there is no matched info found as the image below shows. Since there is no sighting in Miami, if the user keeps Miami all the time and clear the other criteria, he/she would never get any information in the end. It finally will decrease users' satisfaction.

<p align="center">
 <img src="https://github.com/Jarviniazh/Module-11-Challenge-UFOs-Analysis/blob/main/Resources/drawbacks.png?raw=true" alt="Drawbacks"/>
</p> 

#### Recommendation
1. Add a Reset Button at below the filters, then if users would like to start over a new search, they can just click the Reset Button instead of clearing all the inputs or scrolling back and clicking. 
 
2. To make the filters easier to use, we could add dropdown menus for some filters (States, Countries, etc.). Therefore, the users would know the range of each criteria and avoid any typos. These further development would save a lot input time and increase the possibility that users could get at least one fulfilled result every time. Users don't need to adjust their inputs to make sure get some information in the table and would like to revisit Dana's webpage later.

