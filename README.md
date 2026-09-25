# 🧠 Deep Learning: TensorFlow vs PyTorch

Comparação de uma rede neural para classificação de imagens
utilizando TensorFlow/Keras e PyTorch sobre o dataset MNIST.

## 📌 Sobre o projeto

Este projeto surgiu a partir de uma proposta prática da minha
pós-graduação em Inteligência Artificial para a Estratégia dos
Negócios.

A partir da atividade, decidi explorar um pouco além da proposta
inicial e implementar o mesmo problema utilizando dois frameworks
de Deep Learning:

- TensorFlow/Keras
- PyTorch

O objetivo foi entender na prática as diferenças de implementação
e comparar os resultados obtidos pelos dois modelos.

## 🎯 Objetivos

- Implementar uma rede neural para classificação de imagens;
- Trabalhar com o dataset MNIST;
- Realizar pré-processamento dos dados;
- Implementar o modelo em TensorFlow/Keras;
- Implementar o mesmo modelo em PyTorch;
- Avaliar os modelos utilizando métricas de classificação;
- Comparar os resultados.

## 🧠 Arquitetura

          ENTRADA
       28 × 28 pixels
             │
             ▼
          Flatten
             │
             ▼
        784 neurônios
             │
             ▼
       ┌─────────────┐
       │ Dense 128   │
       │    ReLU     │
       └─────────────┘
             │
             ▼
       ┌─────────────┐
       │ Dense 64    │
       │    ReLU     │
       └─────────────┘
             │
             ▼
       ┌─────────────┐
       │ Dense 10    │
       │  Classes    │
       └─────────────┘
             │
             ▼
        0 1 2 3 ... 9

## 📊 Resultados

| Métrica         | TensorFlow | PyTorch |
| --------------- | ---------: | ------: |
| Parâmetros      |    109.386 | 109.386 |
| Accuracy        |     97,72% |  97,70% |
| Macro Precision |     97,72% |  97,71% |
| Macro Recall    |     97,71% |  97,67% |
| Macro F1        |     97,71% |  97,69% |
| Weighted F1     |     97,72% |  97,70% |


## 🔎 Conclusão

Os dois modelos apresentaram desempenho muito semelhante no
experimento, com diferença de apenas 0,02 ponto percentual na
acurácia do conjunto de teste.

O experimento também permitiu observar diferenças na forma como
TensorFlow/Keras e PyTorch estruturam a definição e o treinamento
de redes neurais.

## 🛠️ Tecnologias

- Python
- TensorFlow
- Keras
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- MNIST

## 📚 Contexto acadêmico

Projeto desenvolvido como exploração prática a partir de uma
atividade da pós-graduação em Inteligência Artificial para a
Estratégia dos Negócios.
