# SIN 393 – Introdução à Visão Computacional (Projeto 2)

Este repositório contém o projeto desenvolvido na disciplina **SIN 393 - Introdução à Visão Computacional**, como parte dos estudos de técnicas de processamento de imagens e aprendizado de máquina.

---

## Estrutura do Repositório

- **`Code.ipynb`**: Notebook Jupyter com o código do projeto, incluindo a implementação das técnicas utilizadas, pré-processamento dos dados e análise de resultados.
- **`README.md`**: Este arquivo, contendo informações detalhadas sobre o repositório.
- **`Artigo - Projeto 2.pdf`**: Artigo gerado de acordo com a execução do código do projeto.
- **`Resultados`**: Pasta contendo os resultados gerados de cada modelo utilizado.

---

## Apresentação do Projeto

Um vídeo explicativo foi gravado para apresentar os principais resultados e metodologias do projeto. Ele pode ser acessado pelo seguinte link:

- **[Apresentação do Projeto](https://www.youtube.com/watch?v=YHQ6fi3SFdQ)**
---

## Objetivo do Projeto

O objetivo geral deste trabalho é desenvolver um projeto completo de classificação de imagens utilizando Redes Neurais Convolucionais (CNNs), abrangendo experimentação, análise de resultados, documentação e apresentação.

O trabalho busca aplicar conceitos de visão computacional e aprendizado de máquina para resolver um problema de classificação de imagens, utilizando frameworks como PyTorch, com foco na prática de implementação, avaliação de modelos e apresentação dos resultados em formato técnico.

---

## Tecnologias e Bibliotecas Utilizadas

- **Linguagem**: Python
- **Bibliotecas**:
  - Torch
  - Torchvision
  - Torchaudio
  - Scikit-learn
  - Scikit-image
  - Matplotlib
  - NumPy
  - Pillow
  - EfficientNet-PyTorch

---

## Modelos Utilizados
- **ResNet50**: Modelo robusto e amplamente utilizado em tarefas de classificação de imagens.
- **EfficientNet**: Modelo eficiente em termos de recursos computacionais e alto desempenho em benchmarks.
- **AlexNet**: Modelo pioneiro em redes neurais convolucionais, conhecido por sua simplicidade e eficiência em tarefas de classificação.

---

## Etapas do Projeto

1. **Escolha do Dataset**: Foi selecionado um dataset adequado ao problema de classificação (Kaggle ou outra fonte).
2. **Setup Experimental**: Configuração do ambiente e implementação de dois modelos CNN utilizando PyTorch.
3. **Treinamento e Avaliação**: Treinamento dos modelos com validação cruzada e avaliação usando métricas como Acurácia, Precisão, Recall e F1-score.
4. **Geração do Artigo**: Análise dos resultados e documentação no formato de artigo científico (IEEE Conference Template).
5. **Apresentação**: Gravação de um vídeo explicativo com os principais resultados.

---

## Resultados Obtidos

- **Acurácia**:
  - ResNet50: 95.36%
  - EfficientNet-B0: 94.96%
  - AlexNet: 93.75%
  
- **Matriz de Confusão**:
  As matrizes de confusão foram geradas para cada modelo, disponíveis na pasta `Resultados`.
- **Gráficos de Treinamento**:
  Incluem curvas de erro e acurácia para os conjuntos de treino e validação.

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/BTMiranda/SIN393-Projeto2.git
   ```
2. Instale os requisitos:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o arquivo `Code.ipynb` em um ambiente compatível com Jupyter Notebook (como JupyterLab ou Google Colab).

## Referências

- [João Fernando Mari](https://github.com/joaofmari/SIN392_Introduction-to-digital-image-processing_2023)
- [PyTorch](https://pytorch.org/)
- [EfficientNet](https://github.com/lukemelas/EfficientNet-PyTorch)
- [Dataset Kaggle](https://www.kaggle.com/)
- [Template IEEE no Overleaf](https://www.overleaf.com/latex/templates/ieee-conference-template/grfzhhncsfqn)

---

## Participantes

- [Bernardo Teixeira de Miranda](https://github.com/BTMiranda)
- [Vinicius do Carmo Gomes](https://github.com/ViniciusGomesc) 
- [Phelipe Romano](https://github.com/phromanomr)
