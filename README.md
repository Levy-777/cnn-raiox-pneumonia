# Detecção de Pneumonia em Raio-X com CNN

Este projeto utiliza Deep Learning para classificar imagens de raio-X de tórax em duas classes: **Normal** e **Pneumonia**, empregando uma Rede Neural Convolucional (CNN) desenvolvida com TensorFlow/Keras.

## Objetivo

Construir e avaliar um modelo de classificação de imagens médicas capaz de identificar padrões associados à pneumonia em exames de raio-X, utilizando técnicas de pré-processamento e aprendizado profundo.  
Este projeto possui fins educacionais e não deve ser utilizado para diagnóstico clínico real.

## Avaliação

O desempenho do modelo foi avaliado utilizando dados não vistos durante o treinamento.  
As métricas utilizadas incluem:
- Acurácia
- Matriz de Confusão

A matriz de confusão permite analisar a distribuição de acertos e erros entre as classes Normal e Pneumonia, fornecendo uma visão mais detalhada do comportamento do classificador.

## Bibliotecas Utilizadas

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Autores e Contribuições

O desenvolvimento deste algoritmo contou com a colaboração de dois autores:
- **Levy**  
  Responsável pelo desenvolvimento da arquitetura da Rede Neural Convolucional (CNN), treinamento do modelo e definição dos hiperparâmetros.

- **Gabriel**  
  Responsável pela revisão do código, criação das funções de pré-processamento e predição, além da implementação da matriz de confusão para análise do desempenho do modelo.

## Limitações do Projeto

- Possível viés na aquisição das imagens
- O modelo não foi validado clinicamente
- Resultados dependem fortemente da qualidade do pré-processamento
