This project contains system models of AUV-LER, and the AC generation/ FM verificaiton procedures(folders named with "number.xx").

Step 1: Metamodel register
	-SACM metamodel
	-Hazardlog metamodel
	-RoboChart metamodel
	
Step 2: AC generation by running X.lauch files in folders of "1. hazard log transform- excel to emf", "2. emf HL to SACM AC",and "3. RoboChart model query to SACM model"

Step 3: AC claim verificaiton by FDR model checking 
	-run X.lauch files in "4. FDR assertion generation from AC claim" folder
	-run x.assertions files generated by right click -RoboTool-CSP- Run
	