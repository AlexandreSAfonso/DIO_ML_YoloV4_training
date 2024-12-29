# Usar a Rede Yolo V4 para deteção de objetos em imagens.

## Esse Colab, demonstra o passo a passo para utilizar a rede Yolo para detectar objetos em imagens.

Foram utilizados a rede Yolo V4, as imagens de exemplo do conjunto de dados da COCO



## Utilizando suas Próprias Imagens e Gerando Labels
Se você quiser usar suas próprias imagens em vez de um dataset como o COCO, siga estes passos simples:

Organize suas imagens em uma pasta no seu Google Drive ou diretamente no Colab.

Use ferramentas como LabelImg ou LabelMe ou outro para criar rótulos para suas imagens.

LabelMe:

1. Acesse a versão online ou instale o LabelMe.
2. Carregue suas imagens.
3. Rotule os objetos.
4. Exporte os rótulos no formato YOLO.

Cada arquivo de rótulo deve estar no mesmo diretório que as imagens.

Algumas Bibliotecas Utilizadas no Tutorial
- Darknet
  Descrição: Framework de código aberto escrito em C e CUDA para deep learning.
  Uso: Clonado e compilado para executar o modelo YOLOv4 para detecção de objetos.

- cv2 (OpenCV)
  Descrição: Biblioteca de visão computacional de código aberto.
  Uso: Utilizada para carregar e manipular imagens.

- matplotlib
  Descrição: Biblioteca de plotagem 2D em Python.
  Uso: Utilizada para exibir as imagens com as detecções realizadas pelo YOLOv4.
