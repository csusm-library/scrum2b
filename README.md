SUMMARY
-------

**Scrum2B** is a plugin for Redmine (www.redmine.org) that offers pre-project Scrum Boards and other features aimed at teams wanting to use Scrum for agile project development.
Scrum2B is developed by Scrum2B Team.

***Contacts:***
- Email: *scrum2b@ithanoi.com*
- Website: *www.scrum2b.com*
- Facebook: *www.facebook.com/ScrumToBe*


**The first version (1.0) is quite simple and includes 3 main features:**

1. The ScrumBoard: derived from on another Redmine plugin, ours includes expanded functionality and allows teams to use it like a REAL BOARD.
An awesome new feature is drag and drop sorting for task organization within a Sprint.
2. The ListBoard: lists all issues based on the sort within a project ScrumBoard. The ListBoard streamlines issue tracking in Redmine projects.
3. Interface is based on Twitter Bootstrap, offering a better look and feeling.
(You should get the theme: https://github.com/scrum2b/redmine-scrum2b-theme to install in Redmine)

**You could see the demo version at:**
- *http://scrum2b.com/projects/scrum2b-demo*
- *http://scrum2b.com/scrum2b/board?project_id=scrum2b-demo*

(Please login with username/password: **demo/demo123** to get more detail how Scrum2B works)

*We are focused on making it easier to integrate Scrum in project management. 
If you have ideas on improving the tools we've developed, please do not hesitage to email me at scrum2b@ithanoi.com, 
Or create a Pull request (https://github.com/scrum2b/scrum2b/pulls) to us.*


LICENSE
-------

Scrum2B is open source and released under the terms of the GNU General Public License v2 (GPL)  (http://www.gnu.org/licenses/old-licenses/gpl-2.0.html)


INSTALLATION
------------

This plugin is compatible with Redmine 2.3.x, 2.2.x, 2.1.x, 2.0.x.

Go to the Redmine plugin folder. Clone the plugin from GitHub:
    
    $ git clone https://github.com/scrum2b/scrum2b.git
    $ 

Go back to the Redmine folder, update your bundle and migrate the database:

    $ bundle install
    $ rake redmine:plugins:migrate RAILS_ENV=production
    

Restart Redmine

Go to the plugin configuration page and map the each issue status to applicable Scrum New/In progress/Complete/Closed:

    http://localhost:3000/settings/plugin/scrum2b 



FOR DEVELOPERS
--------------

Change to use "develop" branch for developers:

    $ git checkout -b develop origin/develop

Commit codes
  
    $ git fetch --all
    $ git merge origin/develop
    $ git commit -m "Message Content in here"
    $ git push -u origin develop


FOR FUTURE RELEASES
--------------------

We want to implement new features in short term:

1. Burndown chart based on Estimate Time and Spent Time.
2. The check list for each issues.

If you have any comment/sugguession, please send message to us via Git Issues.

Thanks and best regards,
Scrum2B Team


