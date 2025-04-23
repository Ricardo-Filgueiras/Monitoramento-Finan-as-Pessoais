# Projeto de Monitoramento Básico de Despesas Pessoais

## Visão Geral

Este projeto tem como objetivo criar um sistema simples para registrar e analisar despesas pessoais. A ideia principal é aplicar conhecimentos em banco de dados, cloud e business intelligence para construir uma solução funcional, desde o armazenamento dos dados até a visualização das informações financeiras.

## Conceito

O fluxo de trabalho básico envolve:

1.  **Coleta/Registro:** Inserção de dados de transações financeiras (receitas e despesas) em um banco de dados relacional.
2.  **Armazenamento:** Utilização do PostgreSQL como sistema de gerenciamento de banco de dados (SGBD) para persistir as informações de forma estruturada.
3.  **Hospedagem:** Provisionamento e gerenciamento da infraestrutura para o banco de dados na nuvem utilizando o Amazon Lightsail, garantindo acessibilidade e escalabilidade simplificada.
4.  **Análise e Visualização:** Conexão do Power BI ao banco de dados hospedado no Lightsail para criar dashboards interativos que permitam analisar os padrões de gastos, receitas e o fluxo financeiro geral.

## Tecnologias Utilizadas

* **Banco de Dados:** PostgreSQL
* **Cloud:** Amazon Lightsail
* **Business Intelligence / Visualização:** Microsoft Power BI
* **(Opcional/Futuro):** Python/Django

## Objetivos de Aprendizagem

* Modelagem de dados relacionais para finanças pessoais.
* Manipulação de dados com SQL (CREATE TABLE, INSERT, SELECT, UPDATE, DELETE).
* Provisionamento e configuração básica de instâncias e bancos de dados no Amazon Lightsail.
* Gerenciamento de regras de firewall e segurança básica na nuvem.
* Conexão de ferramentas de BI (Power BI) a fontes de dados externas (PostgreSQL na nuvem).
* Criação de dashboards e relatórios financeiros básicos no Power BI.

## Estrutura do Repositório (Sugestão)

* `/sql`: Contém os scripts SQL para criação das tabelas e, opcionalmente, inserção de dados de exemplo.
* `/docs`: Documentação adicional, diagramas de modelo de dados, etc.
* `/powerbi`: Arquivo `.pbix` do Power BI (ou capturas de tela do dashboard final).
* `README.md`: Este arquivo.

## Como Usar/Replicar (Em Breve)

---

Sinta-se à vontade para adaptar e expandir este texto conforme seu projeto evolui!
