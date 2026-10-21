# Hefesto_API
Solução de Business Intelligence para mapeamento e análise de indicadores trabalhistas e empresariais do polo automotivo de São José dos Campos (Projeto Hefesto).
# 🏭 Projeto Hefesto | Observatório da Montagem Automotiva

**Repositório oficial do Projeto de Aprendizagem por Projetos Integrados (API) - FATEC Prof. Jessen Vidal (São José dos Campos)**

O **Projeto Hefesto** é uma solução de *Business Intelligence* (BI) focada no mapeamento, organização e análise do setor de montagem automotiva em São José dos Campos. O objetivo é transformar bases de dados públicas fragmentadas em um painel de controle gerencial e interativo, auxiliando na tomada de decisão estratégica e no monitoramento do polo industrial.

---

## 🎯 Objetivos do Projeto
* **Mapeamento Setorial:** Localizar e identificar empresas e suas atividades ao longo do município.
* **Integração de Dados:** Unificar informações empresariais e trabalhistas (estoque e fluxo de empregos) em um modelo relacional.
* **Monitoramento Estratégico:** Fornecer dashboards interativos para analisar a evolução de contratações, demissões, remuneração média e perfil demográfico da força de trabalho automotiva.

## 🛠️ Arquitetura e Tecnologias Utilizadas

O projeto utiliza uma esteira de dados automatizada (ETL) e modelagem analítica avançada:

* **PowerShell:** Utilizado para a extração, filtragem inicial e padronização (limpeza) de grandes volumes de dados brutos diretamente das bases governamentais.
* **Microsoft Power BI:** Ferramenta central para visualização de dados e construção de dashboards.
* **DAX (Data Analysis Expressions):** Criação de mais de 20 medidas calculadas para indicadores de emprego, remuneração e perfil.
* **Modelagem Dimensional (Star Schema):** Estruturação do banco de dados com 7 tabelas dimensão (Calendário, CNAE, Sexo, Raça/cor, Escolaridade, Faixa Etária, Ocupação) conectadas a 3 tabelas fato.

## 🗂️ Fontes de Dados (Bases Públicas)
Os dados foram coletados, validados e cruzados a partir de três fontes oficiais do Governo Federal:
1. **Receita Federal (Cadastro de CNPJ):** Dados de estabelecimentos, CNAE, endereços e localização.
2. **Ministério do Trabalho e Emprego (RAIS):** Estoque anual de vínculos empregatícios ativos.
3. **Ministério do Trabalho e Emprego (Novo CAGED):** Fluxo mensal de admissões e desligamentos.

## 🚀 Entregas e Funcionalidades (Sprint 1)
* Mapeamento geoespacial de 125 estabelecimentos distribuídos em 42 bairros de SJC.
* Integração das 3 bases de dados num modelo de dados unificado.
* Dashboard interativo com 4 páginas focadas em:
  * Distribuição e Concentração Geográfica (Mapeamento).
  * Evolução e Tipos de Emprego.
  * Perfil Demográfico dos Trabalhadores (Idade, Gênero, Escolaridade e Gap Salarial).
  * Movimentação de Mercado (Admissões vs. Desligamentos recentes).

---
*Desenvolvido pelo Grupo 3 (Hefesto) - Curso de Tecnologia em Gestão da Produção Industrial.*
