# Tensorflow Playground

## Training Object Detection Model
1. Setup laptop with NVIDIA gpu
2. Install Docker
3. Install NVIDIA driver and Cuda
4. Use tf_docker/dockerfile to create docker image
  - $ docker build -t <image_name> .
5. Run docker container, exposing the GPU
  - $ docker run -it --gpus all --name <container_name> <image_name>
