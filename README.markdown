# RailsCollab
## What is it?

RailsCollab is a free web based Project Management and Collaboration tool largely inspired by [Basecamp] [1], 
the communication-oriented project management solution from 37signals. 

Its roots come from a similar project called ProjectPier (previously known as ActiveCollab), 
which instead of Ruby is written in PHP.

## Manage projects. How?

In RailsCollab, you have the following:

* *Task lists* - to keep track of what needs to get done, and who is responsible
* *Milestones* - to track what needs to get done and by whom
* *Times* - to record how much time has been spent on a project or task
* *Files* - to share data with your clients
* *Messages* - for centralized communication

You can add clients to your projects at any time. Each member of a client can have a login, 
whose access can be restricted to certain elements of the project.

## How can i install / upgrade?

Simply run the following:

    script/setup

And login using the username `admin`, with the password `password`.

For more advanced setup options, refer to the [INSTALL.markdown] [3] and [UPGRADE.markdown] [4] files

## I do i do [x]?

Check out the [wiki on github] [2].

## Are there any screenshots or is there even a demo?

Please refer to the project entry on [OpenSourceRails] [5] for any screenshots or demos.

## Can I run RailsCollab on Heroku?

Yes you can! And this is how:

1. Run setup script

    script/setup

2. Setup heroku app

    heroku create

3. Push database onto heroku

    heroku db:push

4. Push config onto heroku

    rake heroku:config --app [heroku app name]

5. Launch in browser

    heroku open

## Licensing

For licensing details, refer to the [LICENSE] [6] file in the root directory.

[1]: http://www.basecamphq.com
[2]: http://wiki.github.com/jamesu/railscollab
[3]: INSTALL.markdown
[4]: UPGRADE.markdown
[5]: http://www.opensourcerails.com/projects/111-RailsCollab
[6]: LICENSE
