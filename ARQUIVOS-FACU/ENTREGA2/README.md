
# ✍️ Classificador de Torcidas com IA (Teachable Machine)

## Descrição do Projeto
Este projeto consiste em um motor de classificação visual desenvolvido para diferenciar
torcedores de diferentes times (Corinthianos e São Paulinos) 


📝  O objetivo

principal é explorar as capacidades de reconhecimento de imagem e os desafios de
generalização de modelos de aprendizado de máquina quando aplicados a características
humanas subjetivas 
Desenvolvido como parte da disciplina de Inteligência Artificial (2024.1), o sistema
utiliza a plataforma Teachable Machine para treinar redes neurais com amostras de
imagens reais
O foco da experiência foi analisar como a quantidade de dados e
o ajuste de hiperparâmetros influenciam a precisão da classificação final 
*Figura 1: Dashboard do Teachable Machine mostrando o treinamento das classes
'Corinthiano' e 'São Paulino' com os respectivos outputs de confiança.* 

## 💻 Tecnologias Utilizadas

* **Linguagem:** Interface Visual de Machine Learning (TensorFlow.js) 
* **Bibliotecas:** Teachable Machine Image Model 
* **Ferramentas:** Google Teachable Machine, Google Drive para importação de
datasets 
## Resultados e Aprendizados

O projeto trouxe reflexões importantes sobre os limites da visão computacional em
datasets reduzidos :

* **O modelo demonstrou dificuldade de distinção:** Por mais que as pessoas sejam de
torcidas específicas, a IA apresentou falhas na diferenciação mesmo com o aumento do
treinamento .

* **Limitação de Dados:** O aprendizado foi comprometido pela ausência de um
parâmetro (repertório) amplo de fotos para julgar as imagens adequadamente)

* **Erro de Classificação:** Observou-se a classificação errônea de indivíduos, levando a
resultados que não condizem com a realidade das imagens testadas .
* **Hiperparâmetros utilizados:** O treinamento foi configurado com 100 épocas, um
Batch Size de 16 e uma taxa de aprendizado (Learning Rate) de 0.001 .
## Como Executar
1. Acesse o link do modelo hospedado: https://teachablemachine.withgoogle.com/
models/aesn4ikTs/ .
