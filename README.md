# pacakage-managment

1) Creating a record of all the assests used by comapany

we need analyse all the assests like servers , oprating system , networing protocols , pacakages used in server , applications and check if they are updated to the latest version according to there vendors.
for ex : To check if ubuntu server and pacakages in it are upto date you need to run following commands

sudo apt update
This will make sure that system is aware of any updated  configuration or newly installed pacakages and 

sudo apt upgrade
This will check all the pacakages and there latest versions from cloud and install all of them .

First we should make sure that all the system is updated to latest version

2) Do a vulnerability analysis

Here we will check all the known vulnerabilities associated with our system this can be unauthorized access to server or database server or attacks like sql injection , Ddos attacks and many more
To deal with this critical situation we need to priortize all the vulnerabilities accoeding to it's risk.(low , medium , high)

But first I suggest anyone to use tools like Apparmor or SElinux which makes sure that every pacakge or software has the least permissons assigned to them so if someone gets access to this pacakages there would be less threat.

3) Check availability of patches 

we need to make sure that all the vulnerabilities that we have listed have patches for them but it's not neccessary the the vendor has released the patch for a specific vulnerability so we can also see if there's any unofficial patch out there made by some opensource or other community/orgnization

If there's no patch available we need to somehow fix the vulnerability by changing or limiting some functionality which totatlly depends on the project


4) Deploying patches in testing enviorment

All patches will be first tested in a Home lab or mirror lab so that we can make sure
. Everything is compatible and working no break of functionality
. Vulnerability is fixed 
. Our system is not vulnerable to any top security attacks 
. There is no compability issue between hardware and software

5) Make a report 

Configuration managment is neccessary to understand what patches we have done and all the tests taken in test enviorment so if there's any problem you can refer it


6) Deploy the patches and good maintainace

Once you have tested everything you will deploy all the patches officially to all the servers over 200 locations and make sure everything is maintained and updated properly.
At last make sure you have a full report on what patches you have and how you installed them and all behavior in test lab




