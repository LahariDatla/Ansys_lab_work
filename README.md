# Ansys_lab_work
This repository consists of MODULE-3 and MODULE-5 Lab works of the VSD Semiconductor Packaging course.
# MODULE-3: Thermal Simulation of Semiconductor Packages with ANSYS
Step-1: Open ANSYS Electronics Desktop and go to project and click on Insert Icepak Design. 

![image](https://github.com/user-attachments/assets/b7a03188-cf74-44bd-b853-68738c6c3130)


 
Step-2:  For importing the in-built packaging model click on Icepak -> Toolkit ->  
         Geometry -> Packages -> Flipchip_BGA.

![image](https://github.com/user-attachments/assets/76c9c4a9-ce91-4e8b-8715-85c96a4e3531)
         
 
Step-3: After verifying the default dimensions click on OK to import the model.

![image](https://github.com/user-attachments/assets/57d54bdf-67a3-41c1-afec-0714395f8648)
 

Step-4: Click on 3D components or Model to observer various components inside the model.

![image](https://github.com/user-attachments/assets/67505e12-76e1-489e-99a5-ad7cb2178e64)
 

Step-5: Click on Thermal in Project Manager to get information about the boundary conditions.

![image](https://github.com/user-attachments/assets/a94ddac0-9d31-42f1-8de8-1a3ce5c3bdc8)


Step-6: Next step id to put is source boundary condition on the substrate.
        Flipchip_BGA1_substrate(right click)  -> assign Thermal -> Source.

![image](https://github.com/user-attachments/assets/b7ca24fb-cce0-408c-b472-a4d53d0f1b06)
  


Step-7: Remove the previously existing boundary condition to avoid overlapping.

![image](https://github.com/user-attachments/assets/6b42822d-583a-4733-90d2-fce38bc94992)
 


Step-8: Now put some monitors. Flipchip_BGA1_substrate(right click) -> Assign monitor -> Point -> Temperature.

![image](https://github.com/user-attachments/assets/33ccd4f0-9b2a-4ba0-bd96-ca756b4dbfee)
 

Step-9: Assign the monitor for Die and Underfill also.

![image](https://github.com/user-attachments/assets/ae43655a-bfe2-4eab-9853-b3a06d1cd445)
 

Step-9: Now for Meshing go to simulation and click on generate mesh and save the project. 

![image](https://github.com/user-attachments/assets/5f9c7e83-c2b0-4833-8051-3c509f4081b5)

![image](https://github.com/user-attachments/assets/0b5e17a2-2193-4f24-9959-62bb17011c9c)
 
 

Step-10: Next after Meshing we have to analysis. For analysis:
         Analysis (right click) -> add solution setup -> OK.

Step-11: Now click on Validate.

![image](https://github.com/user-attachments/assets/440a4a8e-c169-4f9c-8c3b-611026d3e49b)

Step-12: Click on Analyze All and once the analysis is done select the whole package(right   
                   click)  -> plot fields -> Temperature -> click on specify name, specify folder, plot on   
                   surface only, and now click on surface smoothing ->enable gaussian smoothing -> 
                   done.
 
 ![image](https://github.com/user-attachments/assets/f92a7d85-d4e9-44a8-8b02-89638175aa67)





# MODULE-5: Package Design and Modelling



Step-1: Go to project and click on Q3D Extractor Design.

Step-2: Create the die. Select rectangle to create die (dimensions 3mmX3mm and position (0,0,0) for center and thickness 0.2mm,material-silicon).

![image](https://github.com/user-attachments/assets/7b85b95a-de8c-4898-a229-d325eac09107)

Step-3: Now to create a substrate, select rectangle to create die (dimensions 5mmX5mm and position (-1,-1,-0.1) for center and thickness -0.5mm,material-FR4 epoxy).

![image](https://github.com/user-attachments/assets/571d6f8a-a83f-4b22-ba7f-f73f4f5d2707)

 
Step-4: To fill the gap between die and substrate i.e., die attach, we create another rectangle of same dimensions as die  (dimensions 3mmX3mm and position (0,0,0) for center ) and thickness -0.1mm,material-modified epoxy.

![image](https://github.com/user-attachments/assets/631a4fe1-ef1c-47de-a1bc-329621ea7e59)

 

Step-5: For creating Bond pad on die click on rectangle (dimensions 0.2mmX0.2mm and position (0.2,0.2,0.2) for center ) and thickness 0.005mm,material-copper.
For creating Bond pad on substrate click on rectangle (dimensions 0.2mmX0.2mm and position (0.2 ,-0.8 ,-0.1) for center ).

![image](https://github.com/user-attachments/assets/a37c5ef1-5769-4d3f-84f6-16029ba2e6f5)


Step-6: Now connect the two Bondpads click on bondwire in draw and use the default values and assign material as gold.

![image](https://github.com/user-attachments/assets/e908b72b-ff9d-4886-8665-bbd2635b0ef7)

  

Step-7: Similarly create the bondwires in all the four sides of the square.
 
![image](https://github.com/user-attachments/assets/cdb79a03-7fda-4922-be4e-f80d44c86a15)





Step-8: Now create Mold Compound using rectangle as same dimensions of substrate and thickness of 1.5mm and material epoxy to get final package.
 
![image](https://github.com/user-attachments/assets/62f41458-8aaa-44cf-802c-34f2288ce9cf)



  

                




                                                              


