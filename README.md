# Projeto de Banco de Dados – Loja de Vinhos  
Atividade Somativa 2 – Banco de Dados para TI – PUCPR  
Autora: **Francine Basagni**

# Projeto de Banco de Dados – Loja de Vinhos

Este repositório reúne o desenvolvimento completo da Atividade Somativa 2, voltada para a modelagem e implementação de um banco de dados para uma loja de vinhos.
A proposta foi transformar um conjunto de requisitos teóricos em um banco de dados real, funcional e organizado — passando pelas etapas de modelo conceitual, modelo lógico, modelo físico e consultas em SQL.

O foco deste projeto foi aplicar, na prática, os conceitos trabalhados na disciplina e demonstrar clareza, estrutura e entendimento do processo de construção de um banco relacional.

---

## 1. Objetivo do Projeto

O banco de dados foi estruturado para registrar e relacionar informações essenciais sobre:

 - Vinhos e suas características (nome, tipo, ano, descrição).
 - Vinícolas responsáveis pela produção.
 - Regiões às quais essas vinícolas pertencem.
 - Relacionamentos entre essas entidades, preservando a integridade referencial.

Toda a modelagem foi pensada para garantir consistência, integridade referencial e facilidade na obtenção de informações relevantes.

---

## 2. O que foi desenvolvido?

Este repositório apresenta todas as entregas solicitadas na atividade, incluindo:

 - Modelo conceitual (DER) representando as entidades e seus relacionamentos
 - Modelo lógico criado no MySQL Workbench
 - Modelo físico completo em SQL (DDL + inserts)
 - Aplicação correta de chaves primárias e estrangeiras
 - Consultas SQL utilizando junções para integrar as informações
 - Criação de um usuário com permissões específicas (Sommelier)
 - Organização dos arquivos de forma clara e separada por etapa

Todo o processo foi conduzido seguindo boas práticas, com foco em organização e compreensão do fluxo de modelagem.
---

## 3. Estrutura do Repositório

```plaintext
/loja_vinhos
├── modelo_conceitual.png
├── modelo_logico.png
├── modelo_fisico.sql
├── consultas.sql
├── usuario_sommelier.sql

```

Descrição dos arquivos:

 - modelo_conceitual.png — diagrama DER
 - modelo_logico.png — modelo lógico exportado do MySQL Workbench
 - modelo_fisico.sql — criação das tabelas e inserção dos registros
 - consultas.sql — consultas solicitadas na atividade
 - usuario_sommelier.sql — usuário com permissões restritas conforme regras do enunciado.

---

## 4. Tecnologias Utilizadas

- MySQL Workbench  
- MySQL Server  
- SQL padrão (DDL, DML e DQL)

---

## 5. Como Executar

Para reproduzir o projeto em qualquer ambiente MySQL:

 1. Crie um schema no MySQL.
 2. Execute o arquivo modelo_fisico.sql para gerar as tabelas e popular os dados.
 3. Utilize o arquivo consultas.sql para validar as consultas principais.
 4. Caso queira testar permissões de usuário, execute também usuario_sommelier.sql.

---

## 6. Entregáveis Atendidos

Conforme solicitado na atividade:

-  Modelo Conceitual completo.  
-  Modelo Lógico no MySQL Workbench.  
-  Modelo Físico implementado.  
-  5 registros mínimos em cada tabela.  
-  Consulta trazendo nome do vinho, ano, vinícola e região.  
-  Criação do usuário *Sommelier* com permissões restritas e limite de consultas.  
-  Todos os arquivos estruturados e entregues.

---

## 7. Considerações Finais

Este projeto reúne, de forma direta e organizada, todo o processo de modelagem de um banco de dados — desde a compreensão das entidades até a implementação final em SQL.
Além de atender aos requisitos acadêmicos, o trabalho demonstra entendimento prático de modelagem, relacionamento entre tabelas, integridade referencial e boas práticas de organização.
O repositório também serve como referência para estudos futuros ou início de projetos mais complexos envolvendo banco de dados.

