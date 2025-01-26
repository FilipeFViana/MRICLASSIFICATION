# MRICLASSIFICATION
Classificação de Tumores Cerebrais com Redes Neurais Convolucionais

Este projeto tem como objetivo construir um pipeline de aprendizado profundo para classificação de tumores cerebrais utilizando redes neurais convolucionais pré-treinadas, incluindo ResNet, DenseNet e Inception v3. O modelo foi treinado, validado e testado em um dataset organizado nas categorias de tumor, com o uso de técnicas avançadas de Data Augmentation para melhorar a generalização.

🧠 Objetivo

Desenvolver e comparar modelos de classificação de imagens para detecção e diferenciação de tumores cerebrais em exames de ressonância magnética (MRI). O trabalho utiliza arquiteturas de redes neurais convolucionais amplamente reconhecidas para realizar uma análise quantitativa e qualitativa do desempenho.

⚙️ Funcionalidades
- Treinamento com Otimização de Hiperparâmetros: Explora diferentes combinações de taxa de aprendizado, otimizadores e tamanhos de batch para cada modelo.
- Treinamento com Parâmetros Fixos: Fornece uma abordagem direta para avaliação rápida do pipeline.
- Data Augmentation: Inclui transformações como rotação, inversão horizontal e ajustes de brilho/contraste para aumentar a robustez do modelo.
- Métricas de Avaliação: Acurácia, precisão, recall, F1-score e matriz de confusão são calculadas para análise do desempenho.

📂 Estrutura do Projeto

📁 DataSet/
    Training/
    Validation/
    Testing/
📁 Models/
    Salvar os modelos treinados (.pth)
📁 Results/
    Matriz de Confusão
    Métricas de Avaliação


🛠️ Tecnologias Utilizadas
- Python: Linguagem principal.
- PyTorch: Framework para aprendizado profundo.
- Torchvision: Modelos pré-treinados e ferramentas para processamento de imagens.
- Scikit-learn: Cálculo de métricas e visualização da matriz de confusão.
- Matplotlib: Visualização de gráficos e resultados.
- TQDM: Barras de progresso para o treinamento.


Pré-requisitos

Certifique-se de ter o Python instalado na versão 3.8 ou superior e o ambiente configurado. O projeto pode ser executado em qualquer IDE ou diretamente no Google Colab.

Clone o repositório:

git clone https://github.com/seuprojeto/MRICLASSIFICATION.git
cd MRICLASSIFICATION

Crie e ative um ambiente virtual (opcional):

python -m venv venv
source venv/bin/activate # Linux/Mac
venv\Scripts\activate    # Windows

Instale as dependências necessárias:

pip install torch torchvision scikit-learn matplotlib tqdm


📊 Resultados
Os modelos foram avaliados em termos de:


- Acurácia: Percentual de predições corretas.
- Matriz de Confusão: Para análise detalhada das classes.
- Comparação de Modelos: ResNet, DenseNet e Inception v3.
