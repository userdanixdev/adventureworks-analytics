# AdventureWorks Analytics

## Project Overview:
### Análise de Vendas e E-commerce

Este projeto utiliza o banco de dados AdventureWorks, um conjunto de dados fictício disponibilizado pela Microsoft para fins de demonstração, aprendizado e desenvolvimento de soluções de dados. Os dados simulam operações de uma empresa do setor de bicicletas e acessórios, incluindo informações relacionadas a vendas pela internet (e-commerce), clientes, produtos, datas, territórios e desempenho financeiro.

O objetivo deste projeto é explorar um cenário próximo ao encontrado em ambientes reais de Analytics, aplicando conceitos de SQL, modelagem de dados, transformação e tratamento de dados com dbt e visualização no Power BI.

*Observação: os dados utilizados são fictícios e destinados exclusivamente a estudos, demonstrações e práticas de análise de dados.*

---

A Microsoft disponibiliza diferentes versões do banco de dados AdventureWorks, incluindo versões para SQL Server e diferentes cenários de utilização.

As bases oficiais podem ser encontradas no repositório da Microsoft:

AdventureWorks Sample Databases - Microsoft:

[https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/adventure-works](https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/adventure-works)

---

Também é possível encontrar informações e downloads das bases de exemplo na documentação oficial do SQL Server:

[https://learn.microsoft.com/sql/samples/adventureworks-install-configure](https://learn.microsoft.com/sql/samples/adventureworks-install-configure)

*As diferentes versões permitem trabalhar com dados de períodos e estruturas distintas, sendo úteis para estudos de SQL, Business Intelligence, Data Analytics e Data Engineering.*

---

# Data Visualization:

Esta etapa representa a fase final. Onde há a transformação, modelagem, visualização e análise dos dados do projeto de modernização e migração do dataset *AdventureWorksDW2022* para o Microsoft Azure.

[View Data Visualization](https://github.com/userdanixdev/azure-adventureworks/tree/data-visualization){ .md-button }

---

Após as etapas de restauração do banco de dados, preparação da infraestrutura e desenvolvimento do processo de migração, os dados disponibilizados no ambiente de destino passam por uma camada de transformação e modelagem utilizando dbt (data build tool).

[View Source Code](https://github.com/userdanixdev/azure-adventureworks){ .md-button }
[View Migration Code](https://github.com/userdanixdev/azure-adventureworks/tree/migration-azure-database){ .md-button }

---

## *Architecture:*

![Arquitetura](../images/fluxo_completo_project_adventureworks.png)

---

## *Perguntas de Negócio*

Conheça as principais perguntas que orientaram a análise e ajudaram a definir os objetivos do projeto.

## *Insights*

Explore os principais resultados e descobertas identificados a partir da análise dos dados.

## *Boas Práticas*

Conheça as práticas de arquitetura e ETL de dados e Analytics aplicadas ao longo do desenvolvimento do projeto.

## *Acessos*

Acesse o repositório no GitHub, o dashboard desenvolvido no Power BI e a documentação do dbt.

[View Release](https://github.com/userdanixdev/azure-adventureworks/releases#release-1.2.0){ .md-button }
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmFiMWE4YWItNmM5Yi00ZDE3LWEzYWUtYzlmYmJlYjAwZGNiIiwidCI6ImVkNTJhZDViLTU0YzktNDNlZi04YmNhLThlOWY4Y2U0Zjc1ZiJ9){ .md-button .md-button--primary }
[View dbt docs](https://userdanixdev.github.io/azure-adventureworks/#!/overview/dbt_adventureworks2022){ .md-button }

---