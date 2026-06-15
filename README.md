# Sci-Low-Code
Library for Scientific Computing and Low Code Develpment.
This project is a Spin-Off of the University of Applied Sciences Aalen.
The former project UABM https://www.hs-aalen.de/UABM, or on github https://github.com/U-A-B-M/UABM, is set dormant, the present project is its continuation.

The present Excel Add-In facilitates the following use cases:
1. Numerical Curve Sketching
2. Loan Calculation and Investment Appraisal 
3. Master Data Management: CRUD (Create, Read, Update, Delete), from DBMS (https://en.wikipedia.org/wiki/Database#Database_management_system), ex. https://en.wikipedia.org/wiki/Create,_read,_update_and_delete
4. Low Code / No Code Development
5. Rapid Prototyping
6. Optimization

# Language support
Currently the 4 languages English, Chinese/Mandarin (中文，普通话), German, Vietnamese (Tiếng Việt) are supported. It is possible to set a 1st and 2nd language from the 4 languages mentioned before:
1. The 1st language is displayed in the first place, surprise 😀. If no 1st language is set then the display language defaults to English.
2. If a 2nd language is set (facultative), the the UI is displayed in this language as well, right after the 1st language.

Okay .., this makes the UI a tad overcrowded 😀, but it's fun 😎, seee the examples below.

For example, English combined with Chinese/Mandarin:

<img width="457" height="417" alt="image" src="https://github.com/user-attachments/assets/c4a0b13c-c283-4eeb-a86a-bbee7f2fbbf8" />

Or Vietnamese with German:

<img width="462" height="415" alt="image" src="https://github.com/user-attachments/assets/dcca07e6-7784-477d-8758-ef25193df31f" />


# Architecture  
<img width="1177" height="642" alt="image" src="https://github.com/user-attachments/assets/bdc55e05-4566-4058-bcfd-59bada36489d" />

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
<img width="1062" height="431" alt="image" src="https://github.com/user-attachments/assets/76304dbf-8166-4994-994b-d810ad56cb85" />

The expected outcome of a numerical curve sketch will be alog the lines of the next acreenshot - depending on the function analyzed different shapes and numbers will occur:
<img width="1214" height="715" alt="image" src="https://github.com/user-attachments/assets/b76c724d-d7c8-4f23-8d9e-d19dac3cec74" />
