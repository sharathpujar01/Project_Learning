This project contains  the content management system for the elearning platfrom.
Required installations:
1)Install Django in your virtual environment:
pip install Django==2.0.5
2)install Pillow for image uploads with following command:
pip install Pillow==5.1.0
3)Install django-braces :
pip install django-braces==1.13.0
4)To embed video use command :
pip install django-embed-video==1.1.2
5)Download memcached from https://memcached.org/downloads
then, install its python bindings:
pip install python-memcached==1.59
Install third-party package django-memcache-status:
pip install django-memcache-status==1.3


please uncomment the 'memcache_status' in settings.py file in educa

Then make migrations and run the application
