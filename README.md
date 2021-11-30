<h1>Python-MySql-CRUD-System</h1>

### It is a program developed in Python and MySQL made with the aim of applying crud concepts.

>Status: Developing ⚠️

### Below I'll detail what each field of the Main Screen means:

![tela_incial](https://user-images.githubusercontent.com/38482348/144073254-0cdb17d7-4ecd-4a51-a703-a9564ca6a92d.png)


### Main title: 
+ Product Registration
### ⬜ Text entry: 
+ ⬜ Code    
+ ⬜ Product
+ ⬜ Price
### Title RadioButton: Category
### 🔘 RaddioButon Options:
+ 🔘 Computers
+ 🔘 Food
+ 🔘 Electronic

### 🔲 Button: List(Listar)
> List button: Makes a list of all registered components.
### 🔲 Button: Send(Enviar)
> Send button: Save the information added to the database.

---

![tela_listar](https://user-images.githubusercontent.com/38482348/144073607-d8cfa8e4-5456-4714-a232-e5a252e5ad80.png)

### Below I'll detail what each field of the List screen means:
### Main title: Product list screen
### The fields ID, CODE, ITEM, PRICE, CATEGORY represent the columns registered in the database.

### 🔲 Button: DELETE
> DELETE button: Deletes the selected line.
### 🔲 Button: PDF
>PDF button: Generates a pdf file with the information that is saved in the database. Note: This file will be saved in the same folder as the project.
### 🔲 Button: EDIT
> EDIT button: Allows you to edit the selected line.

---

### Below I'll detail what each field of the Edit screen means:

![tela_editar](https://user-images.githubusercontent.com/38482348/144073656-dd203b6a-a046-4e6d-ab94-b65c087f5de0.png)

### The screen has fields that represent the column information.

### 🔲 Save button: 
> Updates the information that has been modified.

---

## What is being developed:
### a screen that allows you to search for an item by the letter or keyword.

---

## Technologies used:

<table>
  <tr>
    <td>Python</td>
    <td>MySql</td>
  </tr>
  <tr>
    <td>3.9</td>
    <td>8.0</td>
  </tr>
</table>

### Python libraries used: 
<table>
  <tr>
    <td>PyQt5</td>
    <td>reportlab.pdfgen</td>
    <td>mysql.connector</td>
  </tr>

  <tr>
    <td>5.15.6</td>
    <td>3.6.3</td>
    <td>2.2.9</td>
  </tr>
 </table>
 
+ PyQt5: User Interface
+ reportlab.pdfgen: Generate Pdf
+ mysql.connector: Connect ing to the database

---

## How to run the application:
1) Download the repository
2) Run the file controle.py in the main folder.
3) Have fun exploring the possibilities, you will be able to add, query, edit and delete information through the graphical interface.

#### Note: To run the application correctly, you will need to have the respective technologies in place in the machine.
