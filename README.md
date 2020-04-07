## Introducao-DeepLearning

### Container para execução: 

sudo docker run --gpus all -v /home/silvio/git:/tf -p 8888:8888 --user $(id -u):$(id -g)  silviostanzani/tensorflow:nightly-gpu-py3-jupyter

* Define que a execução será feita submetendo para gPU
* Mapeia diretório git para o file system do conteiner
* Usuário local do conteiner é o usuário corrente iniciando o conteiner
