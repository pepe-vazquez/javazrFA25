---
title: About Hextra Theme
type: docs
prev: docs/Commands/
---
## Organize files

By default, Hugo searches for Markdown files in the content directory and the structure of this directory determines the final output structure. Here is my proposal:

📦content  
 ┣ 📂assignments  
 ┃ ┣ 📂week-1  
 ┃ ┃ ┣ 📂images-1  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┣ 📂week-2  
 ┃ ┃ ┣ 📂images-2  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┗ 📜_index.md  
 ┣ 📂docs  
 ┃ ┣ 📂commands  
 ┃ ┃ ┣ 📜abouthextra.md  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┣ 📜studentagreement.md  
 ┃ ┗ 📜_index.md  
 ┣ 📂FinalDiary  
 ┃ ┣ 📂finalproject  
 ┃ ┃ ┗ 📜_index.md  
 ┃ ┣ 📂images-fd  
 ┃ ┗ 📜_index.md  
 ┣ 📜about.md  
 ┗ 📜_index.md  

## Layouts
Three layouts for diferent content types:  
**docs** content/docs Structured information  
**blog** content/assigments For publish the work done each week. With listing and detailed article views  
**blog** content/FinalDiary  
**default** All other directories Single-page article view without sidebar   

## Images
I have decided to place the images under the static folder
![](/images/image.png)

## Configuration
Top right menu under is define under the menu.main section in the config file: hugo.yaml

## Footer
I must create a file called _i18n/en.yam_