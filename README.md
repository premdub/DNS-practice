# DNS-practice
HHA504_assignment 8  

1.  A new github repo called 'DNS practice'

   

2. Create a markdown/readme file that contains the following information: 
     -The name of your purchased domain :  
     
      premdub.tech
      

     -A copy of the 'A' record settings that you needed to write (name, value, TTL) :
     
      Host name: left blank or type @
      
      Value: 34.70.144.72
      
      TTL: 7200
      

      -The cloud vendor you selected:  
      GCP  
      
      
      
  -Brief instructions if re-recreate app needed:
  
  Create own VM and copy the IP address
  Create own domain name ( file name.tech)
  Under "manage orders" - "list/search orders', find domain name and click on it
  Go to "DNS Management' and click "Manage DNS"
  Under "A Records", click "Add A Record"
  Put VM IP address under "Value"
  Set Own TLI (minimum 7200)
  Return to VM terminal and connect to git repo
  Locate he flask app file and connect to it
  
  
  Commands used in VM (GCP) terminal:
  
  Sudo apt-get update
  sudo apt install python3-pip
  sudo apt install python3-flask
  git clone "git repo link"
  sudo python3 "file_name.py"
  to update py file, use command---> "nano file_name.py"
  Go back to the website (**.tech)

  
