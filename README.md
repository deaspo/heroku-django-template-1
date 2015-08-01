# heroku-django-template
A modern and easy-to-use Django project template hosted on Heroku.

Installation Instructions:

1) Simply create a new project by running this command:
```shell
django-admin.py startproject --template=https://github.com/ZIXANLABS/heroku-django-template/archive/master.zip --name=Procfile helloworld
```
2) Go through run.sh in root directory and make appropraite changes.

3) Replace secret key with os.environ['SECRET_KEY'] in project_name/project_name/settings.py

4) Insert CDN URL in settings.py on line 104 replacing REPLACE_THIS_WITH_CLOUD_FRONT_DISTRO.

Any questions, feedback, etc.? Please feel free to drop me a note at zeeshan@zixanlabs.com


## Website using this template:
### Uber Fare Estimator [www.uberfareestimator.co]
### ZIXANLABS [www.zixanlabs.com]
### ZippKode [www.zippkode.com]
