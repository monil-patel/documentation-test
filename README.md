Documentation Repo
====
Utilizes docfx framework which is developed by Microsoft and used for the offical docs https://docs.microsoft.com/en-us/.   

We will have repos within the Azure org
Each extension can create their own repository like this one to host their own documenation
https://azure.github.io/eswm-extension-name/


### How to modify this repo
The outer toc.yml (table of contents) file defines the top level navigation on the page

The technical documentation readmes are located under the **articles** folder. This folder also contains its own toc.yml file which defines the side navigation structure located on the left hand side of the page. This supports nested levels if needed. 

So if you want to add another file to the site there are two steps  
1. add another entry to the articles/toc.yml file  
```
 - name: Display name
   href: newfile.md 
```

2. add the .md file to articles folder
``` 
articles/newfile.md
```

