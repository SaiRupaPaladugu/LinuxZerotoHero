# LinuxZerotoHero

Basic commands

Shell scripting efficiency :

write **echo** on each statement    
write **set -x** to know which command is being executed  
If you don't want to know the users to see the commands u wrote comment out set -xe  

ps -ef (process show entire details in format)  
ps -ef | grep amazon  
ps -ef | grep amazon | aws -F" " '{print $2}'

curl <URL>  
curl <URL> | grep ERROR 
wget downloads the file - curl directly gets infor  . If we don't want to store in local use curl
find / 
sudo su - (Change to root)  
loops  
find   sudo find / -name <name of file>
trap 
sed  replace text in files

**tips:**
sh <scriptname>  (to execute)  
dir exists -d ( initial slash need to be removed from path )  
file exists -f
-e can be used for either dir or file  
if loop comparison use -lt
:set number in vi editor to see the line numbers  
shellcheck is useful in finding out syntax related issues.  


