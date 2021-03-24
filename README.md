![plot](docs/UAI.png)

### IACS-Inventor template
**This is IACS non-official inventor template!** 

### Introduction

<p align="justify"> Main purpose of this repository is allow good base for customization inventor template. Template is created and modifed from originaly IMID template, but contain only basics features, more specifics features must be programmed by your taste and needs.
</p>

### Functions

### Integration part
Follow the steps to integrate into Inventor(save-go):
1) download - ```git clone https://github.com/Steigner/IACS-Inventor_template.git```
2) open *Template_IACS*
3) save as template to e.g. *../Inventor/Templates/en-US/..*
4) restart Inventor
5) designe component -> new -> and u are ready to create tech. documenatation

### Modification part
If u want just modifed logo in title block documentation, follow:
1) Model -> Drawing Resources -> Title blocks
2) right click on e.g. IACS, and Edit
3) now u will be able to modifed logo and other stuff

In this original template is 2 title block language options[czech/english], but more can be added:
1) Model -> Drawing Resources -> Title blocks
2) right click on e.g. IACS, and Copy
   * or right click on e.g. IACS, and Insert
4) right click on Title blocks, and Paste
5) change name e.g. "de" -> right click Edit -> right click on e.g. Preccision, Edit text -> rename only text without ```<>``` e.g. Preccision - Präzision
6) save title block
7) find iLogic -> Rules -> add Rule, name it for example "de" -> add to code editor

```javascript
        ActiveSheet.TitleBlock = de
```

8) save&run
9) Forms -> right click on Edit -> find new rule, and drag&drop it to form -> OK

On that note can be added additional features by personal needs e.g. bill of materials, various calculations. If you find any bug or any inexactitude please leave issue comment. If you like it, hit star button and forked into your new project. 

### Sources
