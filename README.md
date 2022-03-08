# Readme
This dataset was created for a course at the iSchool at the University of Washington in the winter of 2022. It is a study of children experiencing homelessness present in Minnesota counties (Minneapolis/Hennepin, Duluth/St. Louis and Rochester/Southeast) 2020. The intended audience for social workers and/or social services. It is freely available to the public. 

The dataset is available in both. xlxs and .csv format. There are two documents, the first is the raw data, the second is the extracted data pertaining to specified data. The extracted data is the number of children experiencing homelessness in different communities, allowing for comparison for social and community improvement. There are no duplicate variables, and all fields have been parsed and standardized and: no cleaning should be necessary. 

# Naming
Naming for the files should be as follows:
```
    year_datasettype
```

Where *year* is the year of the data being reported, and where *datasettype* indicates whether it is the raw data ("raw") or extracted ("extracted"). 

# Data Dictionary

| Variable | Variable Label | Variable Type |	Allowed Values        | Definition                                        |
| -------- | -------------- | ------------- | --------------------- | ------------------------------------------------- |
| State	   | CocState       |	String	      | 2 Letter Abbreviation |	State abbreviation where the count was collected. | 
| County   | CoC	          | String	      | Text 	                | City and County where the count was collected.    |
| HUD Code | HudNum         |	Numeric	      | Any Number	          | HUD assigned numeric code to assigned as part of the CoC program.|
| Year	   | year	          | Numeric	      | YYYY	                | Year count was collected.|
| Date and Time | HIC Date  |	Numeric	      | MM/DD/YYYY | The date the count was collected.|
| Dedicated Beds for Children | Beds HH w/ Children |	String | Any Number NULL	| The total number of available beds for homeless persons on the date of the inventory count.| 
| Total number Households w/ Children |	Units HH w/ Children | String |	Any Number NULL |	The total number of units available for occupancy on the night of the inventory count.| 
| Veteran Household w/ children	| Veteran Beds HH w/Children | String |	Any Number NULL | The number of beds occupied on the night of the count reserved to veteran households with children.|
| Youth Households w/ children | Youth Beds HH w/ Children | String |	Any Number NULL | The number of beds occupied on the night of the count reserved for youth households with children.|
| Chronically Homeless w/ children | CH Beds HH w/ Children | String | Any Number NULL | The number of beds occupied on the night of the count reserved for chronically homeless with children.|
| Household w/ only children | Beds HH w/ only children | String | Any Number NULL | The number of beds occupied on the night of the count reserved for households composed exclusively of only children.|
| Chronically Homeless households w/ only children | CH Beds HH w/ only Children |String | Any Number NULL | The number of beds occupied on the night of the count reserved for chronically homeless households composed exclusively of only children. |

# Metadata

Schema Used: Project Open Data

| Attribute| Value |
| -------- | ----- |
| accessLevel |	Public |
| accuralPeriodicity | R/P1Y |
| fn | Monica Wigdahl |
| hasEmail | monicawigdahl@gmail.com |
| describedBy | https://github.com/monica-wigdahl/mn_homelessness |
| description | This dataset is a Housing Inventory Count (HIC) of children experiencing homelessness present in Minnesota counties (Minneapolis/Hennepin, Duluth/St. Louis and Rochester/Southeast) 2020. This dataset was created for a course at the iSchool at the University of Washington in the winter of 2022. |
| accessURL | https://github.com/monica-wigdahl/mn_homelessness/blob/main/2020_HIC_Raw.csv |
| format | CSV |
| mediaType | CSV |
| conformsTo | https://project-open-data.cio.gov/v1.1/schema |
| issued | 2022-03-07 |
| keyword | "homelessness", "children", "Minnesota", "Duluth", "Rochester", "Hennepin county", "St. Louis county", "Southeast county", "homeless" |
| language | en-us |
| modified | 2022-03-07 |
| publisher | Monica Wigdahl |
| references | https://www.hudexchange.info/resource/3031/pit-and-hic-data-since-2007/ |
| rights | These data are freely available to all people, both in this repository and their respective government repositories |
| license | https://github.com/monica-wigdahl/mn_homelessness/blob/main/LICENSE |
| theme | Homelessness, children |
| Title |	MN Homeless Children |

# Security 
These data are freely avaible to the public. 

# Contact
Monica Wigdahl monicawigdahl@gmail.com

