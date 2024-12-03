# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Administração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Classificação de Grãos de Trigo com Machine Learning

## Nome do grupo

## 👨‍🎓 Integrantes:

- <a href="https://www.linkedin.com/in/alexomantovani/">Alexandre Oliveira Mantovani</a>
- <a href="https://br.linkedin.com/in/ricardolcoube/">Ricardo Lourenço Coube</a>
- <a href="https://www.linkedin.com/company/">Edmar Ferreira Souza</a>

## 👩‍🏫 Professores:

### Tutor(a)

- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>

### Coordenador(a)

- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

---

## 📜 Descrição

Este projeto tem como objetivo automatizar a classificação de variedades de grãos de trigo (Kama, Rosa, Canadian) com base em suas características físicas, utilizando técnicas de aprendizado de máquina. Por meio do **"Seeds Dataset"** disponível no repositório UCI Machine Learning, foi desenvolvida uma solução que otimiza o processo manual atualmente utilizado por cooperativas agrícolas, tornando-o mais eficiente e preciso.

O projeto segue a metodologia **CRISP-DM** e está estruturado nas seguintes etapas:

1. **Análise e Pré-processamento dos Dados**:

   - Carregamento do conjunto de dados e análise estatística.
   - Exploração visual com histogramas, boxplots e gráficos de dispersão.
   - Tratamento de valores ausentes e padronização das características.

2. **Implementação e Comparação de Algoritmos**:

   - Desenvolvimento de modelos de aprendizado supervisionado: K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Random Forest, Naive Bayes e Regressão Logística.
   - Avaliação inicial com métricas como acurácia, precisão, recall, F1-score e matriz de confusão.

3. **Otimização de Modelos**:

   - Ajuste de hiperparâmetros utilizando Grid Search para melhorar o desempenho.

4. **Interpretação dos Resultados**:
   - Comparação detalhada do desempenho dos modelos.
   - Identificação do modelo mais adequado para o problema com base em métricas de avaliação.

---

## 📁 Estrutura de Pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: arquivos relacionados a elementos visuais, como imagens.
- <b>scripts</b>: arquivos principais, incluindo notebooks e o conjunto de dados.
- <b>README.md</b>: guia e explicação geral sobre o projeto.

---

## 🔧 Como Executar o Código

1. Certifique-se de ter instalado as bibliotecas necessárias:
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Abra o script do programa "analisando_seeds.ipynb"
3. Execute o programa célula por célula

### 📊 Funcionalidades

**Classificação Automática**

O modelo desenvolvido classifica variedades de grãos de trigo com base nos seguintes atributos:

- Área
- Perímetro
- Compacidade
- Comprimento do Núcleo
- Largura do Núcleo
- Coeficiente de Assimetria
- Comprimento do Sulco do Núcleo

**Algoritmos Utilizados**

Os seguintes algoritmos foram implementados e avaliados:

- K-Nearest Neighbors (KNN): Modelo baseado na proximidade dos dados.
- Support Vector Machine (SVM): Separação de dados usando hiperplanos.
- Random Forest: Conjunto de árvores de decisão.
- Naive Bayes: Modelo probabilístico baseado no teorema de Bayes.
- Logistic Regression: Modelo linear para classificação binária ou multiclasses.

**Melhor Modelo**

Após avaliação e otimização, o melhor modelo foi identificado com base em acurácia e outras métricas, proporcionando uma solução precisa e robusta para classificação.

## 🗃 Histórico de lançamentos

- 1.0.0 - 03/12/2024
  - Desenvolvimento do pipeline de classificação de grãos de trigo com machine learning.

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
