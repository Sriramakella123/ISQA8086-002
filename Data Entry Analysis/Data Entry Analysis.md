_This assignment focus on Data Entry Analysis based on three files provided as pond2010,zoop-temp,zoop
temp-main_

## Title of Project
Data Entry Analysis

## Contributed by
Venkata Naga Sai Sriram Akella
September,12 2017.

## List of Data Files provided
* [pond2010](https://github.com/Sriramakella123/ISQA8086-002/blob/master/Data%20Entry%20Analysis/pond2010.xlsx)
* [zooptemp](https://github.com/Sriramakella123/ISQA8086-002/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp.xlsx)
* [zooptemp-main](https://github.com/Sriramakella123/ISQA8086-002/blob/master/Data%20Entry%20Analysis/zoop%20-%20temp-main.xlsx)

## Background
    Plankton are microscopic organisms that form the base of many aquatic food webs – fueling the growth of fish and other larger organisms. It’s common to sample them using a net or another container that can be controlled to collect water just from certain depths; so you can see how plankton collected at the surface (0 meters) might be different from plankton at another depth (e.g. 10 meters below the surface).

    (For more information: http://en.wikipedia.org/wiki/Phytoplankton (Links to an external site.)Links to an external site. and http://en.wikipedia.org/wiki/Zooplankton.) (Links to an external site.)Links to an external site.

    They are identified and counted under a microscope, and usually their numbers are reported as individuals per liter or milliliter.

    Frequently, aquatic scientists collect plankton samples during both day (e.g. noon) and night (e.g. 2 am) because plankton change their distributions from day to night, and not all species alter their distributions in the same way. (For more information, search “diel vertical migration” on the web.)

## Problem Synopsis
The 3 files linked above were all intended to be part of the same study – the investigators wanted to examine the day-night distribution of 2 species of zooplankton across multiple years. The type of zooplankton they studied is called rotifers generally, and specifically the genus Conochilus, in which groups of individual rotifers stick together in colonies (see http://eol.org/pages/43393/overview (Links to an external site.)Links to an external site.). The investigators plan to repeat this study for several more years.

## Task-1 Identifying Problem Statment

The problems in the provided data files are as identified -
1. The species data( Zooplankton - **zoop-temp.xlsx** and **zoop-temp-main.xlsx** )  is maintained in seperate files which makes unnecessary data storage space that can be eliminated.
2. The day and night distribution of data is difficult to maintain because the timings are not maintained.
3. In the data file **zoop-temp.xlsx** it is mentioned that  _"Station B is in a shallower southern arm of the lake, see yellow notebook for map and details"_ . However such yellow notebook or the marked details are not available.
4. Further for all the data files,the time of data collection is not collected, which might mislead the data analysts and examiners in analyzing the behaviour of species
5. The years in which the data are collected for the zoop as well as the pond are not same. The zoop data file is collected in the year 2011 while pond data in 2010 which leads to false analysis.
6. The unit of measurement for the columns is not mentioned in any of the data files provided and this is same with respect to pivot chart.The variables plotted have no labels.
7. In few columns like "Number of chippo.cuni per litre" there exists certain negative values which are not valid.
8. The columns in the data files are abbreviated and that doesn't provide a clear information with respect to the end user perspective.A definition or the meaning of a column is not provided which makes difficult to analyze the data.

    Note:Though the abbreviations are provided they are maintained in a seperate spreadsheet and the in extension the pivot chart included doesnot provide much details.

## Task-2 Solution

The solutions to the above mentioned problems are as mentioned - 
1. The data files **"zoop-temp.xlsx and zoop-temp-main.xlsx"** needs to be merged into a single spreadsheet.
2. A column with the name as "Location or Place" can be added and necessary link can be provided .Any other important details and extra details can be provided as "Additional Details".
3. The data file can have "Time" column included in both the zoop file and the pond files respectively.
4. Year in which data is collected is included for better data storage, filing and analysis.
5. The data storage of the files can be done in a single location or a arepositiory that helps in data integrity and redundany of data.
6. Correspondingly, a data dictionary and the terms of usage of data for analysis and its validity should be properly documented.
7. The unit of measurement of data can be included besides the column header.And the data variables for the charts or analysis needs to be provided for better data understanding.
8. Additionally, data correction or validation tools or statistical softares like SPSS can be used for efficient data entry compared to excel.

## Tables
**Table A: Chippo(Conochilus hippocrepis
) Table**  

| Time (Estimated) | Date | Location | Temperature (Degree Celsius) | Density (kilogram / cubicmetre) | Colony Diameter (metre) | Species | Depth (metre) | Chippo #/L | Chippo Colony Size (millimetre) | Chlorophyll A | Station | Additional Information |
|------------------|------|----------|------------------------------|---------------------------------|-------------------------|---------|---------------|------------|---------------------------------|---------------|---------|------------------------|
|                  |      |          |                              |                                 |                         |         |               |            |                                 |               |         |                        |

**Table B: Cuni(Conochilus unicornis
) Table**  

| Time (Estimated) | Date | Location | Temperature (Degree Celsius) | Density (kilogram / cubicmetre) | Colony Diameter (metre) | Species | Depth (metre) | Cuni #/L | Cuni Colony Size (millimetre) | Chlorophyll A | Station | Additional Information |
|------------------|------|----------|------------------------------|---------------------------------|-------------------------|---------|---------------|------------|---------------------------------|---------------|---------|------------------------|
|                  |      |          |                              |                                 |                         |         |               |            |                                 |               |         |                        |



