# GIS_STREETS.Bike_Network

### Summary  

Network of streets within City of Philadelphia with bike lanes and/or bike-friendly markings.   
  
Attributes updated: 02/11/2014  
Metadata updated: 02/11/2014  
Update Frequency: As needed

### Description  

Abstract:Bicycle Network for the City of Philadelphia FIELD DESCRIPTIONSSEG_ID - Unique segment identifierSTREETNAME - complete street name including directional prefix; street name; street type; directional suffixST_CODE - street code, the unique street name identifierONEWAY - travel direction of street segment, relative to the digitized direction of segmentCLASS - Street classification related to traffic volume and drivabliltyDOMAIN VALUES FOR FIELD CLASS:1 - Expressway2 - Major arterial3 - Minor arterial4 - Collector5 - Local6 - Driveway9 - Low speed ramps10 - High speed ramps12 - Non-travelable13 - New roads under construction14 - City boundary15 - Walkway connector18 - Traffic-controlled crosswalksTYPE - Bike network classificationDOMAIN VALUES FOR FIELD TYPE:B - Buffered - A bike lane separated from motor vehicle traffic by a painted buffer.C - Conventional - Typically, a 5' to 6' bike lane marked with bike symbolsBC - Buffered w Conventional - A buffered bike lane in one direction and a conventional bike lane in the opposite direction.BS - Buffered w Sharrows - A buffered bike lane in one direction and a lane with sharrows in the opposite direction.CT - Cycle track - A physically separated one-way bike lane, typically operating in the same direction as motor vehicles. Bikes are separated from both motor vehicle traffic and the sidewalk by physical barriers such as curbs, bollards, parked cars, etc.CTC - Cycle track w Conventional - A cycle track in one direction and a conventional bike lane in the opposite direction.CTS - Cycle track w Sharrows - A cycle track in one direction and a lane with sharrows in the opposite direction.TCT - Two-way Cycle track - A two-way cycle track. Unless in the middle of the street, this will operate as contra-flow at intersections.CF - Contraflow - A typical 5' to 6' bike lane, but with bikes traveling in the opposite direction from motor vehicles.CFCO - Contraflow w Conventional, opposite - Two bike lanes in opposite directions on opposite sides of a one-way street.CFCS - Contraflow w Conventional, same - Two bike lanes in opposite directions on the same side of a one-way street. Typically, the bike lane closest to motor vehicle traffic will operate in the same direction with it.CFS - Contraflow w Sharrows - A contraflow on one side of a one-way street, with sharrows in a traffic lane.CS - Conventional w Sharrows - A conventional bike lane in one direction and a lane with sharrows in the opposite direction. Typically used on hills where there is no room for lanes in both direction, and called a Climbing Lane.S - Sharrow - A general traffic lane with bike symbols and chevron arrows placed at intervals to indicate bicycle use and safe alignment.BF - Bicycle Friendly Street - A street with various treatments, including sharrows and bicycle signage at a minimum, to encourage bicycle use. May include traffic calming measures.SGO - Signed Only - A street that is signed for bike use, but has no other bicycle accommodation. Used for easy biking streets that form important links in the bicycle network.SP - Sidepath - A sidewalk where bicycling is permitted in both directionsSPOW - One-way sidepath - A sidewalk where bicycling is permitted in only one direction, the direction of adjacent motor vehicle traffic.Spatial_Reference_Information:Horizontal_Coordinate_System_Definition:Planar:Map_Projection:Map_Projection_Name:Lambert Conformal Conic Lambert_Conformal_Conic:Standard_Parallel:39.933333 Standard_Parallel:40.966667 Longitude_of_Central_Meridian:-77.750000 Latitude_of_Projection_Origin:39.333333 False_Easting:1968500.000000 False_Northing:0.000000 Planar_Coordinate_Information:Planar_Coordinate_Encoding_Method:coordinate pair Coordinate_Representation:Abscissa_Resolution:0.000256 Ordinate_Resolution:0.000256 Planar_Distance_Units:survey feet Geodetic_Model:Horizontal_Datum_Name:North American Datum of 1983 Ellipsoid_Name:Geodetic Reference System 80 Semi-major_Axis:6378137.000000 Denominator_of_Flattening_Ratio:298.257222 Vertical_Coordinate_System_Definition:Altitude_System_Definition:Altitude_Resolution:1.000000 Altitude_Encoding_Method:Explicit elevation coordinate included with horizontal coordinates   

### Data Dictionary

| Field | Description  
| ----- | :----------:  
| FID |  
| Shape |  
| SEG_ID |  
| STREETNAME |  
| ST_CODE |  
| ONEWAY |  
| CLASS |  
| TYPE |  
| SHAPE_LEN |  


### Credits  

Created and Maintained By: Charles Camalt, Aaron Ritz, Jeanette Brugger, Max Steinbrenner  
  
Layer posted by: Streets Department GIS Unit  
  
Contact: Max Steinbrenner - (215)686-5093 - max.steinbrenner@phila.gov  


### Use Limitations  

Distribution_Liability: The City of Philadelphia makes no warranty or representation, express or implied, with respect to the quality, content, accuracy, completeness, currency, freedom from computer virus, or non-infringement of proprietary rights, of any of the design, information, text, graphics, images, pages, interfaces, links, software, or other materials and items contained in this dataset. All such items and materials are provided on an "as is" basis, and you are fully and solely responsible for your use of them and for any results or consequences of your use. They have been compiled from a variety of sources, including sources beyond the control of the City of Philadelphia and, and are subject to change without notice from the City of Philadelphia. Commercial use is prohibited without the prior written permission of the City of Philadelphia. In no event shall the City of Philadelphia or their agencies, officers, employees, agents, or representatives, be liable for any direct, indirect, special, punitive, incidental, exemplary or consequential damages arising your accessing or using this data, or otherwise arising from the data or from anything contained in or displayed in this data. Nothing contained in or displayed in this data constitutes or is intended to constitute legal advice by the City of Philadelphia or any of their agencies, officers, employees, agents or representatives. These terms and conditions and all disputes arising under these terms and conditions shall be governed, construed and decided in accordance with the laws of the Commonwealth of Pennsylvania. The City of Philadelphia reserves the right to revise and change these terms and conditions at anytime and without any notice. 