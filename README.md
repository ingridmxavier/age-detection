# 🚀 Age Detection Project

Este projeto explora técnicas de **Visão Computacional** e **Deep Learning** para estimativa de idade e gênero a partir de imagens, utilizando Python e bibliotecas modernas.

Site: https://ingridmxavier.github.io/age-detection/

## 📸 Uso de Imagens

As imagens utilizadas neste projeto foram **geradas por Inteligência Artificial**, com o objetivo de evitar problemas relacionados a direitos autorais e garantir liberdade de uso e compartilhamento.

Essa abordagem também permitiu criar um conjunto diversificado de rostos para testes e validação do modelo.

---

## 📌 Inspiração

Este trabalho foi inicialmente inspirado no tutorial:

> Age Detection using Deep Learning in OpenCV – GeeksforGeeks  
> https://www.geeksforgeeks.org/computer-vision/age-detection-using-deep-learning-in-opencv/

A partir dessa base, o projeto evoluiu para uma abordagem mais robusta com modelos modernos de deep learning.

---

## 🧠 Evolução do Projeto

Inicialmente, foi implementado o modelo clássico baseado em OpenCV (Caffe), conforme o tutorial. No entanto, observou-se:

- Baixa precisão em diferentes faixas etárias  
- Forte limitação na generalização  
- Erros significativos com rostos jovens  

Diante disso, o projeto foi aprimorado com o uso do:

👉 **InsightFace (modelo buffalo_l)**

---

## ⚙️ Tecnologias Utilizadas

- Python  
- OpenCV  
- InsightFace  
- NumPy  
- Matplotlib  

---

## 🔍 Funcionalidades

✔️ Detecção de rostos  
✔️ Estimativa de idade e gênero  
✔️ Processamento em lote de imagens  
✔️ Geração de imagens com bounding box  
✔️ Criação de vídeo com resultados  

---

## 📊 Resultados

- Boa precisão para adultos e idosos  
- Limitações na detecção de crianças  
- Evidência de **viés de dataset** no modelo  

