** Update

2011/07/12 Add a local_environment.json.


** Quick Start

First step:

    dotcloud create your-app-name
    git clone git://github.com/ukyo/dotcloud-django.git your-dotcloud-project
    cd your-dotcloud-project
    dotcloud push your-app-name
    dotcloud run your-app-name.www python current/mysite/manage.py syncdb

Second step:

Edit local_environment.json.


If you change or add files:

    git add .
    git commit -m 'message'
    dotcloud push your-app-name


