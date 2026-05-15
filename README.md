# Sci-Low-Code
Library for Scientific Computing and and Low Code Develpment.
This code repository is a Spin-Off of the University of Applied Sciences Aalen.
The former project UABM https://www.hs-aalen.de/UABM, or on github https://github.com/U-A-B-M/UABM, is set dormant, the present project is its continuation.

The present Excel Add-In facilitates the following use cases:
1. Numerical Curve Sketching
2. Loan Calculation and Investment Appraisal 
3. Master Data Management: CRUD (Create, Read, Update, Delete), from DBMS (https://en.wikipedia.org/wiki/Database#Database_management_system), ex. https://en.wikipedia.org/wiki/Create,_read,_update_and_delete
4. Low Code / No Code Development
5. Rapid Prototyping
6. Optimization

The nextr graphic visualizes 2 things:
1. The Office Technology Stack, exemplified on Excel. We have the following layers:
   a. Top layer: Excel, the well-known spreadsheet calculation programm.
   b. Below the VBA = "Visual Basic for Application" layer. Here, one may automatize Excel by programatically accessing Excel components (cells, sheets, etc)
   c. DLL-Layer: DLL (Dynamic Link Library) are most obscure and represent
       --> libraries programmed usually in C, and
       --> compiled into machine languages, which
       --> can be dynamically integratedin Excel.
   As a matter of fact, the numerical procedures "Newton's Method" 8https://en.wikipedia.org/wiki/Newton%27s_method) and "Gradient Descent" (https://en.wikipedia.org/wiki/Gradient_descent) are already integrated in Excel ... .
   
2. The SciLowCode simply chooses the "right" components from the above technology stack and makes them available as Excel menu. A schematic content of SciLowCode is indicated as layer on the Office Technology Stack.      
<img width="1046" height="610" alt="SciLowCodeArchitecture" src="https://github.com/user-attachments/assets/f4fadc6d-a9d8-4e12-a449-351e4f671f4a" />
