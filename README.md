# Dev-ops-project-collection
Number of dev-ops projects i took as a challenge from https://www.tutorialworks.com/devops-project-ideas/
##

I found this collection of projects and wanted to challenge my self incrementally on my learning journey.
Along my learning path i would like this to be a guide for others, so that i can help people learning Dev-Ops 
and add aditional challenge for me personally to write better guides. 

## Project one.

# Main goal is to build a server that will be hosting a website in private enviroment.
##
Restrictions on the project is that it needs to be done completly programaticaly.
So infrastrucuture, initial website deployment, premissions and the rest will need to be achieved in automated way.
With the ability to repeat the same process with a single or collection of scripts.


### ✅  Step-by-step Instructions
Download the project to your local machine and open it in VSCode, PowerShell or some other IDE.
Open a terminal in VSCode
<hr>
Start by running the following commands

```
"Vagrant init" 
```
to initialise the provisioning of virtual machines.

![start](https://user-images.githubusercontent.com/36207533/135726881-415e8db7-8b0f-41bb-bb85-dbd56db59712.png)

```
"Vagrant up"
```
to start your machine
##
Once your server is up it will invoke the call to our shell script called severscript.sh
![script](https://user-images.githubusercontent.com/36207533/135726886-2fbb63c6-476d-4bf6-aa36-bd64274e0d5d.png)

You will be able to see the output of the script in the powershell window.

After the provisioning of the server and script nginx will be installed and you can check the validity of it by opening another powershell and running 

```curl <ip of the server>
```
##
Or alternatively opening your browser and entering the server ip.
##
![nginxcurl](https://user-images.githubusercontent.com/36207533/135726887-b3763b5b-0334-4eb6-98f6-5cda3dc5a57d.png)
![nginxhome](https://user-images.githubusercontent.com/36207533/135726890-ceb2b4d8-6398-4982-a0d6-62c6ac5ff377.png)



