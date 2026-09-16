# Yu-Gi-Oh-Card-Classifier

Projeto de classificação de cartas de Yu-Gi-Oh! Utilizando uma rede neural convolucional (CNN) desenvolvida em PyTorch. O modelo foi treinado para identificar os principais tipos de cartas que o jogo possui.

# Tecnologias utilizadas

```
Python
PyTorch
TorchVision
Google Colab
Matplotlib
Google Drive
```

# Tipos de Cards

```
Normal
Efeito
Magia
Armadilha
Sincro
Ritual
Link
Fusão
XYZ
```
# DataSet
DataSet criado manualmente para o projeto. Consiste em 10 classes, com 10 imagens cada (Pode aumentar), sendo 9 para os tipos de carta, e um apenas para classificar se a imagem enviada para o modelo não é uma carta.

```
100 imagens
10 categorias
Divisão: 80% treinamento e 20% validação
```

# Modelo
CNN desenvolvida manualmente, em PyTorch.

## Treinamento do modelo

```
Optmizer: Adam
Loss: CrossEntropyLoss
Learning rate: 0.001
Batch size: 32
Epochs: 10
```

# Resultados

100% de assertividade no conjunto de VALIDAÇÃO

# Próximos passos

```
Melhorar o DataSet
Aprimorar o Data Argumentation
Aprimorar testes com fotos de cartas não digitalizadas
