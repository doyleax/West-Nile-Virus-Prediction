
File descriptions

* train.csv, test.csv - the training and test set of the main dataset. The training set consists of data from 2007, 2009, 2011, and 2013, while in the test set you are requested to predict the test results for 2008, 2010, 2012, and 2014. 
  * Id: the id of the record Date: date that the WNV test is performed 
  * Address: approximate address of the location of trap. This is used to send to the GeoCoder. 
  * Species: the species of mosquitos Block: block number of address Street: street name 
  * Trap: Id of the trap AddressNumberAndStreet: approximate address returned from GeoCoder 
  * Latitude, Longitude: Latitude and Longitude returned from GeoCoder 
  * AddressAccuracy: accuracy returned from GeoCoder 
  * NumMosquitos: number of mosquitoes caught in this trap 
  * WnvPresent: whether West Nile Virus was present in these mosquitos. 1 means WNV is present, and 0 means not present. 

* spray.csv - GIS data of spraying efforts in 2011 and 2013 
  * Date, Time: the date and time of the spray 
  * Latitude, Longitude: the Latitude and Longitude of the spray 

* weather.csv - weather data from 2007 to 2014. Column descriptions in noaa_weather_qclcd_documentation.pdf. 
* sampleSubmission.csv - a sample submission file in the correct format
