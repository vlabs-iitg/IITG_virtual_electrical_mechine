1.Download the repo from GitHub. The repository contains the following structure as described below.
  a) README.md: This file contains a brief description about all the folders present inside the repository. 
  b) build: Initially this is an empty folder. But after writing the 'makefile' in the 'src' folder, all the contents of the lab will be copied here.
  c) scripts: This folder contains the following files
    i) dependencies: This folder contains all the dependencies required for Virtual Lab to run.
    ii) initialize.sh: The initialize.sh script creates the initial environment for the required lab by installing the server side dependencies for the lab and invokes the build script.It mention all the server-side dependencies of the lab in dependencies.txt. We have the following shell scripts for different environments- initialize ubuntu.sh,initialize fedora.sh, initialize centos.sh, initialize windows.bat.
    iii) labspec.json (will be added later) : It has the build requirements, lab description, runtime environments for the required lab.
  d) src: This folder contains all the sources of the particular lab. It also has a 'makefile' which will copy the lab source contents to the 'build' folder.
