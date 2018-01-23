# ComplianceReportGenerator
Table of Contents
Table of Contents
1.0	PURPOSE	3
2.0	SCOPE	3
3.0	ASSOCIATED DOCUMENTS	3
4.0	DESCRIPTION OF SYSTEM/SYSTEM INTENDED USE	3
5.0	TOOL VERSION	3
6.0	INSTRUCTIONS FOR INSTALLATION	3
7.0	INSTRUCTIONS FOR USE	3
8.0	SUPPORT PLAN	4
9.0	TRAINING MATERIAL	4
10.0	FILE LISTING	4
APPENDIX A– DEVELOPER INSTRUCTIONS	4


 
1.0	PURPOSE
The purpose of this document is to provide detailed instructions and information regarding the proper use of the Compliance Report Generator Tool. 
2.0	SCOPE
The information in this document covers the steps to be taken for proper operation and preparation for the Compliance Report Generator The software will be used during any Compliance Report generation where the document contains references to other documents that are needed to fill up the IEC 62304 Compliance Audit Report. 
Instructions necessary to perform the Compliance Report Generator Tool, as well as the steps needed for the setting up of the environment is discussed here
3.0	ASSOCIATED DOCUMENTS

60086597- Compliance Report Generator Electronic Records/Electronic Signatures Compliance
60086597- Compliance Report Generator Level of Concern Assessment.
4.0	DESCRIPTION OF SYSTEM/SYSTEM INTENDED USE

The software will be used during any Compliance Report generation where the document contains references to other documents that are needed to fill up the IEC 62304 Compliance Audit Report. The NPS will easily identify the documents needs to fill the template.
5.0	TOOL VERSION

This version of Compliance Report Generator Tool is 1.0. 
6.0	INSTRUCTIONS FOR INSTALLATION

The tool works best for Microsoft Office 2010 and above.
7.0	INSTRUCTIONS FOR USE

•	Copy the folder Compliance Report Gen into your local computer.
•	Run the GUI.exe file
•	A pop up will appear asking you to select the firmware type. Press start.
•	Let the program indicate you to press OK.
•	Make the required selections by pressing the OK button (Use the arrow button to make the list move around)
•	Follow the instructions at the end to generate the compliance report.
NOTE 1: If the program crashes in between selections, run GUI.exe and press start to resume from last selection.
NOTE 2: If the program crashes after all the selections have been made, run GUI.exe and press OK.
8.0	SUPPORT PLAN
Software Development Quality will be responsible for the maintenance and update of this tool.
9.0	TRAINING MATERIAL
Engineers will be trained by performing the instructions for installation and instructions for use detailed in this document. No formal training is required.
10.0	FILE LISTING

•	GUI.exe
•	Template.docx
APPENDIX A– DEVELOPER INSTRUCTIONS
Environment Setup
In order to develop the Compliance report Generator Tool, the proper environment must be setup for code compilation and editing. The source code for the tool is developed using Microsoft Visual C# 2015 Express. A valid installation of Microsoft Office 2010 or greater is recommended. 
Editing the code
Open the GUI.sln in Microsoft Visual C# 2015 Express and make the necessary changes.  Add Microsoft word and excel reference (Project-> Add reference). 

