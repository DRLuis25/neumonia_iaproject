# Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com)

Este repositorio se puede utilizar como punto de partida para implementar modelos [fast.ai] (https://github.com/fastai/fastai) en Render.

Puede probar sus cambios localmente instalando Docker y usando los siguientes comandos:

```
docker build -t fastai-v3 . 
docker run --rm -it -p 5000:5000 fastai-v3

```