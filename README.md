# MockarooProject

GOALS:
* Create a Java class MockarooDataValidation.java
* Navigate to https://mockaroo.com/
* Assert title is correct.
* Assert Mockaroo and realistic data generator are displayed
* Remove all existing fields by clicking on x icon link
* Assert that ‘Field Name’ , ‘Type’, ‘Options’ labels are displayed
* Assert that ‘Add another field’ button is enabled. Find using xpath with tagname and text. isEnabled() method in selenium
* Assert that default number of rows is 1000.
* Assert that default format selection is CSV
* Assert that Line Ending is Unix(LF)
* Assert that header checkbox is checked and BOM is unchecked
* Click on ‘Add another field’ and enter name “City”
* Click on Choose type and assert that Choose a Type dialog box is displayed.
* Search for “city” and click on City on search results.
* Repeat steps 12-14 with field name and type “Country”
* Click on Download Data.
* Open the downloaded file using BufferedReader.
* Assert that first row is matching with Field names that we selected.
* Assert that there are 1000 records
* From file add all Cities to Cities ArrayList
* Add all countries to Countries ArrayList
* Sort all cities and find the city with the longest name and shortest name
* In Countries ArrayList, find how many times each Country is mentioned. And print out ex: Indonesia-10
* From file add all Cities to citiesSet HashSet
* Count how many unique cities are in Cities ArrayList and assert that it is matching with the count of citiesSet HashSet.
* Add all Countries to countrySet HashSet
* Count how many unique cities are in Countries ArrayList and assert that it is matching with the count of countrySet HashSet.
* Push the code to any GitHub repo that you have and submit the url
* DOWNLOAD the pdf for requirements at : https://github.com/bbinbir/MockarooProject/blob/master/src/test/java/com/mockaroo/MockarooProject.pdf

TOOLS USED:
* Java, 
* Selenium,
* TestNg,
* Apache POI, 
* Agile, 
* Eclipse, 
* Git, 
* Chrome, 
* Pom Xml, 
* Maven.
