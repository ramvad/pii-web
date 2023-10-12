# pii-web
  enabling fast api based web for pii project

Execute The following steps on your laptop

1. check out the project from github to a local dir
C:\Users\svgks>cd C:\Users\svgks\IdeaProjects\pii-web
2.open a windows command prompt
3. create a venv and activate it

 C:\Users\svgks\IdeaProjects\pii-web>C:\Users\svgks\pii-web-venv\Scripts\activate.bat

4. pip install requirements file

   (pii-web-venv) C:\Users\svgks\IdeaProjects\pii-web>pip install -r requirements.txt 
5. run fast api based app using uvicorn
   (pii-web-venv) C:\Users\svgks\IdeaProjects\pii-web>uvicorn simple-app:app --reload

6. from Postman or command line, run a request against app

7. ![image](https://github.com/ramvad/pii-web/assets/121734235/0283fae8-8a7a-45b3-8cf1-73d0b79bf359)
