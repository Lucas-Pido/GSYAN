# GSYAN

README – GS IA 4SIS 

Lucas Afonso Pido - RM83736 

Leonardo Brasileiro - RM86233 

Vinicius dos Santos Menten 81967 

 

O projeto foi feito para gerar imagens e mostrar se é uma pessoa saudável ou se ela tem pneumonia. O desenvolvimento é realizado utilizando uma Convolutional Neural Network (CNN) O projeto possui duas partes: o treinamento de um modelo de rede neural usando Keras, e a classificação de uma imagem de entrada usando o modelo treinado. 

 

Dependências do projeto: 

Treinamento do Modelo: 

Python 3 

Bibliotecas Python: os, cv2, numpy, keras 

Keras (deve ser instalado via pip: pip install keras) 

Conjunto de dados contendo imagens Saudáveis e Pneumonia 

Classificação de Imagens: 

Python 3 

Bibliotecas Python: cv2, numpy, keras, serial, matplot 

Modelo Keras treinado (keras_modelo.h5) 

Imagem de entrada para classificação 

Para rodar o projeto: 

	Baixe gsyan.ipynb e faça a sua importação para o colab 

	Baixe as fotos e faça a sua importação para o colab 

Treinamento do Modelo: 

Certifique-se de ter instalado todas as bibliotecas Python necessárias. 

Tenha um conjunto de dados com imagens Saudável e Pneumonia. 

Execute o código 1 para treinar o modelo. Isso gerará um arquivo chamado keras_modelo.h5 após o treinamento. 

Classificação de Imagens: 

Certifique-se de ter as bibliotecas Python necessárias instaladas. 

Carregue o modelo treinado keras_modelo.h5. 

Atualize o caminho da imagem de entrada (image_path) se necessário. 

Execute o código 2 para classificar a imagem de entrada. 

 

 

 

Resultados esperados: 

Espera-se que o modelo classifique com precisão as imagens em "Saudável" e "Pneumonia". O uso de técnicas de aumento de dados visa melhorar a capacidade de generalização, resultando em um modelo ideal para identificação visual de padrões relacionados à saúde nas imagens. Podendo assim ajudar muitos médicos e pacientes a terem um atendimento mais rápido e confiável. 

 

 

 

Link do vídeo: 

https://youtu.be/x97BV8t3WG8 
