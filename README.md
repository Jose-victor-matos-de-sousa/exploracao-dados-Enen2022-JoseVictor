# exploracao-dados-Enen2022-JoseVictor
# Análise Estatística dos Microdados do ENEM

Este projeto realiza uma exploração estatística dos **Microdados do ENEM**, disponibilizados pelo INEP em formato CSV. O objetivo é aplicar técnicas de análise de dados utilizando Python para descrever e visualizar o desempenho dos participantes do exame.

## O que o código faz

1. **Descrição do Dataset**
   Apresenta informações básicas sobre o conjunto de dados: nome, link oficial, órgão responsável (INEP) e finalidade dos microdados do ENEM.

2. **Carregamento dos Dados**
   Lê o arquivo `MICRODADOS_ENEM_2022.csv` (ou outro ano escolhido) utilizando `pandas`.
   Para melhorar o desempenho, o dataset é reduzido por meio de uma **amostragem aleatória** de registros.

3. **Informações Gerais**
   Exibe:

   * Número de registros e colunas
   * Tipos de dados
   * Resumo estrutural do dataset

4. **Seleção de Variáveis Importantes**
   O código foca nas principais notas do ENEM:

   * `NU_NOTA_CN` – Ciências da Natureza
   * `NU_NOTA_CH` – Ciências Humanas
   * `NU_NOTA_LC` – Linguagens
   * `NU_NOTA_MT` – Matemática
   * `NU_NOTA_REDACAO` – Redação

5. **Estatísticas Descritivas**
   São calculadas automaticamente:

   * Média, mediana e moda
   * Valores mínimo e máximo
   * Desvio padrão e variância
   * Quartis e intervalo interquartil (IQR)
   * Contagem de valores ausentes

6. **Visualizações Gráficas**
   O código gera gráficos para melhor interpretação dos dados:

   * Histogramas das notas
   * Boxplot para identificação de outliers
   * Gráfico de dispersão entre Matemática e Redação

7. **Análise Automática**
   O script interpreta os resultados, indicando:

   * Assimetria das distribuições
   * Nível de dispersão dos dados
   * Possíveis indícios de outlier

## Objetivo

Demonstrar a aplicação de estatística descritiva e visualização de dados em um dataset público brasileiro, permitindo observar padrões de desempenho dos estudantes no ENEM.

## Observação

Devido ao grande volume dos microdados, é utilizada uma amostra aleatória do dataset para garantir melhor desempenho sem comprometer a representatividade estatística.
