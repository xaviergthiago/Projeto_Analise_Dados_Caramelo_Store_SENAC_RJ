# Projeto_Analise_Dados_Caramelo_Store_SENAC_RJ

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

Este repositório contém o projeto final desenvolvido para o componente curricular do curso de **Análise de Dados** do **SENAC RJ**. O objetivo principal é transformar dados brutos em insights estratégicos para a tomada de decisão na "Caramelo Store".

-----

## 👥 Equipe de Desenvolvimento

  * **Thiago Xavier** - [GitHub](https://github.com/xaviergthiago)
  * **Matheus Soares** - [GitHub](https://github.com/matheusfrsoares)
  * **Leonardo Faria** - [GitHub](https://github.com/itzleofaria)

-----

## 🚀 Sobre o Projeto

O projeto simula um cenário real de análise de dados de uma loja de varejo, cobrindo todo o pipeline de dados: desde a extração e limpeza até a visualização final em dashboards interativos.

### 🎯 Objetivos Principais:

  * Identificar o perfil demográfico dos clientes (faixas etárias).
  * Analisar o desempenho de vendas por categoria e estado.
  * Identificar **outliers** de preços e vendas utilizando métodos estatísticos (IQR).
  * Gerar relatórios de performance para suporte à gestão.

-----

## 🛠️ Tecnologias e Ferramentas Utilizadas

| Ferramenta | Aplicação |
| :--- | :--- |
| **Python** | Limpeza de dados (Pandas/NumPy) e análise estatística. |
| **SQL Server / Azure** | Armazenamento e gerenciamento das bases de dados. |
| **Power BI** | Criação de dashboards, modelagem DAX e visuais. |
| **Git & GitHub** | Controle de versão e colaboração da equipe. |

-----

## 📊 Estrutura da Análise

### 1\. Tratamento de Dados (Python)

Utilizamos scripts em Python para tratar valores nulos, converter tipos de dados e realizar o cálculo de quartis para detecção de anomalias:

  * Cálculo de **Q1, Q2 (Mediana) e Q3**.
  * Identificação de **outliers superiores e inferiores** no valor de venda.

### 2\. Modelagem e BI (DAX)

No Power BI, estruturamos o modelo de dados (Star Schema) e criamos medidas complexas em DAX para:

  * Segmentação por faixas etárias (Ex: 18-29, 30-39, etc).
  * Cálculo de performance de vendas por estado.
  * Indicadores de status de outliers em tempo real.

-----

## 📂 Como navegar neste repositório

  * `/data`: Bases de dados utilizadas (ou links para fontes públicas).
  * `/scripts`: Notebooks Python (.ipynb) com a análise exploratória.
  * `/dashboards`: Arquivo .pbix do Power BI com o relatório final.
  * `/docs`: Documentação adicional e badges do projeto.

-----

## 📝 Conclusão

Este projeto demonstra a capacidade técnica da equipe em integrar diferentes ferramentas do ecossistema de dados para resolver problemas de negócio reais, seguindo as diretrizes de excelência do **SENAC RJ**.

-----

### 📫 Contato

Para dúvidas ou sugestões, entre em contato com um dos membros da equipe através do GitHub.
