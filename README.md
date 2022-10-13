Hvordan få LaTex og UiT template
Hvordan få LaTex
1.	Last ned TeXlive (https://www.tug.org/texlive/) 
2.	Last ned TeXworks(https://tug.org/texworks/)
3.	Kjør white_paper.tex (I texworks, HUSK å ha med bibl.bib filen i samme mappe som white_paper.tex for at eksemplet skal fungere)
 ![image](https://user-images.githubusercontent.com/92987903/195608544-c588bad6-be86-4367-ac8d-4c32685e6651.png)
4.	Generer filer:
a.	«Play» pdfLaTeX	
b.	«Play» BibTeX 		
c.	«Play» pdfLaTeX
d.	«Play» pdfLaTeX
 ![image](https://user-images.githubusercontent.com/92987903/195608571-bdcc2549-ed16-453e-8782-ae3351a637e8.png) ![image](https://user-images.githubusercontent.com/92987903/195608593-b7e4cd88-ab09-404a-a2a5-e6867f15f362.png)
Hvordan fikse UiT template
1.	Installer uit-thesis-install.exe (https://github.com/egraff/uit-thesis-installer/releases/tag/v2.0.1)
2.	Gå til C:\texlive\2022\texmf-dist\tex\latex\ut-thesis (ut-thesis mappen skal være synlig hvis uit-thesis-install.exe ble installert korrekt).
 ![image](https://user-images.githubusercontent.com/92987903/195608618-b3ab7b32-c94e-4a53-a5c4-c1edb26bd636.png)
3.	Bytt ut-thesis/uit-thesis.cls filen med uit-thesis.cls filen fra repo (https://github.com/tanjaeh/ReportTemplate)
Disse linjene skal være kommentert ut fra den nye uit-thesis.cls filen:  
![image](https://user-images.githubusercontent.com/92987903/195608730-4cf7f79f-036a-4fd4-aba1-4d5e5d6293b1.png)
4.	Kjør UiT_Template.tex (HUSK å ha med bibl.bib filen og photo mappen i samme mappe som som UiT_Template.tex for at eksemplet skal fungere)
5.	Generer filer
