California Counties Impacted By Wildfires 2012-2020 
=====
### Overview:
  The project focused on creating a printable map Layout by compiling layer <br>
  data and perfomring analysis to calculate how much area of the state<br>
  was impacted by fires in the past 10 years.<br>
  
<img width="auto" alt="image" src="https://github.com/user-attachments/assets/18c3c015-8bad-4c29-9b56-48b782c8a7de">

### Technology used:  
- ArcGIS Pro      
- ArcGis Online

### ArcGIS Tools Used:
  Analysis Suite:<br>
    - Calculate Field, Pairwise Buffer, Near, Dissolve, Intersect, Summary Statistics<br>
  Data Managment Tools:<br>
    - Caoculate Field, Calculate Geometry, Add Join, Table Join<br>

### Project Details:
_________
1. Obtain Conty layout and Wilfdfire Data for California<br>
2. Import files into the Database, Create feature classes if needed.<br>
3. Ensure coordinate system is set to California for the projection and feature layers.<br>
4. Dissolve the boundaries between fires to create a layer to include all fires without separation.<br>
5. Merge the conties layer and the newly created fires layer to overlap where they intersect<br>
6. Use the Calculate Geometry Tool to calculate how much area is the fire is affecting in each county<br>
7. Use Calculate Field to populate columns for the table utilizing Python or preconfigured arguments<br>
8. Overlay the newly created layers and decrease opacity to properly visualize the area of imapct and state<br>
