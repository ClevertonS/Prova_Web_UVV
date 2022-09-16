# Projetar um Banco de Dado.

## Definir e criar a estrutura que será utilizado para armazenar e gerenciar dado em um banco de dados
 - Quais Tabelas?
 - Quais os relacionamentos?
 - Quais campos em cada tabela?
 - Quais Regras de checagem?
 - Quais Campos são obrigatórios?

## Por que é importante projetar corretamente? 
Se não for bom:
 - Lento
 - Não vai atender as necessidade do usuário
 - manuntenção dificil
 - debug sql é dificil
 - redundância -> Inconsistênncia
 - tomada de decisões erradas
 - Dificiuldade de alterações futuras

## Etapas para um projeto de banco de dados.

### Engenharia de software
 1. Análise de requisitos 
    * O que os usúarios querem
 
 2. Escolha de um Modelo de dados
    * Existem + 20
    * Modelo Relacional
    * Modelo Objeto Relacional
    * Modelo Objeto
    * Modelo Grafos
    * Modelo Hierárquico
    * Modelo Rede
    * NOSQL

 4. Projeto Conceitual
    * Visão de Alto Nível
    * Não serve para implementação
    * Não é específico para nenhum SGBD.
    * **Serve para entedermos como a empresa e o sistema funcionam. Vai mostrar as entidades, os atributos e os relacionamentos entre as entidades** 
      * Entidades -> Qualquer coisa que eu quero guardar dados.
      * Atributos -> Qualidades, propriedades das entidades.
      * Relacionamentos -> Como as entidades se relacionam.
      
 ## Diagrama
