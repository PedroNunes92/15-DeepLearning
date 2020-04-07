## Introducao a DeepLearning

#### Container para desenvolvimento

* Keras
* Tensorflow 2.1
* Suporte a CPU e GPU

sudo docker run --gpus all -v /home/silvio/git:/tf -p 8888:8888 --user $(id -u):$(id -g) silviostanzani/tensorflow:nightly-gpu-py3-jupyter

* (--gpus all) Define que a execução será feita submetendo para GPU
* (-v) Mapeia diretório git para o file system do conteiner
* (--user $(id -u):$(id -g)) Usuário local do conteiner é o usuário corrente iniciando o conteiner
* (-p 8888:8888) Mapeia porta 8888 interna para porta 8888 do host


#### Container para treino

* Script para treino do modelo
* Salva métricas de desempenho, tempo de execução e pesos gerados
