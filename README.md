# Docker on C++

In this repository I used C++ to apply a simple code which gets the base (float number) and the power (integer number) and calculates the result. The advise in this repository is using Dockerfile to run this code on any machine which has Docker installed, even if your machine doesn't have C++ compiler.

 ## tutorial
 1. first run up the Docker in your machine and extract the rar file "cpp_power_image_making.rar".
 2. then change the direction to the folder by powershell or command prompt:
    ```console
    cd path\you\extract\cpp_power_image_making
    ```
 4. then make an image of the code in the src by powershell commands:
    ```console
    docker build . -t <your_favorite_image_name>
    ```
 5. then make a container of that image:
    ```console
    docker run -it <your_favorite_image_name>
    ```
 6. after that you can insert the base and the power which you want to see their calculation.
    
  **** please change the ```path\you\extract\cpp_power_image_making``` with the path you extract in your machine. Eg. C:\User\Asus\Downloads\cpp_power_image_making
  
  **** please delete ```<>``` in the fourth and fifth command and replace the content in ```<>``` with your favorite image name.
