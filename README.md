# Fluxograma de Arquitetura Local com Indicação de Falhas

Este projeto apresenta um fluxograma detalhado da arquitetura local para um sistema de processamento de dados. O fluxograma inclui etapas principais, subetapas e indicações de falhas em cada etapa do processo.

## Descrição

O fluxograma é uma representação visual da arquitetura do sistema, mostrando as seguintes etapas principais:

1. **Coleta de Dados**
2. **Preprocessamento de Dados**
3. **Normalização de Dados**
4. **Detecção de Outliers**
5. **Armazenamento de Dados**
6. **Visualização**
7. **Ação Corretiva**

Cada etapa principal é subdividida em subetapas, e foram adicionados nós de falha para cada etapa, com mensagens de erro específicas para indicar possíveis problemas.

## Estrutura do Fluxograma

- **Coleta de Dados**
  - Subetapas: API, InduSoft
- **Preprocessamento de Dados**
  - Subetapas: Tratamento de Dados, Limpeza de Dados
- **Normalização de Dados**
  - Subetapas: Escalonamento, Normalização
- **Detecção de Outliers**
  - Subetapas: Método de ML, Análise Estatística
- **Armazenamento de Dados**
  - Subetapas: MySQL, SQLite
- **Visualização**
  - Subetapas: Criação de Relatórios, Dashboards
- **Ação Corretiva**
  - Subetapas: Automatização de Processos, Correção de Dados

Cada etapa principal é conectada a um nó de falha correspondente, e todas as falhas são dirigidas para ações corretivas para tratamento dos erros.

## Requisitos

Para executar o código e gerar o fluxograma, você precisa ter:

- **Python** (versão 3.6 ou superior)
- **Graphviz** (instalado e configurado no sistema)
- **IPython** (para exibição no Jupyter Notebook)

## Instalação

Para instalar as dependências necessárias, execute o seguinte comando:

```bash
pip install graphviz ipython
