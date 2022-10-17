How to download LaTex and UiT template
LaTex download:
1. Download and install TeXlive (https://www.tug.org/texlive/)
2. Download and install TeXworks (https://tug.org/texworks/)
3. Open “white_paper.tex” in TeXworks. (Remember to have the bibl.bib file in the same folder as white_paper.tex for the example to work).
![image](https://user-images.githubusercontent.com/92987903/196160137-ebc7cf7e-5202-4849-ac29-28b504773c5c.png)
4. Generate files (pdf and other needed files):
a. Run/Play pdfLaTeX
b. Run/Play BibTeX
c. Run/Play pdfLaTeX
d. Run/Play pdfLaTeX


UiT Template setup:
1. Install uit-thesis-install.exe (https://github.com/egraff/uit-thesis-installer/releases/tag/v2.0.1)
2. Open “UiT_Template.tex” in TeXworks (Remember to have the bibl.bib, uit-thesis.cls and photos folder in the same folder as the UiT_Template.tex fpr the example to work)
3. Generate files.


Remember:
When using the UiT template on your own .tex document, the document needs to be of the “uit-thesis” type.
![image](https://user-images.githubusercontent.com/92987903/196160212-3e930c28-c39c-4441-ac6f-e9af29b0ccc1.png)

The uit-thesis.cls file also needs to be in the same folder as your own .tex document. The correct uit-thesis.cls can be found on the following repo: https://github.com/tanjaeh/ReportTemplate
Note: These lines should be commented out of the correct uit-thesis.cls file:
![image](https://user-images.githubusercontent.com/92987903/196160250-9be4466c-ad1d-455d-8503-fc00f5a4f3a4.png)


