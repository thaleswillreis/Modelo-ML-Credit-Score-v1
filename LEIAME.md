# Modelo de Regressão Linear para o cálculo de Score de Crédito de Clientes

Projeto destinado a criação, teste e avaliação de um exemplo de modelo de Regressão Linear para o cálculo de Score de Crédito de clientes.

## Fases do projeto

1. Análise exploratória dos dados

   * Verificação das características gerais dos dados;
   * Verificação de dados faltantes;
   * Verificação de dados inconsistentes;
   * Engenharia de atributos.
2. Visualização dos dados

   * Criação de tabelas e gráficos;
3. Transformação dos dados

   * Criação de novas colunas de dados;
   * Tratamento de dados nulos ou incorretos;
   * Exclusão de dados irrelevantes;
   * One Hot Encoding (adequação de tipos de acordo com o algorítimo);
   * Balanceamento da variável alvo e preditoras;
   * Separação dos dados de treinamento e de teste;
   * Normalização e/ou Padronização dos dados;
4. Criação, Teste e Avaliação do Modelo de Regressão Linear

   * Treinamento do modelo de Regressão Linear;
   * Teste do preditor;
   * Avaliação do modelo de Regressão Linear;

## Tecnologias Utilizadas

Esse projeto foi executado utilizando a linguagem Python no formato Jupyter Notebook. Foram utilizadas as bibliotecas Pandas (Carregamento, Limpeza e Análise dos Dados), Matplotlib e Seaborn (Visualização de dados e geração de gráficos), Sklearn (Criação, treinamento e avaliação do modelo de Machine Learning), Git (Versionamento de código) e a IDE escolhida foi o Visual Studio Code, rodando em um Debian Linux.

**Links relacionados:**

* [Debian Linux](https://www.debian.org/index.pt.html)
* [VSCode](https://code.visualstudio.com/)
* [Python](https://www.python.org/)
* [Jupyter](https://jupyter.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/#)
  [Sklearn](https://scikit-learn.org/stable/)
* [Git](https://git-scm.com/)

### Dependências e Versões Necessárias

Os softwares e bibliotecas utilizados no projetos tinham a seguintes versões:

* Python - Versão: 3.11.5
* Pandas - Versão: 2.2.0
* Matplotlib - Versão: 3.8.3 (matplotlib-inline: 0.1.6)
* Seaborn - Versão: 0.13.2
* Scikit-learn - Versão: 1.4.0

**Obs:** para mais detalhes consulte o aquivo "requirements.txt"

## Como rodar o projeto

Para rodar o projeto os seguintes métodos podem ser utilizados:

#### *Método 1:* Fazer o download do projeto

**Passo 1:**

Na pagina principal do projeto [https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git](https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git), busque pelo botão verde contendo o nome "<> Code".

**Passo 2:**

Clique em "Download ZIP"

**Passo 3:**

Descompacte a pasta que você terminou de baixar.

**Passo 4:**

Abra os projetos contendo a extensão ".ipynb".

#### *Método 2:* Clonar o repositório

Obs: Antes de proceder com esse processo, certifique-se de que o GitHub está devidamente configurado no seu computador.

**Passo 1:**

Crie uma pasta na qual você tenha permissão de escrita.

**Passo 2:**

Abra um terminal a partir da pasta recém criada ou navegue até ela pelo terminal.

**Passo 3:**

Na pagina principal do projeto [https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git](https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git), busque pelo botão verde contendo o nome "<> Code".

**Passo 4:**

Copie a URL do repositório.

**Passo 5:**

No terminal digite:

```
git Clone https://github.com/thaleswillreis/Modelo-ML-Credit-Score-v1.git
```

Aguarde a clonagem do repositório terminar.

**Passo 6:**

Abra os projetos contendo a extensão ".ipynb".

## Problemas enfrentados

O código poderá enfrentar problemas ao ser executado utilizando versões diferentes de linguagem e bibliotecas. Certifique-se de que as versões listadas no item "Dependências e Versões Necessárias" estão corretamente instaladas.

Caso já exista um ambiente de desenvolvimento com versões diferentes em uso na máquina utilizada, uma boa alternativa seria a criação de uma ambiente virtual de desenvolvimento. Em caso de dúvida, segue o link da documentação.
[Ambientes virtuais e pacotes](https://docs.python.org/pt-br/3/tutorial/venv.html)

## Resultados Obtidos (Métricas de Avalização)

**Coeficiente de Determinação (R²):**   0.3031101484841182
**Erro Médio Absoluto (MAE):**   20.426584637244353
**Erro Quadrático Médio (MSE):**   519.6339828679319
**Raiz Quadrada do Erro Quadrático Médio (RMSE):**   22.795481632725636

#### Sobre as métricas de Avaliação:

* *Coeficiente de Determinação (R²):*

R² é uma métrica que varia de 0 a 1, onde 1 indica que o modelo explica toda a variabilidade dos dados. Nesse caso, um R² de 0.3031 significa que o modelo explica aproximadamente 30.31% da variabilidade nos dados de teste. Um valor acima de 0.3 pode ser considerado moderado, mas, logicamente, isso depende do contexto e das expectativas para o problema específico.

* *Erro Médio Absoluto (MAE):*

É a média das diferenças absolutas entre as previsões do modelo e os valores reais. Neste caso, o MAE de 20.43 indica que, em média, as previsões do modelo têm um desvio absoluto de 20.43 unidades em relação aos valores reais.

* *Erro Quadrático Médio (MSE):*

É a média dos quadrados das diferenças entre as previsões do modelo e os valores reais. Neste caso, o MSE de 519.63 indica que, em média, o quadrado do desvio das previsões em relação aos valores reais é 519.63.

* *Raiz Quadrada do Erro Quadrático Médio (RMSE):*

É a raiz quadrada do MSE, e fornece uma medida do erro médio em termos da mesma unidade da variável de resposta. Neste caso, o RMSE de 22.80 indica que, em média, as previsões têm um desvio de aproximadamente 22.80 unidades em relação aos valores reais.

## Conclusão

Apesar de, como expliquei anteriormente, uma interpretação de "satisfatório" ou de "não satisfatório", depender do contexto específico do problema e das expectativas em relação ao resultado final, a construção e avaliação do modelo de Regressão Linear proposto inicialmente, foi bem sucedida. No entanto, devemos enfatizar, que durante os testes com os dados utilizados, o modelo obteve um desempenho apenas mediano e se mostrou insuficiente para ser utilizado em produção da forma que está, sendo preciso que seja feito ainda o aprimoramento do modelo.

## Próximos Passos

* *Explorar Modelos Mais Complexos:*

Considerar explorar modelos mais complexos, como modelos de árvores de decisão, random forests ou modelos de gradient boosting, para ver se conseguem capturar padrões mais intricados nos dados.

* *Engenharia de Características:*

Avaliar se a inclusão de novas características relevantes ou a transformação de características existentes pode melhorar o desempenho do modelo.

* *Ajuste de Hiperparâmetros:*

Experimentar ajustar os hiperparâmetros do modelo para otimizar o desempenho. Isso pode ser feito usando técnicas como validação cruzada.

* *Outros Modelos:*

Considerar explorar modelos diferentes para ver qual se ajusta melhor aos dados.

## Considerações Finais

Caso esse conteúdo seja útil para você, tenha alguma dúvida ou queira contribuir com alguma melhoria, deixe seu comentário ou contribua com o projeto.
