# BitPass - Password Manager Web App (Development)
BitPass is a web based Password Manager. User can use it to save different account password so that they don't need to remember each and every complex password, just remember one password and access every other password, since it's a web app it can be accessed from any device which can connect to the internet and has a display😉.

# How to setup in your PC
User has two options: - Either use global environment for the packages or use virtual environment.\

**For Virtual Environment:-**\
**Step-1**: Install virtualenv - Type "pip install virtualenv" (Without Quotation) in terminal\
**Step-2**: Go to the project folder and type "virtualenv env"\
**Step-3**: For windows user only (PowerShell Only) - Type "Set-ExecutionPolicy Unrestricted -Scope Process"\
**Step-4**: Type "env/scripts/activate"\
**Step-5**: Type "pip install django"\
**Step-6**: Type "pip install cryptography"\
**Step-7**: Type "python manage.py migrate"\
**Step-7**: Type "python manage.py runserver"


**For Global Environment:-**\
Ignore from **Step-1** to **Step-4** rest all the steps are same as **Virtual Environment**
