# AutoDelarWebsite_Django
Django Web Development

📌 Basic Installation guide
   
   Create a folder and go to directory


   ☑️ python -m venv env

   ☑️ "for mac user" source ./env/bin/activate  

   ☑️ "for Windows user" source/env/Scripts/activate

   ☑️ pip install django

   ☑️ pip install --upgrade pip

   ☑️ django-admin startproject <folderName> .

   ☑️ "Run server to see if project works" python manage.py runserver

📌  Creating pages 

☑️   python manage.py startapp pages

     🔴 Go to project folder>setting.py and add 'pages.apps.PagesConfig' under INSTALLED_APPS

     🔴 Add urls.py into django folder 