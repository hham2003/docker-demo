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
