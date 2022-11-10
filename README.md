# DNS-practice
HHA504_assignment8
1. Please create a new github repo called 'DNS practice' 

2. Inside the repo, please create a simple flask app (can be your PssP or something else, I have no preference) - this flask app should then be deployed on a VM in either GCP or Azure 

3. Register a domain name using .TECH (be sure to have your github student account linked so it is FREE) - or if you have already purchased domains in the past and use something like godaddy, that is also fine [https://get.tech/github-student-developer-pack] 

4. Create a A record that links together the domain with the IP address of your flask app deployed on either GCP or Azure 

5. Create a markdown/readme file that contains the following information: 
-The name of your purchased domain :  
premdub.tech

-A copy of the 'A' record settings that you needed to write (name, value, TTL) :
Host name: left blank or type @
Value: 34.70.144.72
TTL: 7200

-The cloud vendor you selected:
GCP

-Brief instructions if re-recreate app needed:

Create own vm and get the IP address ready
Create own domain name (e.g. XXX.tech)
Under 'Manage Orders' - 'List/Search orders', find domain name and click on it
Go to 'DNS Management' and click 'Manage DNS'
Under 'A Records', click 'Add A Record'
Put vm IP address under 'Value'
Set own TTL (min is 7200)
Go back to vm terminal and connect to git repo
Locate the flask app file and connect to it

Commands used in vm (GCP) terminal :

sudo apt-get update
sudo apt install python3-pip
Sudo apt install python3-flask
git clone git-repo-link
sudo python3 file_name.py
to update py file with command---> nano file_name.py
Go back to the website  *.tech   




