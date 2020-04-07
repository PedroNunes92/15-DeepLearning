## Introducao-DeepLearning

### Container para execução: 

sudo docker run --gpus all -v /home/silvio/git:/tf -p 8888:8888 --user $(id -u):$(id -g)  silviostanzani/tensorflow:nightly-gpu-py3-jupyter
