Download the repo from GitHub. The repository contains the following structure as described below.
  a) README.md: This file contains a brief description about all the folders present inside the repository.
  b) build: Initially this is an empty folder. But after executing the 'makefile' in the 'src' folder, all the contents of the lab will be copied here.
  c) scripts: This folder contains the following files
    i) dependencies: This folder contains all the dependencies required for Virtual Lab to run.
    ii) initialize.sh: The initialize.sh script provides options to install the lab as a Server or Client.
    iii) initialize-server.sh: The initialize-server.sh script creates the initial environment for the required lab by installing the server side dependencies for the lab and invokes the build script.
    iv) initialize-client.sh: The initialize-client.sh script creates the initial environment for accessing the lab runnning in the server.
  d) src: This folder contains all the sources of the particular lab. It also has a 'makefile' which will copy the lab source contents to the 'build' folder.
 
Steps to be followed to install the lab:
1. Download the lab source zip file from GitHub.
2. Extract the lab source zip file.
3. Goto the scripts folder and run the initialize.sh script.
4. Follow the on-screen instructions to install/run the lab.
