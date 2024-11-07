## Demo 1
The 'demo1' folder contains two files:
- **hello_world.py**: prints "Hello World!" to the console
- **Dockerfile**: a plain-text file with the instructions to create the Docker image
  - This file _must_ be named "Dockerfile" for the Docker engine to recognize it

### Running this demo
1. Clone this repository onto your local machine
2. Start the Docker daemon, either by opening Docker Desktop or through the terminal
3. Navigate to the 'demo1' folder
4. Write ```docker build -t <image_name> .``` in your terminal and execute to create the image (you _must_ do this in the same directory that contains the Dockerfile)
5. Write ```docker run <image_name>``` in your terminal and execute to start and run the container
6. Observe the output in your terminal!

## Demo 2
The 'demo2' folder contains two files:
- **flask_example.py**:
- **Dockerfile**: a plain-text file with the instructions to create the Docker image

### Running this demo
1. Clone this repository (if you haven't already followed the first demo)
2. Start the Docker daemon
3. Navigate to the 'demo2' folder
4. Write ```docker build -t <image_name> .``` in your terminal to create the image (again, from _within_ the 'demo2' directory where the relevant Dockerfile is stored)
5. Write ```docker run -p 8088:3000 <image_name>``` in your terminal to start and run the container (include the ```-d``` tag in this command to have the container run in the background instead of hogging your terminal)
6. Open a web-browser and navigate to http://localhost:8088 to observe the application output!
