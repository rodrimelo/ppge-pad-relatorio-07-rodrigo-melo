# Relatório 07 — Dicionários no Cadastro da LEMA 🗂️

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&logo=Jupyter&logoColor=white)

| Campo | Informação |
|---|---|
| **Aluno(a)** | Rodrigo Massao Yoshihara de Albuquerque Melo |
| **Matrícula** | 20261002321 |
| **Disciplina** | Programação e Análise de Dados com Python — PPGE/UFPB |
| **Professor** | Prof. Dr. Hilton Ramalho |

## 📌 Sobre
Este repositório contém a resolução das 10 questões referentes ao **Relatório 07**, com foco na estrutura de dados de dicionários (`dict` e `defaultdict`), acesso seguro, atualização, iteração, aninhamento e *dict comprehensions*. Os exercícios simulam a migração de planilhas para um sistema de cadastro estruturado por rótulos semânticos na *LEMA Consultoria Econômica*, aplicando pares chave-valor a problemas de cadastro de clientes e ativos, parâmetros macroeconômicos, gestão de premissas e custos, filas de processos, orçamento por área, dados em painel por estado, gestão de filiais, tabelas de transações, precificação e consolidação de vendas.

### 🎯 Objetivos de Aprendizagem
- Criar e manipular dicionários utilizando diferentes construtores, garantindo chaves únicas e imutáveis (*hashable*), além de realizar acessos seguros com `.get()` e o operador `in` para evitar `KeyError`.
- Atualizar, mesclar e remover registros aplicando métodos e operadores específicos (`.update()`, `|`, `|=`, `.setdefault()`, `.pop()`, `del`, `.popitem()` e `.clear()`).
- Percorrer dicionários com `.keys()`, `.values()` e `.items()`, e modelar estruturas complexas com chaves compostas (tuplas), dicionários aninhados e listas de dicionários.
- Transformar, filtrar e inverter dados em uma linha com *dict comprehensions*, além de automatizar contagens e agrupamentos utilizando `defaultdict`.

## 📂 Arquivos
- `relatorio-07-rodrigo-melo.ipynb`: Notebook principal contendo todo o código-fonte, comentários explicativos, justificativas teóricas e as saídas das execuções.

## 🚀 Como visualizar e executar

Você pode interagir com este projeto de três formas:

### 1. Visualização Rápida (GitHub)
Basta clicar no arquivo `.ipynb` na lista de arquivos acima. O próprio GitHub renderizará o notebook com as saídas estáticas.

### 2. Execução Interativa (Google Colab)
Para rodar e modificar os códigos na nuvem, sem precisar instalar nada, clique no botão abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rodrimelo/ppge-pad-relatorio-07-rodrigo-melo/blob/main/relatorio-07-rodrigo-melo.ipynb)

### 3. Execução Local
Caso prefira rodar localmente na sua máquina:
1. Clone este repositório:
   ```bash
   git clone https://github.com/rodrimelo/ppge-pad-relatorio-07-rodrigo-melo.git
   ```
2. Acesse a pasta do projeto e abra o arquivo no Jupyter Notebook ou VS Code:
   ```bash
   cd ppge-pad-relatorio-07-rodrigo-melo
   jupyter notebook relatorio-07-rodrigo-melo.ipynb
   ```