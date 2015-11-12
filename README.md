# Fingal Garda Stations API


##Data-Representation and Querying Project


**Jason Thorne**
**G00317349**


##Overview##

This project outlines the design and documentation for the use of datasets regarding Garda Stations in Fingal.
These datasets are found at data.gov.ie, at the following [link] (https://data.gov.ie/dataset/garda-stations).
This API is designed to provide Fingal residents with information on where and how to contact their local guarda Station in the event of an emergency. This data can be also be useful for use at other times however. Such as by local Schools wishing to arrange Garda required events.  


##Dataset Description##

The data is recieved inComma Separated Values (CSV) format, from the following [link] (https://data.gov.ie/dataset/garda-stations).
The CSV file contains 19 rows. The first being the header row with the names of each field.
There are 15 columns of fields. These are as follows: 


Field Name | Description 
-----------|------------
Name|Station Name
Address1|Station Street Address
Address2|Station Town Address
Address3|Station County Address
Phone|Station Phone Number
Website|Station Website
Division|Station Division
Divisional_HQ|Division HQ
Divisional_HQ_Phone|Division HQ Phone Number
District|District
District_HQ|Dictrct HQ
District_HQ_Phone|Dictrct HQ Phone Number
Opening_Hours|Station opening hours
LAT|Station Latitude co-ordinates
LONG|Station Longitude co-ordinates
 
 
 

**Example of Data im CSV format:**


Name|Address1|Address2|Address3|Phone|Website|Division|Divisional_HQ|Divisional_HQ_Phone|District|District_HQ|District_HQ_Phone|Opening_Hours|LAT|LONG
-----------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------|------------
Balbriggan Garda Station|Drogheda Road|Balbriggan|Co. Dublin|+353 1 8020510|http://www.garda.ie/Stations/Default.aspx|Dublin Metropolitan Region Northern Division|Ballymun|+353 1 6664493|Balbriggan|Balbriggan|+353 1 8020510|Open 24hrs |53.61437815|-6.191052919





This came from [GMIT] (http://mySite.ie)


```c
int myfunction (int c)
{
  return c + c;
}
```
