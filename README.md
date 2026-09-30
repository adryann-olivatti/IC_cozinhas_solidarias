# 🥗 Análise de Renda por Organização Fornecedora — PAA Cozinhas Solidárias (2025)

Este repositório contém notebooks de análise de dados e documentação desenvolvidos para responder à seguinte pergunta de pesquisa:

> **"Qual é a renda por organização fornecedora, categorizada por tipo?"**

A análise consolida os dados abertos do **Programa de Aquisição de Alimentos (PAA)** destinados às **Cozinhas Solidárias** no ciclo de 2025.

---

## 📌 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [📊 Fontes de Dados](#-fontes-de-dados)
- [📁 Estrutura do Repositório](#-estrutura-do-repositório)
- [⚙️️ Como Executar no Google Colab](#️-como-executar-no-google-colab)
- [🔄 Metodologia e Pipeline de Dados](#-metodologia-e-pipeline-de-dados)
- [📈 Arquivos Exportados](#-arquivos-exportados)

---

## 📖 Sobre o Projeto

O **Programa de Aquisição de Alimentos (PAA)** na modalidade Cozinhas Solidárias conecta a produção da agricultura familiar, assentamentos da reforma agrária, comunidades quilombolas e pescadores artesanais com o combate à insegurança alimentar urbana e rural.

Este repositório realiza a extração, tratamento e consolidação dos repasses financeiros previstos pela **CONAB** (Companhia Nacional de Abastecimento) em parceria com o **MDS** (Ministério do Desenvolvimento e Assistência Social, Família e Combate à Fome), agrupando a renda total por organização fornecedora (CNPJ) e categorizando por perfil prioritário.

---

## 📊 Fontes de Dados

A análise integra três fontes principais de informação:

| Fonte | Formato | Link / Acesso | Função no Projeto |
| :--- | :--- | :--- | :--- |
| **Dados CONAB 2025** | Google Sheets (`.xlsx`) | [Acessar Planilha CONAB](https://docs.google.com/spreadsheets/d/1O_mmcnZ2QCBkA6juq_TzKYFv6KDwHsCU/edit) | **Base Operacional Bruta:** Contém os registros de itens fornecidos, valores previstos (R$), proponentes e tipo de organização. |
| **Catálogo de Dados** | JSON | [Ver no GitHub](https://github.com/TriangulosTecnologia/cozsolidarias/blob/main/public/dataset_catalogue.json) | **Metadados:** Esquema JSON indexando as coleções de dados por ID, licenças e procedência. |
| **Portal Cozinhas Solidárias** | Web | [Acessar Portal](https://cozsolidarias.triangulos.tech/dados) | **Documentação e Vocabulário:** Dicionário oficial de conceitos, histórico e regras de agregação. |

---

## 📁 Estrutura do Repositório

```text
.
├── notebook_renda_cozinhas_solidarias_corrigido.ipynb  # Notebook principal (Execução, Análise & Gráficos)
├── documentacao_metodologia_cozinhas_solidarias.ipynb  # Notebook explicativo (Guia Metodológico)
└── README.md                                           # Documentação do repositório
