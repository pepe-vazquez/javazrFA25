---
title: About Hextra Theme
type: docs
prev: docs/Commands/
---
## Organize files

By default, Hugo searches for Markdown files in the content directory and the structure of this directory determines the final output structure. Here is my proposal:

📦content  
 ┣ 📂docs  
 ┃ ┣ 📂assignments  
 ┃ ┃ ┣ 📂week-01  
 ┃ ┃ ┃ ┣ 📂images-01  
 ┃ ┃ ┃ ┗ 📜_index.md  
 ┃ ┃ ┣ 📂week-02  
 ┃ ┃ ┃ ┣ 📂images-02  
 ┃ ┃ ┃ ┗ 📜_index.md  
 ┃ ┃ ┣ 📂week-03  
 ┃ ┃ ┃ ┣ 📂images-03  
 ┃ ┃ ┃ ┗ 📜_index.md  
 ┃ ┃ ┣ 📂week-xx  
 ┃ ┃ ┃ ┣ 📂images-xx  
 ┃ ┃ ┃ ┗ 📜_index.md  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┣ 📂commands  
 ┃ ┃ ┣ 📜abouthextra.md  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┣ 📂finaldiary  
 ┃ ┃ ┣ 📂finalproject  
 ┃ ┃ ┃ ┗ 📜_index.md  
 ┃ ┃ ┣ 📂images-fd  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┣ 📜about.md  
 ┃ ┣ 📜studentagreement.md  
 ┃ ┗ 📜_index.md  
 ┗ 📜_index.md  

## Images
I have decided to organise all the images corresponding to each week in a separate folder.

## Layouts
Three layouts for diferent content types:  
**docs** content/docs Structured information  
**blog** content/assigments and content/FinalDiary for publish the work done each week. With listing and detailed article views   
**default** All other directories single-page article view without sidebar   

## Configuration
Top right menu under is define under the menu.main section in the config file: hugo.yaml

## Footer
I must create a file called _i18n/en.yam
The footer has been one of the sections that I had the hardest time customising, but in the end I think I managed to do it.