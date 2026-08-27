# 🧬 Análise Textual com Python – Caso COH-PIAH (USP/Coursera)

## 🎯 Objetivo  
Este projeto foi desenvolvido como **trabalho de conclusão do curso "Introdução à Ciência da Computação com Python"**, promovido pela **Universidade de São Paulo (USP)** na plataforma **Coursera**.

O desafio consiste em implementar um programa capaz de identificar similaridades linguísticas entre textos, simulando a detecção de plágio através da análise da assinatura textual de documentos.

As principais funcionalidades são:

1. Calcular a assinatura linguística de um texto.  
2. Comparar assinaturas de textos com uma assinatura referência.  
3. Avaliar qual texto entre vários é o mais similar ao infectado pelo “vírus” COH-PIAH.

---

## 🧪 Métodos Utilizados  
O programa utiliza os seguintes traços linguísticos para compor a assinatura de um texto:

- **Tamanho médio de palavra**  
- **Relação Type-Token** (palavras diferentes / total de palavras)  
- **Razão Hapax Legomana** (palavras únicas / total de palavras)  
- **Tamanho médio de sentença**  
- **Complexidade de sentença** (número de frases por sentença)  
- **Tamanho médio de frase**

A comparação entre assinaturas é feita com base na média das diferenças absolutas entre os traços.

---

## 🛠️ Código e Execução  
- A estrutura do código foi fornecida pela USP como esqueleto base.  
- As funções `compara_assinatura`, `calcula_assinatura` e `avalia_textos` foram implementadas por **Valdivan Ramos**.  
- Funções auxiliares foram adicionadas conforme necessário, mantendo a modularidade e clareza do código.

### ⚙️ Como Executar  
1. Baixe o arquivo `coh_piah.py`  
2. Execute em um ambiente Python compatível (como IDLE, VSCode, ou Jupyter Notebook)  
3. Informe os textos conforme solicitado pelo programa

---

## 💡 Tecnologias Utilizadas  
- **Linguagem de Programação Python**  
- **Programação modular e funcional**  
- **Manipulação de strings e listas**

---

## 📜 Créditos  
- **Curso e esqueleto base**: Universidade de São Paulo (USP) / Coursera  
- **Implementação lógica**: Valdivan F. Ramos

---

## 🧩 Perfil e Propósito Profissional

### 🎓 Autor  
**Valdivan F. Ramos** – 📌Analista de Sistemas Multidisciplinar | Mestrando em Eng. de Sistemas e Produtos | Docência/Pesquisa/Gestão | Eng. de Requisitos/CC | Ciência de Dados/Big Data | Dir. Digital/Compliance/LGPD | Redes/IoT/IIoT. Atuação com foco em análise de dados aplicada à educação, desenvolvimento técnico-científico e construção de ferramentas interativas que orientam a tomada de decisão.


### 📚 Educação com Propósito  
> “Ensinar linguagens de programação é mais do que ensinar algoritmos e códigos.  
> É educar mentes capazes de resolver problemas complexos da realidade, unindo teoria e prática, sem desprezar os valores humanos.  
> Mas educação e valores só fazem sentido quando estão a serviço da sociedade.”  
> — Valdivan F. Ramos

---

### 📄 Referência para Currículo Lattes  
**Título:** Detecção de Autenticidade em Texto com Python.  
**Tipo de produção técnica:** Desenvolvimento de Software  
**Ano:** 2024  
**Descrição:** Código fonte desenvolvido em Python para analisar textos informados por usuários e identificar padrões que indiquem possíveis plágios e práticas de cópia de textos. Código desenvolvido para trabalho de conclusão do curso da Universidade de São Paulo (USP), disponibilizado na plataforma de cursos da Coursera.  
**Disponível em:** [https://github.com/IvanEffierre/programa-coh-Piah](https://github.com/IvanEffierre/programa-coh-Piah)
