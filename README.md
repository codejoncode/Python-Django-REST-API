# Python-Django-REST-API


1. Development Server
   Running code in a virtual dev machine: 
   - Easy to share the server with others 
   - Exact same version of all requirements
   - Run exactly the same software as a real production server
   - Easily create and destroy server as needed
2. Application Code 
   - Using Python to write logic for our application
   - Using Django Web framework for Python (Pre defined set of code to perform common actions)
   - Django REST framework - used for making standard REST API's
3. Tools
   - Using VS Code editor
   - Git used for version control
   -  Mod Header  Chrome extension to easily modify HTTP Headers


#DOCKER VS VAGRANT 

Virtualization technology to isolate the application from the machine its running on.  

What is docker? 

Open source containerization tool run app in light weight image.   Creates a docker file featuring all of the steps needed to build the application. 

Docker limitations  steeper learning curve.  

Vagrant  mange virtual development environments   

Hypervisor (i.e Virtualbox)   
Create a vagrant file that includes all steps to build  development server.  
Steamlined but complex version of Linux OS 
Easier learning curve vs. Docker  Wideer range of support  runs on any machine that supports Virtual Box  
Streamline workflow  All developers use supported OS   Just getting started Need support wider range of OS. 


Will need to install Git, VirtualBox, Vagrant, 

git config --global user.email  " email address"   ---->>>>  sets the email address to use in git bash 
git config --global user.name "name"  ---->>>  sets the name in git bash 

Install VirtualBox  at www.virtualbox.org 

Install Vagrant at https://www.vagrantup.com
Default  Vagrant desitnation C:\HashiCorp\Vagrant\ 

vagrant --version in gitbash to test if it is installed correctly should provide a version type. 

modheader extension for google chrome https://chrome.google.com/webstore/detail/modheader/idgpnmonknjnojddfkpgkljpfnnfcklj/related?hl=en
