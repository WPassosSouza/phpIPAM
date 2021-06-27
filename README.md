# phpIPAM


phpIPAM can be obtained from following sources:
1.) Stable releases

Latest official phpIPAM installation files can be obtaned from following sources:

    GitHub repository
    Sourceforge download

Easiest way to obtain files is to simply clone GitHub GIT repo:

[root@ipam /]# GIT clone https://github.com/phpipam/phpipam.git /var/www/phpipam/
[root@ipam /var/www]# cd /var/www/phpipam
[root@ipam /var/www/phpipam]# git checkout 1.4

This will download current code to phpipam directory in /var/www/. We also need to install submodules, to do so issue

[root@ipam /var/www/phpipam]# git submodule update --init --recursive

2.) Development releases

If you are comfortable using development release of phpipam, along with submitting feedback and filing bug report for development releases you can use either github or download latest release from sorceforge directly. Prefered method is using github, as it is easier to pull new updates from server.

Development releases are hosted on GitHub only. From release 1.2 onwards development SVN repository will not be used anymore, so please switch to GitHub.

    phpipam GitHub page


Simply clone GitHub repo to local directory on server:

[root@ipam /]# GIT clone https://github.com/phpipam/phpipam.git /var/www/phpipam
[root@ipam /var/www/phpipam]# git submodule update --init --recursive
