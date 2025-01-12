# Análise de Crédito: Prevendo Inadimplência

Este projeto é uma análise de dados voltada para prever a inadimplência de clientes com base em um conjunto de dados de propostas e pagamentos. Ele inclui processos como tratamento de dados, análise exploratória e construção de modelos preditivos para classificação de risco de crédito.

## Objetivos do Projeto

1. **Identificar inadimplência:** Determinar clientes que não honraram pagamentos.
2. **Construção da variável resposta:** Criar a variável de classificação de "bom" ou "mau" pagador.
3. **Explorar os dados:** Realizar análise exploratória para compreender padrões e relações.
4. **Modelagem preditiva:** Desenvolver modelos de aprendizado de máquina para prever inadimplência.

## Estrutura do Projeto

1. **Carregamento de Dados:**
   - Importação de bibliotecas.
   - Leitura e consolidação dos dados de propostas e pagamentos.

2. **Tratamento de Dados:**
   - Limpeza de dados ausentes e inconsistentes.
   - Geração de variáveis derivadas relevantes.

3. **Análise Exploratória:**
   - Estatísticas descritivas.
   - Visualizações gráficas para entendimento dos dados.

4. **Modelagem Preditiva:**
   - Split dos dados em treino e teste.
   - Treinamento de modelos como Regressão Logística, Árvores de Decisão, e Random Forest.
   - Avaliação de métricas como AUC-ROC e acurácia.

5. **Resultados:**
   - Apresentação de insights.
   - Sugestões de aplicação prática.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone <URL-do-repositorio>
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook:
   ```bash
   jupyter notebook analise-de-credito-prevendo-inadimplencia.ipynb
   ```

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Contribuição

1. Fork este repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça commit das alterações:
   ```bash
   git commit -m 'Adiciona nova feature'
   ```
4. Envie as alterações para o repositório remoto:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob os termos da MIT License. Consulte o arquivo LICENSE para mais detalhes.

---

**Observações:** Caso deseje adicionar ou modificar algo, sinta-se à vontade para sugerir melhorias.
