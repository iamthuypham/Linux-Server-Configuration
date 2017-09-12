# Linux Server Configuration
Linux Server Configuration is a backend web project from Udacity Full Stack Nanodegree

## Info
1. IP Address: 34.228.15.203
2. SSH Port: `2200`
3. Web URL: 
- http://ec2-34-228-15-203.compute-1.amazonaws.com/catalogs/
- http://34.228.15.203/catalogs/

## Installed and Configured Software
- Git Bash
- Apache2
- mod_wsgi
- virtualenv
- Flask
- psycopg2
- httplib2
- SQLAlchemy

## Getting Started
1. Download or `git clone` this project
2. Open Git Bash
3. Navigate to directory of the `grader_key` file
4. Log in by typing this command line with `XX.XXX.XXX.XXX` is the IP Address
```
ssh grader@XX.XXX.XXX.XXX -p 2200 -i grader_key
```
5. Enter passphrase: **udacity**. 

As success:
![Image of success ssh login](https://github.com/iamthuypham/Linux-Server-Configuration/blob/master/successssh.PNG)

## Explore
1. Firewall: `sudo ufw status`
2. Timezone: `date`
3. Database
- Connect to database: `psql -R grader catalog`
- View all database: `\l`
- View all roles and permission: `\du`
- Quit current view: `Q` key
- Quit postgres: `\q`

