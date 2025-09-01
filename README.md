# 🐾 Khalil-Ravikson - Redes Neurais para Classificação de Gatos e Cachorros

Este projeto tem como objetivo treinar uma **Rede Neural Convolucional (CNN)** para classificar imagens entre **gatos** e **cachorros**.  
Foram realizados dois experimentos principais:  
1. Uma CNN desenvolvida do zero.  
2. Uma CNN utilizando **transfer learning** com a arquitetura **VGG16**.  

---

## 🚀 Tecnologias Utilizadas
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Google Colab** (ou ambiente local configurado)

---

## 📂 Estrutura do Projeto
├── dataset/ # Conjunto de imagens de treino e teste
├── models/ # Modelos treinados (H5, Keras SavedModel)
├── notebooks/ # Jupyter/Colab notebooks de treinamento
├── results/ # Gráficos de perda e acurácia
└── README.md # Documentação do projeto


---

## 🔬 Experimentos

### 1️⃣ CNN do Zero
- Camadas convolucionais + pooling
- Função de ativação: **ReLU**
- Camadas densas para classificação final
- Otimizador: **Adam**
- Resultado: **~70% de acurácia**

### 2️⃣ CNN com VGG16 (Transfer Learning)
- Modelo **pré-treinado no ImageNet**
- Camadas iniciais congeladas
- Fine-tuning nas camadas finais
- Otimizador: **Adam**
- Resultado: **acurácia próxima ou superior a 70%**

---

## 📊 Resultados Obtidos
- A CNN simples alcançou aproximadamente **70% de acurácia**.  
- Com o uso do **VGG16**, os resultados foram consistentes, mostrando o ganho do **transfer learning** em relação ao modelo construído do zero.  

*(Inserir aqui gráficos de treinamento, perda e acurácia para cada modelo caso tenha salvo.)*

---

## 📌 Conclusão
- Redes neurais convolucionais são eficazes para classificação de imagens.  
- Mesmo uma arquitetura simples já consegue bons resultados (~70%).  
- O **VGG16** mostrou-se vantajoso em termos de estabilidade e desempenho, aproveitando o conhecimento prévio adquirido em grandes datasets.  

---

## 👨‍💻 Autor
Projeto desenvolvido por **Khalil Ravikson**  
Estudante de **Engenharia da Computação - UEMA**  
