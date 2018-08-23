# Contributing to definitions

## Git Commit Guidelines

Read this article how to write meaningful commit messages:
[How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)

With the expectations listed below, we follow the rules contained in
[AngularJS's Git Commit Guidelines](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#-git-commit-guidelines):

 -  **Type**: Must be one of the following
     -  **feat**: A new definition, exercise, workshop or material
     -  **fix**: A bug fix
     -  **refactor**: A code change that neither fixes a bug nor adds a feature
     -  **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
     -  **chore**: Changes to the build process or auxiliary tools and libraries such as documentation generation

## Working on branches
-  Always work on your separate feature branch. 
-  The name of the branch should contain the title of the feature, your name can be also included but that's optional. 
-  Your name only as a branch name is invalid.

## Submission Guidelines

Before you submit your changes consider the following guidelines:
 -  We use Pull Requests for reviewing definitions and materials
 -  The pull request must be reviewed by an other mentor
     -  The review should include completing (or reviewing if already completed) the solutions for the exercises in the [solutions repository](https://github.com/green-fox-academy/solutions)
 -  Delete your branches after the pull request is merged


## Naming conventions

### WebElements

UI                         | Prefix  | Example
-------------------------- | ------  | --------------- 
Button                     | btn     | btn_Exit        
Check box                  | chk     | chk_ReadOnly    
Combo box                  | cbo     | cbo_English     
Common dialog              | dlg     | dlg_FileOpen    
Date picker                | dtp     | dtp_Published   
Dropdown List / Select tag | ddl     | ddl_Country     
Form                       | form    | form_Entry       
Frame                      | fra     | fra_Language    
Image                      | img     | img_Icon        
Label                      | lbl     | lbl_HelpMessage 
Links/Anchor Tags          | lnk     | lnk_ForgotPwd   
List box                   | lst     | lst_PolicyCodes 
Menu                       | mnu     | mnu_FileOpen    
Radio button / group       | rdo     | rdo_Gender      
RichTextBox                | rtf     | rtf_Report      
Table                      | tbl     | tbl_Customer    
TabStrip                   | tab     | tab_Options     
Text Area                  | txa     | txa_Description 
Text box                   | txt     | txt_LastName
Chevron                    | chv     | chv_Protocol    
Data grid                  | dgd     | dgd_Titles      
Data list                  | dbl     | dbl_Publisher   
Directory list box         | dir     | dir_Source      
Drive list box             | drv     | drv_Target      
File list box              | fil     | fil_Source      
Panel/Fieldset             | pnl     | pnl_Group       
ProgressBar                | prg     | prg_LoadFile    
Slider                     | sld     | sld_Scale       
Spinner                    | spn     | spn_Pages       
StatusBar                  | sta     | sta_DateTime    
Timer                      | tmr     | tmr_Alarm       
Toolbar                    | tlb     | tlb_Actions      
TreeView                   | tre     | tre_Organization

### POM Functions

WebElement                 | PageObjectModel          | Example
-------------------------- | -------------------------| ---------------------------- 
WebElement.click()         | page.clickOn(pageField)  | mainPage.clickOn(lnk_SignIn)
WebElement.isDisplayed()   | page.isLoaded(pageField) | mainPage.isLoaded(btn_Apply)
