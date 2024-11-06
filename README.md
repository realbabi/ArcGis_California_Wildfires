California Counties Impacted By Wildfires 2012-2020 
  Overview: 
    The project focused on creating a printable map Layout by compiling layer data and perfomring analysis to calculate how much area of the state 
    was impacted by fires in the past 10 years.
<img width="auto" alt="image" src="https://github.com/user-attachments/assets/18c3c015-8bad-4c29-9b56-48b782c8a7de">

Technology used:  
  ArcGIS Pro      
  ArcGis Online

ArcGIS Tools Used:
  Analysis Suite:
    Calculate Field, Pairwise Buffer, Near, Dissolve, Intersect, Summary Statistics
  Data Managment Tools:
    Caoculate Field, Calculate Geometry, Add Join, Table Join

Project Details:
  Obtain Conty layout and Wilfdfire Data for California
  Import files into the Database, Create feature classes if needed.
  Ensure coordinate system is set to California for the projection and feature layers.
  Dissolve the boundaries between fires to create a layer to include all fires without separation.
  Merge the conties layer and the newly created fires layer to overlap where they intersect
  Use the Calculate Geometry Tool to calculate how much area is the fire is affecting in each county8
  
