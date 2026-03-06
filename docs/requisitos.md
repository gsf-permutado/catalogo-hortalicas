# Documento de Requisitos - Projeto Catálogo Agrícola

Este documento detalha as funcionalidades (Requisitos Funcionais) e as restrições (Requisitos Não Funcionais) do sistema.

## 1. Requisitos Funcionais (RF)
*O que o sistema deve fazer.*

| ID | Requisito | Descrição |
| :--- | :--- | :--- |
| **RF-01** | **Consulta de Catálogo** | O sistema deve permitir que o usuário navegue por uma lista de pragas, fungos e deficiências. |
| **RF-02** | **Filtro por Sintomas** | O usuário deve conseguir filtrar os problemas selecionando sintomas visuais (ex: manchas, furos, murchamento). |
| **RF-03** | **Detalhamento Científico** | Cada item deve exibir uma descrição técnica, causas prováveis e recomendações de manejo. |
| **RF-04** | **Galeria de Imagens** | O sistema deve exibir fotos de alta qualidade para comparação visual no campo. |
| **RF-05** | **Busca Global** | Deve haver uma barra de pesquisa para busca por nome popular ou científico. |

## 2. Requisitos Não Funcionais (RNF)
*Como o sistema deve ser (performance, segurança, usabilidade).*

| ID | Requisito | Descrição |
| :--- | :--- | :--- |
| **RNF-01** | **Responsividade** | A interface deve ser adaptável a diferentes tamanhos de tela (Mobile-First). |
| **RNF-02** | **Performance** | O carregamento inicial da página não deve ultrapassar 3 segundos em conexões 3G. |
| **RNF-03** | **Disponibilidade** | O sistema deve ser hospedado em plataforma estável (ex: GitHub Pages ou Vercel). |
| **RNF-04** | **Usabilidade** | A interface deve possuir alto contraste para facilitar a leitura sob luz solar direta. |
| **RNF-05** | **Tecnologia** | O projeto deve ser desenvolvido utilizando tecnologias Web padrão (HTML5, CSS3 e JavaScript). |

---

---

## 3. Regras de Negócio (RN)
*Premissas e limitações do projeto.*

* **RN-01:** Todas as informações de tratamento devem conter uma nota de rodapé recomendando a consulta a um engenheiro agrônomo.
* **RN-02:** O sistema não terá área de login para o produtor; o acesso às informações de consulta será público e imediato.