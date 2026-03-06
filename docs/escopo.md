# Escopo do Projeto: Microsite de Diagnóstico Agrícola (DF)

## 1. Definição Central do Problema
Produtores rurais do Distrito Federal enfrentam desafios fitossanitários que comprometem a saúde das culturas. A dificuldade de acesso a diagnósticos rápidos e a complexidade da linguagem científica disponível tornam o manejo de pragas e doenças ineficiente, gerando perdas econômicas e uso inadequado de defensivos.

## 2. Solução Proposta: Microsite Master-Detail
Para democratizar o acesso à informação, propõe-se o desenvolvimento de um **Microsite de Guia Fitossanitário**. A solução abandona a complexidade de bancos de dados dinâmicos em favor de uma arquitetura estática de alto desempenho:

* **Página Mestra (Master):** Uma Landing Page que funciona como índice visual das 10 principais hortaliças do DF (identificadas no documento de contexto).
* **Páginas de Detalhe (Detail):** Documentos individuais para cada patologia, permitindo um aprofundamento técnico sem sobrecarregar a navegação do usuário.

---

## 3. Objetivos do Desenvolvimento

### 3.1 Objetivo Geral
Desenvolver uma ferramenta digital estática, leve e intuitiva para auxiliar produtores rurais na identificação visual de pragas e doenças, promovendo o manejo sustentável no cinturão verde do DF.

### 3.2 Objetivos Específicos
* **Curadoria de Conteúdo:** Catalogar as patologias mais recorrentes nas culturas de maior relevância regional (Tomate, Alface e Pimentão) com base em fontes como a Embrapa.
* **Arquitetura de Páginas Estáticas:** Implementar a navegação via links diretos entre a página principal e as páginas de diagnóstico, garantindo compatibilidade com navegadores básicos.
* **Desenvolvimento Mobile-First:** Criar um layout responsivo focado na usabilidade sob condições de campo (alto contraste e fontes legíveis).
* **Otimização de Carregamento:** Minimizar o uso de scripts externos e imagens pesadas para assegurar a funcionalidade em redes móveis instáveis (2G/3G).

## 4. Diferenciais da Abordagem Técnica
1.  **Baixa Manutenção:** Por ser um site estático, não exige servidor de banco de dados, reduzindo custos e complexidade técnica.
2.  **Acessibilidade Offline:** Uma vez carregado no navegador, o acesso às informações entre as páginas é mais rápido e consome menos dados.
3.  **Foco em Resultados:** Prioriza a clareza visual (fotos e sintomas) em vez de funcionalidades burocráticas como login ou cadastros.

## 5. Delimitação de Entrega (MVP)
Para o cronograma de 3 meses, o projeto focará em:
* Landing Page completa com as 10 culturas listadas.
* Páginas de detalhes completas para as culturas de **Tomate, Alface e Pimentão** (as de maior participação estimada).