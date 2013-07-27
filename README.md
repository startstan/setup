setup.git
=========

TODO:
---------
1. Add steps to setup github account (git config username and user email), in the setup scipt
2. Add steps to setup ssh keys for github on a new instance
3. Add steps to setup ssh keys for heroku on a new instance
 
Setup instructions:
---------
Forked and modified setup.sh to include Heroku command line tool installation
Clone and run this on a new EC2 instance running Ubuntu 12.04.2 LTS to
configure both the machine and your individual development environment as
follows:

```sh
cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/startstan/setup.git
./setup/setup.sh   
```

Note: You need to log out and log back in to the Linux box for all the setup changes to take effect.

See also http://github.com/startstan/dotfiles and
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.





