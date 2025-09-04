# 📌 Requisitos do Sistema HelpDesk com IA

## 1. Introdução
Este documento descreve os requisitos funcionais e não funcionais do sistema **HelpDesk com Inteligência Artificial**, desenvolvido como parte do PIM.  
O objetivo é fornecer uma visão clara do que o sistema deve realizar e as restrições que devem ser consideradas.

---

## 2. Escopo
O sistema HelpDesk permitirá que clientes abram chamados de suporte técnico por meio de uma plataforma (web, desktop e mobile).  
Uma IA tentará resolver o problema automaticamente. Caso não consiga, o chamado será encaminhado para um funcionário humano.  

Principais atores:
- **Cliente** – abre chamados e acompanha status.  
- **Funcionário** – atende chamados que a IA não resolveu.    

---

## 3. Requisitos Funcionais (RF)
A tabela abaixo lista as funcionalidades que o sistema deve possuir.

| ID   | Requisito Funcional | Descrição |
|------|---------------------|-----------|
| RF01 | Cadastro de Cliente | O sistema deve permitir que clientes se cadastrem. |
| RF02 | Login e Autenticação | O sistema deve permitir login seguro de clientes, funcionários e administradores. |
| RF03 | Abertura de Chamados | O cliente deve poder abrir chamados de suporte. |
| RF04 | Atendimento por IA | O sistema deve utilizar IA para tentar resolver o chamado automaticamente. |
| RF05 | Escalonamento de Chamados | Se a IA não resolver, o chamado deve ser encaminhado a um funcionário. |
| RF06 | Priorização de Chamados | O sistema deve classificar chamados por prioridade. |
| RF07 | Chat com Atendente | O cliente deve poder conversar com um atendente humano. |
| RF08 | Gestão de Usuários | O administrador deve poder cadastrar, editar e remover usuários. |
| RF09 | Relatórios | O administrador deve poder gerar relatórios de atendimentos. |

---

## 4. Requisitos Não Funcionais (RNF)
Estes requisitos descrevem restrições e características do sistema.
