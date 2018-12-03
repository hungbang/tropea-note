# tropea-note

##  About heroku server 
I provide you accdess for Heroku (https://dashboard.heroku.com/apps/tranquil-taiga-65093) and for trello.
Please don't change any heroku configurations :-)

Also you link the heroku repository as remote to your local branch
https://git.heroku.com/tranquil-taiga-65093.git

Heroku is configured to do a re-deploy after every push.

For now I do that:
1 I/you can commit multiple time in local branch until the task is done.
2 Push on bitbucket repository (bitbucked  branch is mapped as origin/master) for code review.
3. After code review I can push your changes to heroku for testing. If there are some fast requirements for testing  you can push yourself on heroku. 
4. Update heroku database (execute new scripts)

Usualy the heroku server will sleep if there is no activities, after first acces on site it wil do a tomcat start + deploy, so if it don't work try again after 30 secounds - 1 minute


==============

I provide you accdess for Heroku ( https://dashboard.heroku.com/apps/tranquil-taiga-65093 ) and for trello.
Please don't change any heroku configurations  :-)
 
Also you link the heroku repository as remote to your local branch
 https://git.heroku.com/tranquil-taiga-65093.git 

Heroku is configured to do a re-deploy after every push.

For now I do that:
1 I/you can commit multiple time in local branch until the task is done.
2 Push on bitbucket repository (bitbucked  branch is mapped as origin/master) for code review.
3. After code review I can push your changes to heroku for testing. If there are some fast requirements for testing  you can push yourself on heroku. 
4. Update heroku database (execute new scripts)

Usualy the heroku server will sleep if there is no activities, after first acces on site it wil do a tomcat start + deploy, so if it don't work try again after 30 secounds - 1 minute
