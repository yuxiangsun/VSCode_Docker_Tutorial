## Tutorial for using VSCode with Docker for Deep Learning Research

### This tutorial takes [RTFNet](https://github.com/yuxiangsun/RTFNet) as an example. We assume that you have successfully built the RTFNet docker image `docker_image_rtfnet`.

### Step-1: Open VSCode and click File->New Window->Open Folder to open the RTFNet folder on your computer. Then, click the Extensions. Serch and install extensions `Docker`, `Docker Compose` and `Remote-Containers`.

<img src="Steps/Step_01.png" width="1280px"/>
<img src="Steps/Step_02.png" width="1280px"/>

### Step-2: Click the left bottom square button, then follow the below figures.

<img src="Steps/Step_03.png" width="1280px"/>
<img src="Steps/Step_04.png" width="1280px"/>
<img src="Steps/Step_05.png" width="1280px"/>

### Step-3: Overwirte the `devcontainer.json` and `docker-compose.yml` files using the ones given in this repo. Then delete the `Dockerfile`, because you have already built the docker image using a Dockerfile. You may need to add the volumn mapping to let docker container to access some folder in your local computer. Please also modify the devices list according to the number of your GPU cards.

<img src="Steps/Step_06.png" width="1280px"/>
<img src="Steps/Step_07.png" width="1280px"/>
<img src="Steps/Step_08.png" width="1280px"/>

### Step-4: Click the left bottom square button again, then follow the below figures to reopen the project in a docker container that will be built by VSCode automatically.

<img src="Steps/Step_09.png" width="1280px"/>

### Step-5: Finally, install the `Pylance` and `Python` extensions. The extensions will be installed in this container. If you do not install the two extensions, you may not be able to use code auto-completion, highlighting, etc.

<img src="Steps/Step_10.png" width="1280px"/>

### Please feel free to contact me if you have any problems. 

sun.yuxiang@outlook.com, https://yuxiangsun.github.io/
