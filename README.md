## Pico Container C
### Template to develop in C/C++ with a Raspberry Pi Pico and using Docker and Visual Studio Code 

#### Problem:
Setting up the enviroment to develop in C/C++ for the Pico can be a hassle. Rather than installing and setting up your environment each time, I wanted to have a development environment that was ready to go  is to solve the problem of having to download serveral programs and set up the different SDK to develop in C/C++ with a Raspberry Pi Pico.

#### Pre-requisites:  
* Docker installed  
* Visual Studio Code Installed
* Dev Containers Extension installed


#### How to use:

1. Change to a directory where you want to create your new project  
`cd ~/Documents` 
 
2. Clone this repository  
    `git clone https://github.com/jrsola/pico-container-c`
  
3. Change the directory name into your own  
 `mv pico-container-c <my_project>`

4. Enter the directory and remove the previous .git information  
`cd <my_project>`   
`rm -rf .git`

5. Open the directory in Visual Studio Code and Open in container.