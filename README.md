# 🚗 Esquema Conceitual - Oficina Mecânica

Este projeto apresenta um **esquema conceitual** de banco de dados para um sistema de controle e gerenciamento de ordens de serviço de uma **oficina mecânica**. Foi desenvolvido como parte de um desafio prático para aprimorar a modelagem de dados e está disponível para consulta e futuras melhorias.

## 📘 Descrição

O sistema permite que **clientes levem veículos à oficina** para serviços como consertos e revisões. Cada veículo é atribuído a uma equipe de mecânicos, que preenche uma **Ordem de Serviço (OS)** com os serviços a serem executados, bem como as peças necessárias.

### Principais funcionalidades do sistema:

- Cadastro de clientes e seus veículos
- Cadastro de equipes e mecânicos
- Criação e gestão de Ordens de Serviço
- Associação de serviços e peças a cada OS
- Cálculo de custos com base na mão de obra e peças utilizadas
- Controle de status e prazos das OS

## 🧱 Modelagem

O esquema inclui as seguintes entidades:

- Cliente
- Veículo
- Equipe
- Mecânico
- Ordem de Serviço (OS)
- Serviço
- Peça
- Tabelas associativas: OS_Servico, OS_Peca

## 🔎 Observações

Caso a narrativa não tenha especificado detalhes como o nome da equipe, fornecedor da peça, tempo estimado de serviço, ou status da OS, foram adicionados com base em **interpretação de contexto** e **boas práticas de modelagem**.

## 📎 Arquivos

- `esquema-conceitual.drawio` — Arquivo com o diagrama do modelo ER.
- `modelo-relacional.pdf` — Documento com a transformação para o modelo relacional (opcional).

---

Feito com ❤️ por Gustavo Raineri
