# Sistema de Classificação de Fissuras em Imagens Térmicas

  Este é um sistema de identificação de fissuras desenvolvido em Python utilizando OpenCV. 
  O sistema utiliza técnicas de Processamento de Imagem e Machine Learning para identificar a presença de fissuras em uma imagem térmica.

## Funcionalidades Principais
Identificação de Fissuras: O sistema é capaz de analisar imagens térmicas contendo ou não fissuras em estruturas de concreto e classificar de 2 classes: Positive - Imagem com presença de fissuras - e Negative - Imagem sem a presença de fissuras.

Processamento de Imagem: Utilizando OpenCV, o sistema realiza o pré-processamento das imagens, destacando as fissuras e classificando o tipo dentro das 2 classes pré-determinadas.

Modelo de Machine Learning: O sistema utiliza um modelo de Machine Learning treinado previamente para classificação de fissuras. Este modelo foi treinado com uma variedade de imagens térmica de diferentes tipos de fissuras.

## Requisitos de Sistema
- Python 3.x
- OpenCV
- Bibliotecas Python: NumPy, Streamlit, scikit-learn, etc. (detalhes podem ser encontrados no arquivo requirements.txt)
