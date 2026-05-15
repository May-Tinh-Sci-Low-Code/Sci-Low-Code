# Sci-Low-Code
Library for Scientific Computing and and Low Code Develpment.
This project is a Spin-Off of the University of Applied Sciences Aalen.
The former project UABM https://www.hs-aalen.de/UABM, or on github https://github.com/U-A-B-M/UABM, is set dormant, the present project is its continuation.

The present Excel Add-In facilitates the following use cases:
1. Numerical Curve Sketching
2. Loan Calculation and Investment Appraisal 
3. Master Data Management: CRUD (Create, Read, Update, Delete), from DBMS (https://en.wikipedia.org/wiki/Database#Database_management_system), ex. https://en.wikipedia.org/wiki/Create,_read,_update_and_delete
4. Low Code / No Code Development
5. Rapid Prototyping
6. Optimization


# Architecture  
<img width="1046" height="610" alt="SciLowCodeArchitecture" src="https://github.com/user-attachments/assets/f4fadc6d-a9d8-4e12-a449-351e4f671f4a" />
The graphic visualizes 2 things:

A. The Office Technology Stack, exemplified on Excel. We have the following layers:
1. Top layer: Excel, the well-known spreadsheet calculation programm.
2. Below Excel-Layer the VBA = "Visual Basic for Application" layer. Here, one may automatize Excel by programatically accessing Excel components (cells, sheets, etc)
3. DLL-Layer: DLL (Dynamic Link Library) are most obscure and

       --> represent libraries programmed usually in C, and
   
       --> compiled into machine languages, which
   
       --> can be dynamically integrated in Excel.


   As a matter of fact, the numerical procedures "Newton's Method" (https://en.wikipedia.org/wiki/Newton%27s_method) and "Gradient Descent" (https://en.wikipedia.org/wiki/Gradient_descent) are already integrated in Excel ... .
   
B. The SciLowCode Archtecture: SciLowCode simply chooses the "right" components from the above technology stack and makes them available as Excel menu. A schematic content of SciLowCode is is overlaying the Office Technology Stack.

# Use case Numerical Curve Sketching

<img width="1726" height="781" alt="image" src="https://github.com/user-attachments/assets/06e8bcb3-096c-483f-ac8b-dc4569aecacc" />

The expected outcome of a numerical curve sketch will be alog the lines of the next acreenshot - depending on the function analyzed different shapes and numbers will occur:
<img width="1214" height="715" alt="image" src="https://github.com/user-attachments/assets/b76c724d-d7c8-4f23-8d9e-d19dac3cec74" />
