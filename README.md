
# THIS REPOSITORY HAS MOVED

New URL: https://git.goyman.com/kuon/ansible-capistrano-app

Why I moved everything out of GitHub:

https://github.com/kuon/WhyILeftGithub/blob/main/README.md

----

Capistrano app
==============

Prepare the directory structure for a ruby deployed via capistrano on a centos host.



Requirements
------------

none

Role Variables
--------------

- `deploy_user` - The name of the user that will be used to deploy the app using capistrano, usually a privileged user
- `app_user` - The name of the user running the app, will be created as an unprivileged user.
- `deploy_path` - The path to deploy the app to.
- `app_services` - The "services" of the app.


Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: kuon.capistrano-app }

License
-------

MIT
